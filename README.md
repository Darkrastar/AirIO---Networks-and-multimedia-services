# AirIO---Networks-and-Multimedia-Services
This is a project that was developed to show how an Internet of Things application works, transferring data using the REST protocol.

# Folder structure
``` 
AirIO--------------It is the page in PHP, it receives the data transferred from ubidots, by a REST request.
ArduinoProject-----It is the .ino.hex file that contains the logic of the Arduino code. 
JavaProject--------It is the Java code that contains the logic of collecting data using a serial port and then transferring it to a web server.
AirIO.pdsprj--Is the Proteus file that contains the Arduino Simultion and Sensors.
```
The proteus simulator simulates the collection of data in sensors that will then be sent to the Java project through a serial port (VSPE). Then this data will be sent to the Ubidots platform, then the PHP page will retrieve it and display the data on a dashboard. 

# Versions
``` 
Software
PHP -----------------Version 7.2.34
Java-----------------Version 8 update 281 (compilation 1.8.0_281-b09)
Proteus--------------Version 8.5 SP0 (Build 22067)
Arduino--------------Version 1.8.12
Netbeans-------------Version 8.2 (Build 201609300101)
Visual Studio Code---Version 1.53.2
VSPE-----------------Version 6.2.9200.2
Xampp----------------Version 7.2.34

Library
ArduinoJson----------------------Vesrion 6.17.2
PanamaHitek_Arduino--------------Version 3.0.0
org.eclipse.paho.client.mqttv3---Version 1.1.0
``` 

# Testing video
https://user-images.githubusercontent.com/36736949/110251798-34825500-7f50-11eb-8324-1bf3c37e71fe.mp4




