# Agro-Navigation-receiver
Building instructions DIY GPS receiver for the parallel driving app.


## What is the AGRO NAVIGATION app? 
Agro Navigation is a tiny and fast GPS navigation app (iOs, Android) for parallel driving that helps farmers on fertilizers and pesticides.
The Agro Navigation helps you navigate in parallel lines while driving in the field.

![parallel driving app interface](https://user-images.githubusercontent.com/54446451/192321951-3f21f5fd-f789-44fc-ab61-2b0535d08ef7.png)

You can see on your smartphone if you have an underspread of chemicals, which can improve the efficiency of your farming work.

[![AppStore](https://user-images.githubusercontent.com/54446451/159944768-9d67f01b-6657-4abf-8b83-6af861813203.png)](https://apps.apple.com/ru/app/agro-navigation/id1625258870)

[![Google Play](https://user-images.githubusercontent.com/54446451/159944833-5c906f5f-61c7-4b45-8715-b167915c0620.png)](https://play.google.com/store/apps/details?id=com.shlyagin.parallel_driving)

## How it Works

The Agro Navigation helps you navigate in parallel lines while driving in the field.

### Just three steps to get started

---

#### 1. Set main direction

   Drive to the start point and press «Set».

   Main direction will be set.
   
---

#### 2. Press «Start» to start working

   After press «Start» you will see a wide trail

   that is drawn behind the tractor.
   
---

#### 3. Set operating width

   Make the first turn according to visual references.

   Then set the operation width using the left slider.
   
---

That's all! Follow the green lines.

Watch the YouTube “Agro Navigation app for parallel driving”.

[![YouTube ARGO NAVIGATION video](http://img.youtube.com/vi/I6HTStWH_PI/0.jpg)](http://www.youtube.com/watch?v=I6HTStWH_PI)

Please note that the accuracy depends on the smartphone's GPS. Some models are not accurate enough.

## Сontrols

![Controls 1. Operation width slider.
2. Set main operation direction.
3. Start working.
4. Zoom slider.
5. Clear track.
6. Settings.
7. Back from pan mode.
Note:
Pan mode allow you zoom and rotate track by using gestures.
8. If recorded track is not vertical you can correct it by manual correction.
9. Use magnetic declination. Some devices is not corrected compass according to location.
10.  If the smartphone's built-in compass is turned off, the GPS heading is used.
Note:
Turns will be displayed with a delay.
Heading may be wrong at low speed.](https://user-images.githubusercontent.com/54446451/192325605-54100f03-de39-486c-af4d-93c52a3b2c1c.png)


## Why do you need an external receiver?

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
