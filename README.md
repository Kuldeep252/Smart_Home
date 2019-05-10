# Smart_Home
![](https://raw.githubusercontent.com/Kuldeep252/Smart_Home/master/Home1.jpg)This project is modeled over Arduino Uno and tries to recreate a house environment in the presence of automation. It uses 3 sensors that provide input along with Bluetooth transmitter/receiver. The output is delivered via servo motors and LED lights which controls the respective operations. Click [here](https://www.youtube.com/watch?v=9MvSyy1kmfc) to watch the video.

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
The connection for each pin is given in the code attached. Some images of the house are also attached to this repository. MIT app creator was used for the development of the Android application.![](https://raw.githubusercontent.com/Kuldeep252/Smart_Home/master/screenshot.jpg)The app transmits the signal (alphanumeric code) to the Bluetooth module,
 which then feeds it to the program where decoding of the signal takes place and operations are selected accordingly.
 
 #### To access the code click [here](https://github.com/Kuldeep252/Smart_Home/blob/master/Code)
