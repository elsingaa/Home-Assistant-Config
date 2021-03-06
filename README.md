# Live in Comfort aka my Home Assistant Configuration
I tried [Home Assistant](https://home-assistant.io/) a couple of years ago, put it aside again, because then it wasn't there where I needed it to be.
Recently I reinstalled Home Assistant to integrate all the various systems I use for controlling our home.

In an effort to document my configuration I created this repository.

![Maintained](https://img.shields.io/maintenance/yes/2020?style=for-the-badge)
![Last commit](https://img.shields.io/github/last-commit/elsingaa/Home-Assistant-Config?style=for-the-badge)
![Open issues](https://img.shields.io/github/issues-raw/elsingaa/Home-Assistant-Config?color=brightgreen&style=for-the-badge)
![Commits](https://img.shields.io/github/commit-activity/w/elsingaa/Home-Assistant-Config?color=brightgreen&style=for-the-badge)
![Stars](https://img.shields.io/github/stars/elsingaa/Home-Assistant-Config?color=brightgreen&style=for-the-badge)
![Build status](https://img.shields.io/travis/elsingaa/Home-Assistant-Config?style=for-the-badge)

Like a lot of folks I'm using the GitHub issues and project to keep track of bugs in my configuration and new features I want to make/use.

## Table of Contents
* [Base](#base)
* [My devices, services, and software I use](#my-devices-services-and-software-i-use)
    * [Audio / video](#audio--video)
    * [Network / Wireless](#network--wireless)
    * [Energy](#energy)
    * [Health](#health)
    * [Environment](#environment)
    * [Presence](#presence)
    * [Heating](#heating)
    * [Calendar](#calendar)
    * [Storage](#storage)
    * [Computers](#computers)
    * [Various](#various)


## Base
The base of my smart home is a Z-Wave network, created by the ZWay board for Raspberry Pi. Sensors and switches are controlled then through a MQTT message bus. To create automation and a user interface I use Home Assistant, which is running on a virtual machine on VMware vSphere.

[Table of Contents](#table-of-contents)

## My devices, services, and software I use

Device | Quantity | More info | Image 
--- | --- | --- | ---
Aeotec Door/window sensor 7| 3 | | ![Aeotec Door/Window sensor](www/images/README/aeotec-windowsensor.jpg)
Aeotec multi Sensor| 3 | [Aeotec Multi Sensor ](https://aeotec.com/z-wave-sensor/) | ![Aeotec multisensor](www/images/README/aeotec-multisensor.jpg)
EverSpring Z-Wave PIR Sensor SP814  | 1 | [EverSpring sensor](http://www.everspring.com/portfolio-item/sp814-lens-changeable-pir-detector/) | ![EverSpring PIR Sensor](www/images/README/everspring-sensor.jpg)
Fibaro Wall Plug FGWPE-101 (Z-Wave)| 16 | [Fibaro wall plug](https://www.fibaro.com/en/products/wall-plug/) | ![Fibaro wall plug](www/images/README/fibaro-wallplug.jpg "Fibaro wall plug")
Philips Hue lighting | (a lot) |[Philips Hue](https://meethue.com) | ![Philips Hue](www/images/README/philipshue.jpg)
Ikea TRÅDFRI (aka Home smart) | 2 | [Ikea Smart Lighting](https://www.ikea.com/nl/en/cat/smart-lighting-36812/)| ![Ikea Tradfri](www/images/README/ikeatradfri.jpg)

[Table of Contents](#table-of-contents)

## Audio / Video

Vendor | Device | |
--- | --- | --- 
Apple | Apple TV | ![Apple TV](www/images/README/apple-tv-4gen.jpg) | 
Denon |  X2100W AVR | ![Denon X2100W AVR](www/images/README/denonx2100w.jpg)
Plex | Plex |  ![Plex](www/images/README/plex.jpg)
Spotify | Spotify | ![Spotify](www/images/README/spotify.png)
Samsung | Samsung UE46D6200 | ![Spotify](www/images/README/samsung_ue46d6200.jpg) 

[Table of Contents](#table-of-contents)

## Network / Wireless
Kind | explanation | |
--- | --- | ---
Pi-Hole | Ad-blocker | ![Pi-hole](www/images/README/pihole.jpg)
Ubiquiti Unifi | Network & Wireless |![Ubiquiti Unifi](www/images/README/ubiquitiunifi.jpg)

[Table of Contents](#table-of-contents)

## Energy
Kind | explanation
--- | --- 
PVOutput | Solar totals
SolarEdge | Solar Panels

[Table of Contents](#table-of-contents)

## Health
Kind | explanation | 
--- | --- | ---
FitBit | Health tracking 
MyFitnessPal | Health tracking

[Table of Contents](#table-of-contents)

## Environment
Kind | explanation
--- | --- 
Luftdaten | Air conditition

[Table of Contents](#table-of-contents)

## Presence
Kind | explanation
--- | --- 
Owntracks |
ESP32 | Home Bluetooth presence detection

[Table of Contents](#table-of-contents)

## Heating
Kind | explanation
--- | --- 
Alpha Innotec | Air-Water heatpump

[Table of Contents](#table-of-contents)

## Calendar
Kind | explanation
--- | --- 
Google Calendar |

[Table of Contents](#table-of-contents)

## Storage
Kind | explanation
--- | --- 
Synology | Storage

[Table of Contents](#table-of-contents)

## Various
Kind | explanation
--- | --- 
MQTT | Message bus
BMW ConnectedDrive | Car information
RDW | Information about our cars
P2000 | Information about Ambulance/police/firebrigade

[Table of Contents](#table-of-contents)

## Computers
Kind | explanation
--- | --- 
Raspberry Pi | Z-Way Z-Wave network
Intel Nuc i5 (3x) | VMware cluster containing various items, including home automation items like Home Assistant

[Table of Contents](#table-of-contents)


## License

MIT License

Copyright (c) 2019 Anne Jan Elsinga

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
