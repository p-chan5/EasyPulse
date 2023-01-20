# EasyPulse
A collection of HQ presets for EasyEffects and PulseEffects.

![easyeffects_presets](https://user-images.githubusercontent.com/123143444/213625722-3d25507e-05d7-4dad-ad9a-72bcd157d6db.gif)
![pulseeffects_presets](https://user-images.githubusercontent.com/123143444/213635531-5b1e66a0-faff-4b1f-8f7d-ffd51c1832b0.gif)

## Features

- Ready to use. No need to set anything else only load.
- Constant updates. This includes quality improvements and bug fixes.
- 12 presets
  - air (Acoustic / Ballad / Vocal)
  - bass (Beat / Deep)
  - blues (Jazz / R&B)
  - club (Dance / Electronic)
  - custom (Template)
  - hifi (Surround / Theater)
  - laptop (Speakers)
  - lofi (Chill / Dream)
  - podcast (Speech)
  - radio
  - rock (Alternative / Indie / Metal)
  - ziyad
- 10 band equalizer (25Hz – 12800kHz / x4 / Q 5.00)
- Bedroom reverb (200Hz – 12800kHz)
- Limiter with automatic leveling (distortion free)
- 25 ms delay on the right channel (stereo effect in headphones)

## Installation

1. [Clone this repository](https://github.com/p-chan5/EasyPulse/archive/refs/heads/main.zip) or go to the [releases tab](https://github.com/p-chan5/EasyPulse/releases) and download the last version.
2. Unzip it.
3. Locate the `.js` files and paste them into one of the following paths:

***PulseEffects:***

`~/.config/PulseEffects/output` *(Repositories)*

`~/.var/app/com.github.wwmm.pulseeffects/.config/output` *(Flatpak)*

***EasyEffects:***

`~/.config/easyeffects/output` *(Repositories)*

`~/.var/app/com.github.wwmm.easyeffects/config/output` *(Flatpak)*

...or use the `Import a preset` button.

![easyeffects_import_a_preset_button](https://user-images.githubusercontent.com/123143444/213627977-1a4009de-9122-415b-b644-a3a41c2a7429.png)

![pulseeffects_import_a_preset_button](https://user-images.githubusercontent.com/123143444/213635562-7567877d-feea-4a42-969e-3abe522d7045.png)

4. It's done!

## FAQ

**What equipment did you try it with?**

I used the following headphones:

- sony-mdr-zx110
- sony-mdr-zx310

**Are they compatible with older versions of Easy Effects or Pulse Effects?**

Most likely not. You can try but this could lead to problems. If you can't upgrade or downgrade to any of these versions I suggest you try recreating them from scratch (soon a tutorial on how to do it)

<img align="right" src=https://user-images.githubusercontent.com/123143444/213626078-ab51df40-8acf-481a-af5f-e8c7e5e4a7ca.png> <img align="right" src=https://user-images.githubusercontent.com/123143444/213626063-9c5a9b1e-560e-48de-a99a-e65a2b2338b2.png>

**Please add more bass!**

I didn't add it because I prefer to get rid of annoying frequencies rather than boost them. In technical terms I believe more in subtractive EQ than additive EQ. But if you want more bass and a crisp sound then boost the frequencies `50Hz` and `12.8kHz`

**I notice volume reduction on the equalizer. Why?**

This is normal (believe it or not) it's impossible to edit the source without getting a different volume level. Unless you want to kill the dynamics with a compressor (although I don't recommend it).

![level](https://user-images.githubusercontent.com/123143444/213627926-8f0ddf20-3e24-48d9-878d-fb035b787ef6.png)

**False Volume**

In fact the limiter must act only in dangerous situations (when the input signal exceeds `0 dB` and becomes distorted) Although this can also affect your source and cause `Automatic Leveling`. One solution for this is to reduce the Output Level of the equalizer so the limiter will act less frequently.

![output](https://user-images.githubusercontent.com/123143444/213627944-600d2e52-a126-4bea-8be7-71696a5eebf7.png)
