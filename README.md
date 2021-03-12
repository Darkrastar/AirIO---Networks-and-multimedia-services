# AirIO---Networks-and-Multimedia-Services
This is a project that was developed to show how an Internet of Things application works, transferring data using the REST protocol.

# Folder structure
``` 
AirIO--------------It is the page in PHP, it receives the data transferred from ubidots, by a REST request.
ArduinoProject-----It is the .ino.hex file that contains the logic of the Arduino code. 
JavaProject--------It is the Java code that contains the logic of collecting data using a serial port and then transferring it to a web server.
Taller14V2.pdsprj--Is the Proteus file that contains the Arduino Simultion and Sensors.
```
The proteus simulator simulates the collection of data in sensors that will then be sent to the Java project through a serial port. Then this data will be sent to the Ubidots platform, then the PHP page will retrieve it and display the data on a dashboard. 


# Testing video
https://user-images.githubusercontent.com/36736949/110251798-34825500-7f50-11eb-8324-1bf3c37e71fe.mp4




