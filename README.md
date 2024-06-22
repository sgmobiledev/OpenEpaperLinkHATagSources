# OpenEpaperLinkHATagSources
Home-Assistant BLE Tags Yaml Scripts for OpenEpaperLink

## Folder Structure

    # 2.9-Gicisky-epaper-tags

    Sources only tested with Gicisky BLE EPD BWR 2.9 E-Tags.

    # 2.13-Gicisky-epaper-tags

    Sources only tested with Gicisky BLE TFT 2.9 E-Tags.
      - 2.9-accu-weather.yaml
        Implementation from HACS Integration of Weathercloudservice Accu Weather.
      - 2.9-hochwasserportal-pegelstaende.yaml
        Implementation from HACS Integration of Hochwasserportal Service.
    
    # media

    The font is currently only required for the Accu Weather Script.

    # images

    Result on my existing devices.

## Instructions and Informations

### Designed for display size:
    - (2.13") 250x132 
    - (2.9")  296x128

### Installation instructions

    In order to use the font in script, 
    the font file must be copied into the Home Assistant instance used under the following file folder.

    - Source folder: 
      /media/
    - Destination folder: 
      /homeassistant/custom_components/open_epaper_link/
