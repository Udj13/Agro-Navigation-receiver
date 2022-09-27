# Agro Navigation external BLUETOOTH GPS receiver

![image](https://user-images.githubusercontent.com/54446451/192328353-de5d13e1-79c2-46a0-b84a-97f5fcf3eff6.png)

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

![image](https://user-images.githubusercontent.com/54446451/192331144-a0ec966c-a7f0-4a36-98e2-09ca9ee466da.png)

The easiest way is to use the module with built-in GPS/GNSS antenna and USB connector

![image](https://user-images.githubusercontent.com/54446451/192331362-aef31ed4-a5da-4fb3-861a-ec3518bad729.png)

Bluetooth: HM-10

![image](https://user-images.githubusercontent.com/54446451/192330582-9fdb2f72-698b-43bb-b2df-02b6ece3b08c.png)

## Wiring

Connect the power pins (VCC, GND) of both modules. Then connect TX-pin GPS to RX-pin Bluetooth.

![image](https://user-images.githubusercontent.com/54446451/192331728-f2b793fa-9cbb-43ba-8480-3eb963aa0504.png)

![image](https://user-images.githubusercontent.com/54446451/192331898-ed50d8ad-1472-4218-9e6c-7da237a900ab.png)

## Case printing

You can 3d print the case, if you want.

![image](https://user-images.githubusercontent.com/54446451/192332293-ef468b10-6526-4c64-99ac-65d437ed8901.png)

Solder the jumper.

![image](https://user-images.githubusercontent.com/54446451/192332680-483529e2-ad33-4674-af27-58dda2daa0f5.png)

Print case. 

https://github.com/Udj13/Agro-Navigation-receiver/blob/main/gps%20receiver.stl

![image](https://user-images.githubusercontent.com/54446451/192332779-a4e65086-50dc-459f-b07a-9ecf0b83bb04.png)

Assemble the device. Сut off the legs of the LED.

![image](https://user-images.githubusercontent.com/54446451/192334140-bb86a1de-a44e-492e-8067-1390fb8e1eed.png)

![image](https://user-images.githubusercontent.com/54446451/192334551-9c44bbf6-8639-4798-a0ca-bc41f963d9b5.png)

![image](https://user-images.githubusercontent.com/54446451/192334318-b11bdb39-c672-4ae7-92f6-a22b0b81eaba.png)

![image](https://user-images.githubusercontent.com/54446451/192334396-0a5e6fd1-aea6-40e9-9fba-7dc29989ee5a.png)

![image](https://user-images.githubusercontent.com/54446451/192336644-f192ef51-9946-44fd-9eda-9e8b9614c351.png)


## Setup GPS module

Download u-center from https://www.u-blox.com/en/product/u-center (Windows only), and set up your GPS module.

![settings screenshot](https://user-images.githubusercontent.com/54446451/192336721-4a7ae506-ddcb-4f99-aea3-c281dda86965.png)


## AGRO NAVIGATION app connection

First install the app on your phone.

[![AppStore](https://user-images.githubusercontent.com/54446451/159944768-9d67f01b-6657-4abf-8b83-6af861813203.png)](https://apps.apple.com/ru/app/agro-navigation/id1625258870)

[![Google Play](https://user-images.githubusercontent.com/54446451/159944833-5c906f5f-61c7-4b45-8715-b167915c0620.png)](https://play.google.com/store/apps/details?id=com.shlyagin.parallel_driving)

In the parallel driving app: Settings -> Connect external GPS receiver… 

![app screenshot](https://user-images.githubusercontent.com/54446451/192339032-12334d23-4ad8-4c22-96b9-7c42a1ece3a7.png)

The connection icon is displayed on the left on the main screen when the GPS receiver is connected.

YouTube:

[![YouTube GPS receiver connection in ARGO NAVIGATION](http://img.youtube.com/vi/7Vs9jBaqPb4/0.jpg)](http://www.youtube.com/watch?v=7Vs9jBaqPb4)
