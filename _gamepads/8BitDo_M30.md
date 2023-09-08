---
brand: 8BitDo
model: M30
---

# {{ page.brand }} {{ page.model }}

<img class="drawing" src="8BitDo_M30.svg" alt="Drawing of the {{ page.brand }} {{ page.model }} gamepad, showing all buttons.">

* Connections: Bluetooth and USB-C
* [Product page](https://www.8bitdo.com/m30/)
* [Manual](https://download.8bitdo.com/Manual/Controller/M30/M30_Manual.pdf)
* [FAQ](https://support.8bitdo.com/faq/m30-bluetooth-controller.html)
* User-created content:
    * [clach04/8bitdo_manual](https://github.com/clach04/8bitdo_manual/)
    * [fwupd/8bitdo-firmware](https://github.com/fwupd/8bitdo-firmware)
    * [jayp76/8bitdo_faq](https://github.com/jayp76/8bitdo_faq/wiki)

## Overview

At the top edge of the controller, between the L and R buttons, there is a "Bluetooth pair" button, a USB-C connection, and a red LED.

At the bottom edge of the controller, there are 4 green LEDs.

At the front of the controller, just below the START button, there are three buttons: STAR, SELECT (or MINUS), HEART (or HOME).

## Power-on modes (Bluetooth)

Use these combinations to turn on the gamepad.

Combination   | Mode            | LEDs                         | Vendor id | Product id | Device name                                                      |
------------- | --------------- | ----------------------------------------| ---- | ---- | ---------------------------------------------------------------- |
START         | Last used mode  | As many as last mode                    |      |      |                                                                  |
B + START     | Android/Dinput  | 1 LED blinks                            | 2dc8 | 5006 (USB) or 0651 (BT) | *8BitDo M30 gamepad*                          |
X + START     | Xinput          | 2 LEDs blink                            | 045e | 028e (USB) or 02e0 (BT) | *8Bitdo M30 Controller* Xbox 360 Controller   |
A + START     | Mac             | 3 LEDs blink                            | 054c | 05c4 | *Sony Computer Entertainment Wireless Controller* PS4 Controller |
Y + START     | Nintendo Switch | 4 LEDs blink in a back-and-forth motion | 057e | 2009 | *Nintendo Co., Ltd. Pro Controller*                              |
L + R + START | Firmware update | Red LED blinks constantly               | 2dc8 | 5750 | *8BitdoJoy 8Bitdo* BootMod                                       |

## Power-off

Automatically turns off after 15 minutes without activity.

Hold for...  | Action
------------ | ------
START for 3s | Power off
START for 8s | Force power off

## Battery

480mAh battery, 1-2 hours of charging time, 18 hours of play time.

LED          | Meaning
------------ | -------
RED blinking | Low battery
RED solid    | Charging
RED off      | Fully charged

## Button remapping

Red LED blinks upon remapping.

Hold for 5s    | Mapping
-------------- | -------
SELECT + UP    | Map D-pad as D-pad (hat)
SELECT + LEFT  | Map D-pad as left analogue stick
SELECT + RIGHT | Map D-pad as right analogue stick
SELECT + DOWN  | Swap A-B and X-Y (only in Nintendo Switch mode)

## Other mappings

Button | Dinput | Xinput | Switch
------ | ------ | ------ | ------
STAR   | Turbo  | Turbo  | Screenshot
HEART  | C      | HOME   | HOME
Z      | L1     | L1     | L
C      | R1     | R1     | R
L      | L2     | L2     | ZL
R      | R2     | R2     | ZR

To toggle the *turbo* function, hold down any button and then press STAR.
