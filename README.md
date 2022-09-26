# Agro-Navigation-receiver
Building instructions DIY GPS receiver for the parallel driving app.


## What is the AGRO NAVIGATION app? 
Agro Navigation is a tiny and fast GPS navigation app (iOs, Android) for parallel driving that helps farmers on fertilizers and pesticides.
The Agro Navigation helps you navigate in parallel lines while driving in the field.
You can see on your smartphone if you have an underspread of chemicals, which can improve the efficiency of your farming work.

https://shlyagin.ru/agro-navigation/

[![image](https://user-images.githubusercontent.com/54446451/159944768-9d67f01b-6657-4abf-8b83-6af861813203.png)](https://apps.apple.com/ru/app/agro-navigation/id1625258870)

[![image](https://user-images.githubusercontent.com/54446451/159944833-5c906f5f-61c7-4b45-8715-b167915c0620.png)](https://play.google.com/store/apps/details?id=com.shlyagin.parallel_driving)

[![AGRO NAVIGATION video](https://user-images.githubusercontent.com/54446451/192274331-f42de192-308b-4260-a28e-7538e0a617b6.png)](https://youtu.be/I6HTStWH_PI)




Low GPS accuracy is the main problem of using AGRO NAVIGATION APP. If the phone is arranged in the cabin of the vehicle, the GPS signal may be shielded by the top plate of the cabin.

External receiver can be placed on the top of the tractor and connected to the phone via bluetooth.

Because the AGRO NAVIGATION app accepts a NMEA data stream, any external receiver can be connected to it.

## Components

To create your own GPS AGRO NAVIGATION receiver you will be wiring only two modules. The GPS module (from u-blox) and the bluetooth UART module.

GPS: Neo-6M (low accuracy, external antenna required), NEO-7M, NEO-8M
Bluetooth: HM-10

The easiest way is to use the module with built -in GPS/GNSS antenna and USB connector

## Wiring

Connect the power pins (VCC, GND) of both modules. Then connect TX-pin GPS to RX-pin Bluetooth.

## Case printing

You can 3d print the case, if you want.

## Setup GPS module

Download u-center from https://www.u-blox.com/en/product/u-center (Windows only), and set up your GPS module.

## AGRO NAVIGATION app connection

First install the app on your phone.

In the parallel driving app: Settings -> Connect external GPS receiver… 

The connection icon is displayed on the left on the main screen when the GPS receiver is connected.
