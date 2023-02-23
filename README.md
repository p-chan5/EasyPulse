A set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/220776157-734288e4-5244-4211-a872-91c5b0bb9a11.gif height=185> <img src=https://user-images.githubusercontent.com/123143444/220776177-bafa90b6-c2c0-4dd8-a45c-915cad8243c0.gif height=185>
</p>

<p align=center>
Made to be Easy. Made with the Pulse of the Soul. ❤️
</p>

## WHAT'S INSIDE? 🎁

<details>
<summary>8 presets with bedroom and stereo effects included.</summary>
<p>

- classical 🎻️
- club 🍸
- custom 🎨
- hifi 💥️
- kpop 🎤️
- lofi 🍃️
- podcast 🎙
- rock 🎸️
  
</p>
</details>
  
- Support for new versions included in the [Ubuntu repositories](https://packages.ubuntu.com/).
- A simple guide on how to build them.

Do they sound amazing? Then support me with a ⭐️ and a follow!

## INSTALLATION 🚀️

1. Go to [Releases](https://github.com/p-chan5/EasyPulse/releases) and download the latest version as `Source code` (zip) or (tar.gz)
2. Unzip and move the `.js` files to one of the following paths:

EasyEffects:
  
* Flatpak: `~/.var/app/com.github.wwmm.easyeffects/config/output`
* Repositories: `~/.config/easyeffects/output`

PulseEffects:

* Flatpak: `~/.var/app/com.github.wwmm.pulseeffects/.config/output`
* Repositories: `~/.config/PulseEffects/output`

3. It's done! `Load` them from `Presets` > `Output`

<img src=https://user-images.githubusercontent.com/123143444/216798224-68a8b6b7-dee3-4a8b-b7d4-ee1396b30a3d.png>
<img src=https://user-images.githubusercontent.com/123143444/215234552-4046d7d2-0270-4364-9a69-ed5b59c6f563.png>
<img src=https://user-images.githubusercontent.com/123143444/217419736-f55194b2-617b-4947-812c-8e312cd2b195.png>

## PHILOSOPHY 🧠

All ideas and comments are welcome as long as you are respectful of others. Feel free to suggest changes or make them on a [fork](https://github.com/p-chan5/EasyPulse/fork) after all, we do this for fun!

## UNLOCK THE POTENTIAL OF YOUR EQUIPMENT 🔓

You don't need expensive headphones or speakers to achieve good results. They were created with the aim of cleaning up the signal. So if they sound amazing with my `sony-mdr-zx110` maybe yours is no exception!

## THE EQUALIZER IS EVERYTHING 🤯️

<img src=https://user-images.githubusercontent.com/123143444/219545184-953ee563-9730-4f98-b28a-d4eb71031288.png height=250 align=right>

Achieving professional results is difficult even with the right tools. You might think that something is much more complicated than it seems but in reality you just need to look back. In this case, a clean sound will be the result of a correct EQ or commonly known as [Subtractive EQ](https://producerhive.com/music-production-recording-tips/subtractive-vs-additive-eq/).

Both versions include LSP equalizer (the best FOSS option so far) so you just need to find the most pleasing range and parameters `(25Hz - 12.8kHz)` `(RLC (MT) / Slope x4 / Q 5.00)` and you're done!

For testing purposes I migrated this setting to `para-equalizer-x32-stereo` and toggled between `5 dB` and `-5 dB`

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/220776374-7f857e4d-5e8b-4c3e-b99f-9abf3000e8b8.gif height=200> <img src=https://user-images.githubusercontent.com/123143444/219545396-a5cf41b2-fb82-4174-9883-c1461b473764.gif height=200>
</p>

## EFFECTS 🎛️

### REVERBERATION ⛰️

Increase the `Amount` to make it more noticeable. Try going beyond these values, you can achieve creative results with some practice.

### DELAY 👥️

Sets a delay in `ms` on the right channel (the most common) achieving a stereo effect. Try ranges from `20.00 ms` to `35.00 ms`

### MAXIMIZER 👂

Prevents the signal from exceeding `0 dB` and becoming distorted.

## TIPS ✨️

### BASS AND HIGHS 💯️

<img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align=right> <img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align=right>

If you want to give them more presence increase the gain of the `50.0 Hz` and `12.8 kHz` frequencies (see graph).

<img src=https://user-images.githubusercontent.com/123143444/219545652-2a875057-5fe0-4ce4-8e3e-f12173c23893.gif height=200>

### ON OR OFF? 🤔️

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save this setting by rewriting the original file.

<img src=https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png>
<img src=https://user-images.githubusercontent.com/123143444/216798874-1055f53a-0029-45dd-b58c-1e4f1ee47198.png>

## COMPATIBILITY ISSUES ⚠️

I recommend upgrading or downgrading your version to avoid having to deal with this. EasyEffects regularly changes the structure of its `.js` files (which is why they need to be rebuilt) but for PulseEffects this is different, since their files have no further changes!

## HOW TO BUILD THEM 🏗️

This is a manual process summarized in a few steps:

1. Add them in the following order: Equalizer > Reverberation > Delay > Maximizer (reset each to its default values).

<img src=https://user-images.githubusercontent.com/123143444/216802921-bbd53003-2f54-477f-8a96-534f4ea7b6fa.png>

2. Select Equalizer. Set the following values:

Bands
:---:
10

1|2|3|4|5|6|7|8|9|10
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz

Band|Mode|Slope|Quality
:---:|:---:|:---:|:---:
All|RLC (MT)|x4|5.00

3. Select Reverberation. Set the following values:

High Frequency Damping|Room Size|Diffusion|Pre Delay|Decay Time|Wet Level / Amount|Bass Cut|Treble Cut
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
12800 Hz|Large/smooth|0.00|25.00 ms|0.40 s|-6.0 dB|200 Hz|12800 Hz

4. Select Delay. Set the following values:

Right
:---:
25.00 ms

5. Turn off Reverberation and Delay
6. Save this setting as `custom`
7. Select Equalizer. Reduce band gain and save each setting according to its name. Load `custom` to start over.

Name|25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
classical 🎻️|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00|0.00
club 🍸|0.00|0.00|0.00|-10.00|-10.00|-10.00|-10.00|-10.00|0.00|0.00
custom 🎨|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00
hifi 💥️|0.00|0.00|0.00|-15.00|-12.00|-12.00|-12.00|-15.00|0.00|0.00
kpop 🎤️|0.00|0.00|0.00|-4.00|-8.00|-12.00|-8.00|-4.00|0.00|0.00
lofi 🍃️|0.00|0.00|0.00|-6.00|-12.00|-12.00|-6.00|0.00|0.00|0.00
podcast 🎙|0.00|0.00|-3.00|-6.00|-9.00|-9.00|-6.00|-3.00|0.00|0.00
rock 🎸️|0.00|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00

## LOOK IT UP ON THE WIKI 📖

Tutorials / FAQs / settings and more can be found [here](https://github.com/p-chan5/EasyPulse/wiki).

## HELP LINKS 🔗

### Equalizer

- [LSP | Parametric Equalizer x32 LeftRight](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_lr)
- [FL Studio | Fruity Parametric EQ 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Parametric%20EQ%202.htm)
- [Equalizers tutorial | MeldaProduction](https://www.meldaproduction.com/tutorials/text/equalizers)

### Reverberation

- [Calf Studio Gear | Reverb](https://calf-studio-gear.org/doc/Reverb.html)
- [FL Studio | Fruity Reeverb 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Reeverb%202.htm)

### Delay

- [LSP | Delay Compensator x2 Stereo](https://lsp-plug.in/?page=manuals&section=comp_delay_x2_stereo)
- [FL Studio | Fruity Stereo Enhancer](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Stereo%20Enhancer.htm)

### Maximizer

- [zam-plugins](https://www.zamaudio.com/?p=976)
