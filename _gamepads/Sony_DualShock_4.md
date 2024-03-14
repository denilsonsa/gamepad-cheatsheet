---
brand: Sony
model: DualShock 4
---

# {{ page.brand }} {{ page.model }}

There are two models:

* v1
    * The model number starts with `CUH-ZCT1`, followed by region letter(s).
    * Doesn't work over USB, can only be used over Bluetooth.
    * The rubber coating from the analog sticks degrades too quickly.
    * The LED light bar is only visible from the back.
    * Bluetooth version 2.1+EDR.
* v2
    * The model number starts with `CUH-ZCT2`, followed by region letter(s).
    * Works both via USB and via Bluetooth.
    * The LED light bar is visible from the top and from the back.
    * Bluetooth version 4.0.

The information of this page is based on the second model (v2).

* Connections: Bluetooth and Micro-USB
* 3.5mm TRRS combo headset jack can be used when the controller is connected via USB
    * Measured about 30ms of microphone delay, but it could be an issue with my testing.
* 3.65V 1000mAh battery
* Weight: 210g
* Vendor id: `054c` "Sony Interactive Entertainment"
* Product id:
    * v1: `05c4` "Wireless Controller"
    * v2: `09cc` "Wireless Controller"
* Official manual:
    * [DUALSHOCK®4 Wireless Controller Instruction Manual](https://www.playstation.com/content/dam/global_pdc/en/corporate/support/manuals/accessories/ps4-accessories/dualshock4-wireless-controller-cuh-zct2/IND_EN_CUH-ZCT2_DS4%20Wireless%20Controller%20Web.pdf)
    * [Search for other variants and languages](https://duckduckgo.com/?q=filetype%3Apdf+dualshock4-wireless-controller-cuh-zct2)
* Third-pary documentation:
    * <https://www.pcgamingwiki.com/wiki/Controller:DualShock_4>
    * <https://www.ifixit.com/Device/DualShock_4>
    * <https://www.ifixit.com/Device/DualShock_4_CHU-ZCT2U>
    * <https://wiki.archlinux.org/title/Gamepad#PlayStation_3/4_controller>
    * <https://wiki.archlinux.org/title/Gamepad#Playstation_4_controllers>
    * <https://github.com/chrippa/ds4drv>

## Power-on (Bluetooth)

Buttons              | Action                       | LED light bar
-------------------- | ---------------------------- | -------------
Press PS button      | Reconnect to the last device | Blinking white two times per second
Hold PS+SHARE for 4s | Bluetooth pairing            | Two short flashes per second

## Power-off

Hold the PS button from 8s to 15s to turn off the controller.

## Factory reset

Insert a paper clip into a little hole on the bottom of the controller, next to a screw near the L2 trigger, and push the reset button for 5 seconds.
