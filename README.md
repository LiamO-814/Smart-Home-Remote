# DIY Smart Home Remote
This project includes printable files for a wireless IOT remote with 9 programmable buttons, wiring diagrams, and software scripts that can be integrated with ESPHome for HomeAssistant. If you aren't familiar with the ESPHome Project, please [check out their documentation](https://esphome.io/) to get setup.

This repo also includes the full build log of all of my tribulations in designing and bringing the project to life. 

The inception of this project came from outfitting my apartment with as much smart tech and home automation hardware as I possessed, and then coming to the realization that we could no longer use the Light Switches and my phone become the central controller for the entire space. I realized quickly that I was in need of a hardware solution to make the home more controllable. I wanted to make a wall-mounted switch that could also be removed and used as a wireless remote. The wall mount would double as a charging dock of sorts. This remains the ultimate goal of the project. 

This project has taken multiple iterations including a a full "back-to-the-drawing-board" moment, that, so far, seems to have been for the best. Much of this project was also developing my 3D Design and CAD skills, so I think my comfort and skill level shows throughout iterations of the project.

## Outline

The general outline of this project can be summarized in the following circuit:
<!--- ![General Circuit](https://github.com/LiamO-814/Smart-Home-Remote/blob/main/References/GeneralCircuit.png) -->

<img alt="General Circuit" src="https://github.com/LiamO-814/Smart-Home-Remote/blob/main/References/GeneralCircuit.png" width="40%" height="40%">

It is as simple as 9 GPIO Pins ties to 9 Push Button Switches, a battery and charge controller, and a Wi-Fi enabled microcontroller to run the show. No rocket science needed or involved here. 

Fritzing is a bit limited in terms of parts, so I had to use some substitutes. 

I am using a [USB Charge Controller with a TP4056 Charge Controller](https://www.aliexpress.us/item/3256804241424963.html?spm=a2g0o.order_list.order_list_main.17.59e274ddH2cvsc&gatewayAdapt=glo2usa):

<img alt="Charge Controller" src="https://github.com/LiamO-814/Smart-Home-Remote/blob/main/References/TP4056%20USB-C%20Charger.png" width="20%" height="20%">

The microcontroller is a [ESP32-C3 Zero Development Board from Waveshare](https://www.waveshare.com/esp32-c3-zero.htm):

<img alt="uController" src="https://github.com/LiamO-814/Smart-Home-Remote/blob/main/References/ESP32%20C3.jpg" width="20%" height="20%">


Any 3.7v LiPo Battery (with a charge voltage of 4.2V) should fit the bill. I am using [LP402535 from EEMB](https://a.co/d/e7UViq0) which have a capacity of 320mAh. Note the dimensions of the remote are very much based around this specific model's dimensions, so if you wish to you use other models, the enclosure dimensions will have to change. 

Please See the Design Log Files for more project details

## Assembly and Installation

**This section will be completed as the project is finalized. Thank you for your patience.**

