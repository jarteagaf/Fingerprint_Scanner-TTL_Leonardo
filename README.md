[![FingerPrint Scanner](https://dlnmh9ip6v2uc.cloudfront.net/images/products/1/1/7/9/2/11792-01_medium.jpg)  
*Fingerprint Scanner - 5V TTL (GT-511C3)(SEN-11792)*](https://www.sparkfun.com/products/11792)

This library takes code, originally written by Josh Hawley, for the GT-511C3 sensor and changes it slightly to make it work on Arduino Leonardo using the built in UART module known as Serial1. It doesn't use the SoftwareSerial library, therefore uses less memory in the Arduino Leonardo. (I guess it will work with Arduino Mega as well) 

This is a great fingerprint module from ADH-Tech that communicates over TTL Serial so you can easily embed it into your next project. It was tested with GT-511C1R. Sometimes is necesary to initialize the arduino first and then connect the sensor. This is because when the arduino Leonardo is initialized, it sends data to the sensor. This data is kept in the sensor buffer which will cause conflicts when receiving the actual data.

This repository contains example code to work with it. 

Repository Contents
-------------------
* **/FPS_GT511C3** - Arduino Library to interface with the sensor.

License Information
-------------------

The original library license is as follows:

"	Created by Josh Hawley, July 23rd 2013
	Licensed for non-commercial use, must include this license message
	basically, Feel free to hack away at it, but just give me credit for my work =)
	TLDR; Wil Wheaton's Law "

"	Library updated by Juan Arteaga-Falconi, January 15th 2016."
