# SmartTrashBin

## About Project 
This trash bin opens and closes its lid if it sees any rubbish in front of it. You just need to bring the rubbish to it and it'll open automatically and will wait for you to feed it more then after a certain delay it'll close automatically. Watch the video to see exactly what it can do.
[Click here](https://youtube.com/shorts/UzTi7w11_3U?feature=share)

Let's get started.
## Components
![FSAIWBLJHATN3BJ LARGE](https://user-images.githubusercontent.com/73534500/171785855-9dccf8c7-1f58-440c-8a9b-93221e054f66.jpg)
![FLS1O30JHATN1O9 LARGE](https://user-images.githubusercontent.com/73534500/171785845-e61a0f2d-3bb7-46ef-b241-880e9db9626e.jpg)
![FGBWAJPJHATN1QD LARGE](https://user-images.githubusercontent.com/73534500/171785857-09db7941-431e-4b37-a78a-97462b85a4e1.jpg)
![image](https://user-images.githubusercontent.com/73534500/171786467-107b8e20-b316-445c-b734-a78e6cdc1eb3.png)


+ Arduino Uno (any board)
+ Servo motor (We used micro servo sg90)
+ HCSR04 ultrasound sensor
+ Servo arms (beside the servo in pic 2)
+ Cardboard (just slice piece)
+ Trash bin

## Build the Circuit
![image](https://user-images.githubusercontent.com/73534500/171784371-60ba27b5-6621-48d6-866c-3b85e297cfad.png)

The circuit is so easy. As the servo and sonar only takes less power and we just powered them directly from Arduino 5v source.
+ Servo data (yellow) to pin 3 of arduino
+ Servo vcc (red) to 5v of Arduino
+ Servo ground (black/gray) to Arduino Gnd
+ Sonar sensor trig to Arduino 6
+ Sonar sensor echo to Arduino 5
+ Vcc to Arduino 5v
+ Gnd to Arduino Gnd

## Code 
We've programmed the Arduino so that if it sees any rubbish (literally anything) in a 40 cm range the servo goes to 90 degrees and hits the lid of the bin, so that the  lid is opened, waits for three seconds, then automatically turns to back and thus the lid gets closed.

## Contributors: Akzhol Suborov, Nazim Mukhtarbekov, Zhakyp Zhoomart uulu
