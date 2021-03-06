# MQTT-using-RPi-and-ESP8266
### Encouraged by  <a href="https://appiko.org/">Appiko</a>

### OBJECTIVE
To publish a message from Python Web server and ESP8266 subscribing the message using Raspberry Pi Musquitto broker.

### INTRODUCTION
<ul>
<li>In this project we shall see the wireless data transfer using MQTT protocol.<br>
<li>MQTT, or MQ Telemetry Transport, is a messaging protocol which allows multiple devices to talk to each other.<br>
<li>The MQTT protocol surrounds two subjects: a client and a broker.<br>
<li>An MQTT broker is a server, while the clients are the connected devices. When a device or client wants to send data to a server or broker it is called a publish. When the operation is reversed, it is called a subscribe.<br>
 </ul>

### WORKING
In this project you’ll create a standalone web server with a Raspberry Pi that can toggle two LEDs from an ESP8266 using MQTT protocol.<br>
In order to create the web server you will be using a Python microframework called Flask.
##### Working schematic
<img src="images/Capture1.JPG" width="800" height="400"> <br/>

### METHODOLOGY
<ul>
<li>Basic Raspberry Pi Setup
<li>Run and install Mosquitto broker
<li> Python web server with Flask
<li> Installing Python Paho-MQTT
<li> Creating the Python Script
<li>Creating the HTML File
<li> Programming the ESP8266
 </ul>
 
 ### SCHEMATIC
 <img src="images/Capture2.JPG" width="400" height="400"> <br/>
