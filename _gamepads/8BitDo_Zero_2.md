---
brand: 8BitDo
model: Zero 2
---

# {{ page.brand }} {{ page.model }}

<img class="drawing" src="8BitDo_Zero_2.svg" alt="Drawing of the {{ page.brand }} {{ page.model }} gamepad, showing all buttons.">

* Connections: Bluetooth and USB Micro(1)
* [Product page](https://www.8bitdo.com/zero2/)
* [Manual](https://download.8bitdo.com/Manual/Controller/Zero2/Zero2_Manual.pdf)
* [FAQ](https://support.8bitdo.com/faq/zero2.html)
* User-created content:
    * [clach04/8bitdo_manual](https://github.com/clach04/8bitdo_manual/)
    * [fwupd/8bitdo-firmware](https://github.com/fwupd/8bitdo-firmware)
    * [jayp76/8bitdo_faq](https://github.com/jayp76/8bitdo_faq/wiki)

(1) The [FAQ](https://support.8bitdo.com/faq/zero2.html) claims *“The USB connection is for firmware upgrade and power charging only.”*, but that's incorrect. This gamepad can be used through USB.

## Power-on modes (Bluetooth)

Use these combinations to turn on the gamepad.

Combination   | Mode               | LED                              | Vendor id | Product id | Device name                                                   |
------------- | ------------------ | ------------------------------------------- | ---- | ---- | ------------------------------------------------------------- |
Plug USB cable| Android/Dinput     | Blue LED lights up, or RED while charging   | 2dc8 | 9018 | *8BitDo Zero 2 gamepad*                                       |
START         | Last used mode     | Blue LED blinks (last selected mode) times  |      |      |                                                               |
B + START     | Android/Dinput     | Blue LED blinks 1 time                      | 2dc8 | 3230 | *8BitDo Zero 2 gamepad*                                       |
X + START     | Xinput             | Blue LED blinks 2 times                     | 045e | 02e0 | *Xbox One S Controller*                                       |
A + START     | Mac                | Blue LED blinks 3 times                     | 054c | 05c4 | *Sony Computer Entertainment Wireless Controller* DualShock 4 |
Y + START     | Nintendo Switch    | Blue LED blinks 4 times                     | 057e | 2009 | *Nintendo Switch Pro Controller*                              |
R + START     | Keyboard(2)        | Blue LED blinks 5 times                     | 2dc8 | 3230 | *8BitDo Zero 2 gamepad*                                       |
L + START     | No power saving(3) | Green LED blinks (last selected mode) times |      |      |                                                               |
L + R + START | Firmware update    | Green-yellowish LED blinks constantly       | 0483 | 5760 | *8BitDo Zero 2 BootLoader*                                    |

(2) Buttons are mapped to the letters from `e` to `o` (on a QWERTY layout).
(3) Undocumented, [8BitDo support confirmed it disables the 15-minute power-off](https://www.reddit.com/r/8bitdo/comments/f37ovb/8bitdo_zero_2_lstart_blinks_green_led_why/).

## Power-off

Automatically turns off after 15 minutes without activity, unless started with L + START.

Hold for...  | Action
------------ | ------
START for 3s | Power off
START for 8s | Force power off

## Battery

180mAh Li-on battery, 1-2 hours of charging time, 8 hours of play time.

LED          | Meaning
------------ | -------
Red blinking | Low battery
Red solid    | Charging
Red off      | Fully charged

## Button remapping

Red LED blinks upon remapping.

Hold for 5s    | Mapping
-------------- | -------
SELECT + UP    | Map D-pad as D-pad (hat)
SELECT + LEFT  | Map D-pad as left analogue stick
SELECT + RIGHT | Map D-pad as right analogue stick
SELECT + DOWN  | Swap A-B and X-Y

## Other combinations

Combination    | Mapping
-------------- | -------
Hold SELECT    | Bluetooth pairing (blue LED blinks rapidly)
SELECT + DOWN  | Home button (Xinput and Nintento Switch modes)
SELECT + START | ZL + ZR buttons (Nintendo Switch mode)
