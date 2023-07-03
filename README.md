# Gamepads cheat sheets

This website contains a collection of cheatsheets for various gamepads.

Each cheatsheet should be:

* **Correct**: Any mistake should be corrected and pushed to [the repository][repo]).
* **Concise**: It should be quick to find relevant information. Think of it as a *reference*, rather than a full manual.
* **Comprehensive**: It should contain as much (relevant) information as possible.

This website is focused on any game controller (not just gamepads) that can be connected to a computer, to a smartphone, or even to a video-game console.

## Why this exists

[denilsonsa][] has [quite a few different game controllers](https://imgur.com/a/s6gCh). Some of them are USB, many are (also) Bluetooth. They have different sets of features, and they have different settings that can be changed through button combinations. However, it's hard to memorize all the settings for all controllers. Sure, we could get the official manual from the the website, but usually the manual is either incomplete or too verbose (or both).

That's why this website was created. Since it is "community"-driven, we are free to add missing information and to rearrange the information to make it easier to find. If you like analogies, think of this website as a <https://tldr.sh/> version of gamepad manuals.

[repo]: https://github.com/denilsonsa/gamepad-cheatsheet
[denilsonsa]: https://denilson.sa.nom.br/

## Common gamepad features

### Connectivity

Many Bluetooth gamepads can also be connected through USB, and then they are recognized as a wired controller.

### Xinput and Dinput

On Windows, *DInput* (abbreviation of [*DirectInput*](https://en.wikipedia.org/wiki/DirectInput)) was the traditional way of using game controllers since 1995. Then, in 2005, Microsoft introduced *XInput* alongside the launch of Xbox 360 game console. Since then, Microsoft has been pushing more and more towards XInput instead of DInput.

While DirectInput was extremely flexible, it also meant controllers were mostly free to map any hardware button to any logical number. On the other hand, XInput expects an [Xbox-like controller](https://en.wikipedia.org/wiki/Xbox_360_controller):

* Four face buttons: A, B, X, Y
* Two shoulder buttons: LB, RB (sometimes known as L1, R1)
* Two shoulder analog triggers: LT, RT (sometimes known as L2, R2)
* Two clickable analog sticks (the buttons are sometimes known as L3, R3)
* One digital Dpad
* Three other buttons: START, BACK (or SELECT), GUIDE (or HOME)

Currently, most game consoles (Xbox, Playstation, Switch) follow a similar gamepad style, with a similar amount of features, but sometimes with different names for buttons.

Why does it matter?

By design, the two analog triggers (LT, RT) are mapped to the same analog axis on DInput, but they are independent on XInput. Thus, if you have the option, most likely you want to use the XInput mode to be able to use both triggers at the same time. Additionally, XInput mode has predictable button names, so the in-game prompts can display the button name, instead of the button number.

However, you may want to use the DInput mode for compatibility reasons. Some gamepads can also be paired to a different device for each "mode", so you could use the same gamepad with two devices (but not at the same time) by just pairing each device with a different mode.

Regardless, both modes (DInput or XInput) are supported on both Windows, Linux, Android.

### Remapping A/B an X/Y buttons

By looking at the position of the A and B buttons, we have two families of gamepads:

* Alphabetical order: The A button to the left of the B button. The X button to the left of the Y button (if they are present).
    * SEGA Mega Drive, SEGA Saturn, SEGA Dreamcast.
    * Microsoft Xbox (all consoles in this series).
    * SNK Neo Geo CD, SNK Neo Geo Pocket.
    * 3DO.
    * Nvidia Shield.
* Reverse order: The B button to the left of the A button. The Y button to the left of the X button (if they are present).
    * Nintendo consoles and handhelds: NES, SNES, Virtual Boy, Wii (classic controller), Wii U, Game Boy, Game Boy Advance, DS, 3DS, Switch.
    * Atari Jaguar.
* PlayStation has symbols instead of letters, so it doesn't fit in this classification.

Gamepads trying to support multiple systems (or aimed at players that play emulated systems) can provide a feature to swap the A/B and X/Y buttons. This way, pressing the hardware A button can be reported as either the A button or the B button, depending on the setting (likewise for the X and Y buttons).

## About SVG files in this repository

The SVG drawings of each gamepad are extracted from the PDF manuals using [Inkscape](https://www.inkscape.org/) and then cleaned up using [Scour](https://github.com/scour-project/scour).

     scour -i INPUT.svg -o OUTPUT.svg \
         --remove-metadata \
         --enable-comment-stripping \
         --enable-id-stripping \
         --create-groups

The `width` and `height` attributes are then manually removed, as they are not needed anyway.

## Where to buy?

* <https://www.dragonbox.de/> has a great selection of gamepads and products.

## See also

Other somewhat related projects and pages:

* <https://github.com/gabomdq/SDL_GameControllerDB>
