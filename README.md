# OpenEpaperLinkHATagSources

Home-Assistant BLE Tags Yaml Scripts for OpenEpaperLink

## Folder Structure
### 1.54 Epaper-tags

#### Sources only tested with SoluM-1-54 E-Tags.
>- *1.54-aqara-tvoc-mini.yaml*
![Example of the Yaml script!](/images/1.54-aqara-tvoc-air.jpg)
      Implementation Zigbee Aqara TVOC AIR senordata for 1.54 E-Tags Version.
      This integration you must a Aqara Sensor in your Home Assistant.

>- *1.54-weather-wind-compass.yaml*
   Implementation from HACS Integration of Weather Cloudservice Wundergroundpws with my ecowitt weatherstation.

>    - *1.54-waste-collection-calender.yaml*
![Example of the Yaml script!](/images/1.54-waste-collections-calender.png)
      Implementation from HACS Integration of Müllkalender 1.54 E-Tags Version.
      This integration must config to your region for waste calender.

>    - *1.54-openuvindex_mini.yaml*
![Example of the Yaml script!](/images/1.54.openuvindex_mini.png)
      Implementation from HACS Integration OpenUV 1.54 E-Tags Version.
      This integration must config to your region acording documentation.      

>    - *1.54-ecowitt-wh51-soil.yaml*
![Example of the Yaml script!](/images/1.54.ecowitt_wh51_soil_mini.png)
      Implementation from Ecowitt-API for WH51 Sensor for 1.54 E-Tags Version.
      This integration must config sensors in ha-template-sensor.yaml or configuration.yaml .      

>    - *1.54-smart-air.yaml*
![Example of the Yaml script!](/images/1.54-smart_air.png)
      Implementation Zigbee Air Quality Sensor of SmartAir for 1.54 E-Tags Version.
      This integration must config sensors in ha-template-sensor.yaml or configuration.yaml .      

>    - *1.54-solar-rain-alert.yaml*
>    - *1.54-solar-rain-alerter-V2.yaml*
![Example of the Yaml script!](/images/1.54-solar_rain_mini.jpg)
      Implementation Zigbee Solarpanel based Sensor Rain Alerter for 1.54 E-Tags Version.
      This integration must configured template Sensors from your zigbee or configuration.yaml.
      In my usecase must rest template from zigbee instance from zigbeeToMqtt.V2 has new device Syntex and update View.

>    - *1.54-openplant-soil.yaml*
![Example of the Yaml script!](/images/1.54-openplant-motion-soil.jpg)
![Stand!](/images/1.54-openplant-stand.jpg)
      Implementation from zigbee-motion-soil based data and integration openplant for 1.54 E-Tags Version.
      This integration must config sensors in ha-template-sensor.yaml or configuration.yaml.
      I design Sensor and Plant Card for HA, my friend axel design a 3D Printer STL for stick to connect your E-Tag in plant.      
>    - *1.54-flightradar.yaml*
![Example of the Yaml script!](/images/1.54.flightradar.jpg)
      Implementation from flightradar data from nuernberg airport based data and integration flightradar for 1.54 E-Tags Version.
      This integration must config sensors in ha-template-sensor.yaml or configuration.yaml.
      I design Sensors and Yaml for HA.      

### 2.13-Gicisky-epaper-tags
>- *2.13.dwd-pollen-warning.yaml*
![Example of the Yaml script!](/images/2.13.dwd-pollenflug.jpg)        
        Implementation from HACS Integration of Weathercloudservice Deutschen Wetterdienst.

>- *2.13.openuv-warning.yaml*
![Example of the Yaml script!](/images/2.13.openuv.jpg)        
        Implementation from HACS Integration of Weathercloudservice OPENUV.

>- *2.13-hochwasserportal-pegelstaende.yaml*
        Implementation from HACS Integration of Hochwasserportal Service.
### 2.2-SoluM - E-Tags
#### Sources only tested with SoluM 2.2 E-Tags.
>- *2.2-openplant-soil.yaml*
![Example of the Yaml script!](/images/2.2.openplant-soil-soluM.jpg)        
        Implementation from HACS Integration of Openplant.
>- *2.2-ecowitt_wh51_soil_4ch.yaml*
![Example of the Yaml script!](/images/2.2.ecowitt_wh51_soil_4ch.jpg)        
        Implementation from HACS Integration of Ecowitt Soil WH51 Sensor 4 devices.
### 2.9-Gicisky - E-Tags
#### Sources only tested with Gicisky BLE EPD BWR 2.9 E-Tags.
>- *2.9-accu-weather.yaml*
![Example of the Yaml script!](/images/2.19.accuweather.jpg)        
        Implementation from HACS Integration of Weathercloudservice Accu Weather.

>- *2.9-hochwasserportal-pegelstaende.yaml*
![Example of the Yaml script!](/images/Wasserstand.svg)        
        Implementation from HACS Integration of Hochwasserportal Service.
>- *2.9-waste-collection.yaml*
        Implementation from HACS Integration of Müllkalender.
        This integration must config to your region for waste calender.  

### Handshow 3.5 E-Tags        
#### Sources only tested with Handshow 3.5 E-Tags.
>- *3.5-dwd-weather-warning.yaml*
        Implementation from HACS Integration of DWD Weather Warning.
>- *3.5-dwd-weather-lighting-warning.yaml*
![Example of the Yaml script!](/images/3.5.dwd-weather-lightning-warn.jpg)        
        Implementation from HACS Integration of DWD Weather based.        

### Handshow 4.2 E-Tags        
#### Sources only tested with Solumn 4.2 E-Tags.
>- *4.2-flight-radar.yaml*
        Implementation from HACS Integration of Flightradar24.
        this ist automation script, you must changed for your usecae.
        https://github.com/AlexandrErohin/home-assistant-flightradar24?tab=readme-ov-file#flight
>- *4.2-dwd-weather.yaml*
        Implementation from HACS Integration of DWD Weather.
        this ist automation script, you must changed for your usecae.
        
### Chroma 7.4 E-Tags        
#### Sources only tested with Chroma 7.5 E-Tags.
>- *7.4-dwd-weather-ranking-hh-n.yaml*
        Implementation from HACS Integration DWD Weather between Hamburg and Nürnberg.
![Example of the Yaml script!](/images/chroma75_dwd_ranking.png)  

### Hanshow 7.5 E-Tags        
#### Sources only tested with Hanshow 7.5 E-Tags.
>- *7.5-pws-weather.yaml*
        Implementation from HACS Integration Ecowitt-PWS Weather Nürnberg.
![Example of the Yaml script!](/images/7.5_hanshow_PWS.jpg)  

# external sensor
>- ha-template-sensors.yaml
        add template sensors to your HomeAssistant configuration.yaml or sensors.yaml
        add 2 x template sensors CAPE and LiftedIndex to your HomeAssistant configuration.yaml or sensors.yaml
# media
    The font is currently only required for the Accu Weather Script.
# images
    Result on my existing devices.
# stl
    3D Printer Files for Openplant Stand(Stick)    
## Instructions and Informations

### Designed for display size:
 >   - (1.54") 152x152 
 >   - (2.13") 250x132 
 >   - (2.9")  296x128
 >   - (3.5")  384x184
 >   - (4.2")  400x300
 >   - (7.4")  640x384
 >   - (7.5")  800x480
  
 
### Installation instructions
    In order to use the font in script, 
    the font file must be copied into the Home Assistant instance used under the following file folder.

#### Source folder: 
>-      /media/
#### Destination folder: 
>-      /homeassistant/custom_components/open_epaper_link/
