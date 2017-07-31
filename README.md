# DooFon:  Local rain forecast system (IoT)

> [**Thai version**](https://github.com/HomeRuk/Doofon_SeniorProject/blob/master/README_TH.md)

> [**English version**](https://github.com/HomeRuk/Doofon_SeniorProject/blob/master/README.md)

### Highlight 
> **A local rain detection algorithms based on classification algorithms by Random forests (Random decision forests)**

   The system is designed to be utilized to detect current weather and rain forecast advance. In our system, Barometric pressure sensor, Humidity sensor, Thermistor, Light Sensor and etc. are IoT device and it continuously submits their measurements to our doofon management system. 
### Important Features

1. Local Weather -- display the local weather of IoT device updated every 5 minutes.
    * Atmospheric pressure (hPa)
    * Temperature (degree Celsius)
    * Humidity (percent %)
    * Dewpoint (degree Celsius)
    * Light (illuminance or lux)
    * Rain Detection
2. Local Rain Detection 
    * detect a rain in 2 hour advance and display the detail of the rain for IoT device. 
    * detect current rain and display the detail of the rain for IoT device. 
3. Rain monitoring 
    * monitor the rain forecast and sent instant notifications in case of rain forecast are more than or equal to user-defined values.
    * monitor the current rain of IoT device and sent instant notifications in case of raindrop.
4. Weather History - view the weather history of IoT device.

### Architecture for DooFon:  Local rain forecast system (IoT)
<img src="image/ArchitectDooFon.png" width="60%"/> 

### Sample system

#### Sample IoT Device
<img src="image/IoT.jpg" width="60%"/> 

#### Sample Mobile App 
<img src="image/app1.png" width="25%"/> <img src="image/app2.png" width="25%"/>

#### Sample Web 
<img src="image/01.png" width="90%"/> 
<img src="image/02.png" width="90%"/> 
<img src="image/03-2.png" width="90%"/> 


