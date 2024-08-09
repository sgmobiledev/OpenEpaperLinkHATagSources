# OpenEpaperLinkHATagSources

Home-Assistant BLE Tags Yaml Scripts for OpenEpaperLink

## Folder Structure
### 1.54 Epaper-tags

#### Sources only tested with SoluM-1-54 E-Tags.
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


### 2.13-Gicisky-epaper-tags
>- *2.13.dwd-pollen-warning.yaml*
![Example of the Yaml script!](/images/2.13.dwd-pollenflug.jpg)        
        Implementation from HACS Integration of Weathercloudservice Deutschen Wetterdienst.

>- *2.13.openuv-warning.yaml*
![Example of the Yaml script!](/images/2.13.openuv.jpg)        
        Implementation from HACS Integration of Weathercloudservice OPENUV.

>- *2.13-hochwasserportal-pegelstaende.yaml*
        Implementation from HACS Integration of Hochwasserportal Service.
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
>- ha-template-sensors.yaml
        add template sensors to your HomeAssistant configuration.yaml or sensors.yaml
        add 2 x template sensors CAPE and LiftedIndex to your HomeAssistant configuration.yaml or sensors.yaml
# media
    The font is currently only required for the Accu Weather Script.
# images
    Result on my existing devices.
## Instructions and Informations

### Designed for display size:
 >   - (1.54") 152x152 
 >   - (2.13") 250x132 
 >   - (2.9")  296x128
 >   - (3.5")  384x184
 >   - (4.2")  400x300
### Installation instructions
    In order to use the font in script, 
    the font file must be copied into the Home Assistant instance used under the following file folder.

#### Source folder: 
>-      /media/
#### Destination folder: 
>-      /homeassistant/custom_components/open_epaper_link/
