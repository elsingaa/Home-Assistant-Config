# Live in Comfort aka my Home Assistant Configuration
I tried [Home Assistant](https://home-assistant.io/) a couple of years ago, put it aside again, because then it wasn't there where I needed it to be.
Recently I reinstalled Home Assistant to integrate all the various systems I use for controlling our home.

In an effort to document my configuration I created this repository.

## Base
The base of my smart home is a Z-Wave network, created by the ZWay board for Raspberry Pi. Sensors and switches are controlled then through a MQTT message bus. To create automation and a user interface I use Home Assistant, which is running on a virtual machine on VMware vSphere.

## My devices, services, and software I use

Device | Quantity | More info | Image 
--- | --- | --- | ---
Aeotec Door/window sensor 7| 3 | | ![Aeotec Door/Window sensor](www/images/README/aeotec-windowsensor.jpg)
Aeotec multi Sensor| 3 | [Aeotec Multi Sensor ](https://aeotec.com/z-wave-sensor/) | ![Aeotec multisensor](www/images/README/aeotec-multisensor.jpg)
EverSpring Z-Wave PIR Sensor SP814  | 1 | [EverSpring sensor](http://www.everspring.com/portfolio-item/sp814-lens-changeable-pir-detector/) | ![EverSpring PIR Sensor](www/images/README/everspring-sensor.jpg)
Fibaro Wall Plug FGWPE-101 (Z-Wave)| 16 | [Fibaro wall plug](https://www.fibaro.com/en/products/wall-plug/) | ![Fibaro wall plug](www/images/README/fibaro-wallplug.jpg "Fibaro wall plug")
Philips Hue lighting | |
Ikea Tradfri | |


## Audio / Video

Vendor | Device | |
--- | --- | --- 
Apple | Apple TV | ![Apple TV](www/images/README/apple-tv-4gen.jpg) | 
Denon |  X2100W AVR | ![Denon X2100W AVR](www/images/README/denonx2100w.jpg)
Plex | Plex |  ![Plex](www/images/README/plex.jpg)
Spotify | Spotify | ![Spotify](www/images/README/spotify.png)
Samsung | Samsung UE46D6200 | ![Spotify](www/images/README/samsung_ue46d6200.jpg) 

## Network / Wireless
Kind | explanation
--- | --- 
Pi-Hole | Ad-blocker
Unifi | Network & Wireless


## Energy
Kind | explanation
--- | --- 
PVOutput | Solar totals
SolarEdge | Solar Panels

## Health
Kind | explanation
--- | --- 
FitBit | Fitbit wife
MyFitnessPal | My own health

## Environment
Kind | explanation
--- | --- 
Luftdaten | Air conditition



## Presence
Kind | explanation
--- | --- 
Owntracks |
ESP32 | Home Bluetooth presence detection

## Heating
Kind | explanation
--- | --- 
Alpha Innotec | Air-Water heatpump


## Calendar
Kind | explanation
--- | --- 
Google Calendar |


## Storage
Kind | explanation
--- | --- 
Synology | Storage


## Various
Kind | explanation
--- | --- 
MQTT | Message bus
BMW ConnectedDrive | Car information
RDW | Information about our cars
P2000 | Information about Ambulance/police/firebrigade


## Computers
Kind | explanation
--- | --- 
Raspberry Pi | Z-Way Z-Wave network
Intel Nuc i5 (3x) | VMware cluster containing various items, including home automation items like Home Assistant
