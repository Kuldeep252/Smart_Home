# Smart_Home
This project is based upon arduino Uno and tries to model a house environment in presence of automtion.  It uses 3 sensors which provides input along with bluetooth transmitter/receiver.The output is delivered via servo motors and LED lights which controls the respective operations.Click [here](https://www.youtube.com/watch?v=IT07HGOR8mw&t=60s) to watch the video (sorry for noises in Audio)

## prerequisite
 
### Hardware
 *  [Rain sensor module](https://www.amazon.in/Generic-Rain-Sensitive-Sensor-Detection/dp/B00GTJLQSQ?tag=googinhydr18418-21&tag=googinkenshoo-21&ascsubtag=6f770f62-14d1-4016-a1b4-5fcfa200632e)
 *  Arduino Uno
 *  LED lights
 *  [LDR](https://www.amazon.in/LDR-Light-Dependent-Register-resistor/dp/B018LJPI76/ref=sr_1_2?ie=UTF8&qid=1512967276&sr=8-2&keywords=ldr) 
 *  [SG 90 Micro Servo](https://www.amazon.in/TowerPro-SG90-9g-Mini-Servo/dp/B076HP5MY1?tag=googinhydr18418-21&tag=googinkenshoo-21&ascsubtag=6f770f62-14d1-4016-a1b4-5fcfa200632e)
 *  [HC-05 Bluetooth Module](https://www.amazon.in/CENTIoT-Bluetooth-Transceiver-Module-Output/dp/B01LZTZVGQ?tag=googinhydr18418-21&tag=googinkenshoo-21&ascsubtag=6f770f62-14d1-4016-a1b4-5fcfa200632e)
 *  Connector wires
### Software
 *  Arduino IDE
 *  [MIT app creator](http://ai2.appinventor.mit.edu/)


## Getting Started
 Connection for each pin is given in the program.The 3D image of the house is also attached with this repository.
 MIT app creater will be used for development of android application.The app will transmits the signal(alphabetic code) to the bluetooth module,
 which will feed it to program where decoding of the signal takes place and operations are made accordingly.
 
 #### Proceed to Code file to know the software
