# SSTV-Based IoT Data Acquisition and Analytics for remote regions

# Project Description

## Software Used
* Arduino IDE
* Python IDLE
* Thingspeak Data Analytics Tool

## Hardware Used
* Arduino Uno 
* DHT11 Temperature and Humidity Sensor
* Gas Sensor 
* Rain Sensor

## To run the python files install the dependencies using
```
pip install pyserial
pip install time
pip install os-win
pip install pyteserract
pip install pillow
```

## Make the following ciruit connections   
<p align="center">
  <img src="transmission_images\sketch.png">
</p>
<br>
<p align="center">
  <img src="transmission_images\circuit_diagram1.jpeg">
</p>

## Block Diagram 
<p align="center">
  <img src="transmission_images\block_diagram_iot_project.png">
</p>
<br>


## Flowchart
<p align="center">
  <img src="Flow.png">
</p>
<br>


## Roadmap
<p align="center">
  <img src="Roadmap.png">
</p>
<br>

## Upload the following code to the Arduino Uno Board
```
data_fetch_sstv.ino
```

## Arduino Serial Monitor 
<p align="center">
  <img src="transmission_images\Arduino Serial Monitor.png">
</p>
<br>
<p align="center">
  <img src="transmission_images\circuit_diagram2.jpeg">
</p>

## For transmitting the image(data) through sstv run the following 
```
python sstv_image_send.py
```

## For receiving back the image(data) and putting it up on thingspeak run the following 
```
python python2thingspeak.py
python masterclass.py
```

## SSTV 

## Transmission Transceiver and Receiver Transceiver
<p align="center">
  <img src="sstv_images\sstv1.png">
</p>
<br>

## Transmission
<p align="center">
  <img src="sstv_images\sstv2.png">
</p>
<br>

<p align="center">
  <img src="sstv_images\sstv4.png">
</p>
<br>

## Reception
<p align="center">
  <img src="sstv_images\sstv3.png">
</p>
<br>

<p align="center">
  <img src="sstv_images\sstv5.png">
</p>
<br>

<p align="center">
  <img src="sstv_images\sstv6.png">
</p>
<br>



## Text(Sensor Data) to Image
<p align="center">
  <img src="transmission_images\Text2Image.png">
</p>
<br>

## Image to Text(Sensor Data) 
<p align="center">
  <img src="reception_images\Image2Text.png">
</p>
<br>

## Thingspeak Channel

https://thingspeak.com/channels/1578749


<p>Channel Screenshot</p>
<p align="center">
  <img src="reception_images\thingspeak_channel.png">
</p>
 
 ## Video 
https://drive.google.com/drive/u/1/folders/1sVIIqHa9b1y_xpHrPC9CtE0m2hM2E_ia
