A complete set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align="center">
<img src="https://user-images.githubusercontent.com/123143444/215234342-4a49f39b-9092-4916-94c1-3d8e0c6a9b06.gif" height="185"> <img src="https://user-images.githubusercontent.com/123143444/215234349-585700f8-f45e-4162-8de5-3141da05573f.gif" height="185">
</p>

## WHAT'S INSIDE? 🎁

<details>
<summary>15 presets with bedroom and stereo effects included.</summary>
<p>
  
- acoustic 🥁
- bass 🔉
- blues 🎷️
- classical 🎻️
- club 🎛️
- custom 🎨
- hifi 💥️
- laptop 💻️
- latin 👠️
- lofi 🍃️
- podcast 🎙
- pop 🎤️
- radio 📻️
- rock 🎸️
- vocal 👄️
  
</p>
</details>
  
- Support for newer versions of [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects) (included in the [Ubuntu repositories](https://packages.ubuntu.com/)).
- A simple guide on how to build them (under development 🚧).

**Sounds amazing!?** 🥳 Then support me with a ⭐️ and a follow! 😎️

## INSTALLATION 🚀️

[![Source Tarball](https://img.shields.io/badge/-Source_zip-green.svg?style=for-the-badge)](https://github.com/p-chan5/EasyPulse/archive/refs/heads/main.zip)
[![All versions](https://img.shields.io/badge/-All_Versions-lightgrey.svg?style=for-the-badge)](https://github.com/p-chan5/EasyPulse/releases)

1. Unzip and move the `.js` files to one of the following paths or use the `Import a preset` button:

<details>
<summary>EasyEffects</summary>
<p>
  
* Flatpak: `~/.var/app/com.github.wwmm.easyeffects/config/output`
* Repositories: `~/.config/easyeffects/output`
  
</p>
</details>

<details> 
<summary>PulseEffects</summary>
<p>

* Flatpak: `~/.var/app/com.github.wwmm.pulseeffects/.config/output`
* Repositories: `~/.config/PulseEffects/output`

</p>
</details>

2. Finally load your favorite from `Presets`

![presets_output](https://user-images.githubusercontent.com/123143444/215234552-4046d7d2-0270-4364-9a69-ed5b59c6f563.png)

## A BIT OF HISTORY 📖️
The other day I was looking for some presets on the web. The first result I came across was [JackHack96's repository](https://github.com/JackHack96/EasyEffects-Presets) I tried them but **they were not capable enough for what they promised (Bass Enhancement and Perfect EQ)** so I decided to create my own and share them with the community!

## INSPIRATION 💡
Much of it comes from the presets offered by the `macOS` equalizer (note that **the settings are not exactly the same**).

<img src="https://user-images.githubusercontent.com/123143444/215025761-689f1011-f8bb-4bb0-aebe-6c206148c670.jpg" height="250"> <img src="https://user-images.githubusercontent.com/123143444/215027219-54166db1-a36d-4f0b-bcd8-b717db550f6a.jpg" height="250">

## PHILOSOPHY 🧠
All ideas and comments are welcome as long as you are respectful of others. Feel free to suggest changes or make them in a [fork](https://github.com/p-chan5/EasyPulse/fork) after all we do this for fun!

## UNLOCK THE POTENTIAL OF YOUR SPEAKERS AND HEADPHONES 🔓
**You don't need overpriced equipment to get good results!** For example I use `sony-mdr-zx110` headphones and a `low-end laptop` running `PulseAudio` (factory sound card). What is the potential of yor equipment? Please be realistic. Maybe you just need to reduce an annoying frequency (use `custom` for it) or increase the lows.

## THE EQUALIZER IS EVERYTHING 🤯️

<img src=https://user-images.githubusercontent.com/123143444/215235039-93d2e6a0-2aaf-488f-b8a7-6a02f0b7c749.png height="250" align="right">

You may be wondering what is special about your presets? 🤨️ The answer is: The `Equalizer` or as I usually call it: **"The Soul"**. Just remember that **a clean sound will be the result of a correct EQ**

[EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects) includes the [LSP equalizer](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_stereo) (the best option so far) so you just need to find the correct frequency: `(25Hz - 12.8kHz)` + the appropriate parameters: `(Slope x4 / Q 5.00)` and you're ready to go! I wish I could explain this in more detail but that's pretty much all I did. 🙂️ Lie! I tried with the following frequency ranges: `(20Hz - 10.2kHz)` / `(30Hz - 15.4kHz)` / `(35Hz - 17.9kHz)` but none sound better than `(25Hz - 12.8kHz)`

So I migrated this settings to `lsp-plugins-para-equalizer-x32-stereo` and I did toggling between `5 dB` to `-5 dB` Here are the 👽️ results:

<p align="center">
<img src=https://user-images.githubusercontent.com/123143444/215234666-ac75f0bf-35ed-45a7-8e30-1905b49ccb58.gif height="200"> <img src=https://user-images.githubusercontent.com/123143444/215234752-f4d334ba-a793-4cde-a0b8-57a7a6989236.gif height="200">
</p>

## TIPS ✨️

<img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align="right"> <img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align="right">

### BASS AND HIGHS 💯️
I applied `subtractive EQ` to each preset (the cleanest option) this means that **you will not see any EQ bands with gain above** `0 dB` but if you want to give them more presence increase `50Hz` and `12.8kHz`

### ON OR OFF 🤔️
Some effects like `Reverberation` or `Delay` are disabled for obvious reasons (you might like it or not). **Be sure to activate them and test them!** Finally save your settings by rewriting the preset.

![on_or_off](https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png)

### LIMITER ON STAGE 🎭
The limiter has a good and a bad side (this will depend on how much you force him to act) on the one hand it will prevent the modified signal from exceeding `0 dB` and being distorted on the other hand it could kill the dynamics of the source and push it below the threshold.

[EasyEffects](https://github.com/wwmm/easyeffects) includes the [LSP limiter](https://lsp-plug.in/?page=manuals&section=limiter_stereo) (more advanced in theory) which **can achieve transparent results with the right settings!** But even with this **the signal is still hanging by a thread and... You move that thread!** The simplest solution is to lower the `Output Volume` of the `Equalizer` or the `Input Level` of the `Limiter` (at least for [PulseEffects](https://github.com/wwmm/pulseeffects))

<img src=https://user-images.githubusercontent.com/123143444/215234944-83711bc0-f037-4a1d-badd-42e0eeeb2e8b.png height="100">

But... **for nothing in the world do you think of turning it off!** ⚠️ or any incoming signal greater than `0 dB` could be harmful to your hearing 👂️☠️ or your equipment 💻️🎧️☠️

## UPDATE CYCLE ⚡️
I can only offer support for new versions included in the [Ubuntu releases](https://ubuntu.com/about/release-cycle). This is the case of [EasyEffects](https://github.com/wwmm/easyeffects) that was included since `22.10` but **maintainers are always welcome!** Contact me by opening a [New Issue](https://github.com/p-chan5/EasyPulse/issues/new/choose).

## COMPATIBILITY ISSUES ⚠️
I recommend `upgrading` or `downgrading` your version to avoid having to deal with this. [EasyEffects](https://github.com/wwmm/easyeffects) regularly changes the structure of its `.js` files (which is why they need to be rebuilt) but for [PulseEffects](https://github.com/wwmm/pulseeffects) this is different since their files have no further changes! It's up to you...

## HOW TO BUILD THEM 🏗️
(under development 🚧)

## FAQ ❓
**What does EasyPulse mean?**
Just a weird mix of the words [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects) 😜️ or if you want: "Made to be `Easy` 🙌️ Made with the `Pulse` of the soul ❤️"
