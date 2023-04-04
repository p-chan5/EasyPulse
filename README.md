A set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/229336611-5696d3ff-0eea-406f-b443-29f69072dac4.gif height=185> <img src=https://user-images.githubusercontent.com/123143444/229336618-77c24ad1-d454-4053-a1d7-da1334b24000.gif height=185>
</p>

<p align=center>
Made to be Easy. Made with the Pulse of the Soul. ❤️
</p>

## WHAT'S INSIDE? 🎁

<details>
<summary>8 configuration profiles.</summary>
<p>

- classical 🎻️
- custom 🎨
- edm 🎹
- hifi 💥️
- kpop 🎤️
- lofi 🍃️
- podcast 🎙
- rock 🎸️
  
</p>
</details>
  
- Support for new versions included in the [Ubuntu repositories](https://packages.ubuntu.com/). For old see: [HOW TO BUILD THEM](https://github.com/p-chan5/EasyPulse/wiki/HOW-TO-BUILD-THEM).

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

3. It's done! Load them from `Presets` > `Output`

<img src=https://user-images.githubusercontent.com/123143444/216798224-68a8b6b7-dee3-4a8b-b7d4-ee1396b30a3d.png>
<img src=https://user-images.githubusercontent.com/123143444/215234552-4046d7d2-0270-4364-9a69-ed5b59c6f563.png>
<img src=https://user-images.githubusercontent.com/123143444/217419736-f55194b2-617b-4947-812c-8e312cd2b195.png>

## PHILOSOPHY 🧠

All ideas and comments are welcome as long as you are respectful of others. Feel free to suggest changes or make them on a [fork](https://github.com/p-chan5/EasyPulse/fork) after all, we do this for fun!

## UNLOCK THE POTENTIAL OF YOUR EQUIPMENT 🔓

You don't need expensive headphones or speakers to get good results, because they're designed to work on any architecture.

## THE EQUALIZER IS EVERYTHING 🤯️

<img src=https://user-images.githubusercontent.com/123143444/219545184-953ee563-9730-4f98-b28a-d4eb71031288.png height=250 align=right>

Achieving professional results is difficult even with the right tools. You might think that something is much more complicated than it seems, but you just need to look back. In this case, a clean sound will be the result of a correct EQ or also known as: [Subtractive EQ](https://producerhive.com/music-production-recording-tips/subtractive-vs-additive-eq/).

Both versions include LSP equalizer (the best FOSS option so far) So we need to set the range and filter characteristics: `(25Hz - 12.8kHz)` `(RLC (MT) / Slope x4 / Q 5.00)`

For testing purposes I migrated this setting to `para-equalizer-x32-stereo` and toggled between `5 dB` and `-5 dB`

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/229336718-a29eac21-2fdd-4b9f-8440-178a7b186590.gif height=200> <img src=https://user-images.githubusercontent.com/123143444/223950404-f540e6dc-cf83-4eee-92b8-d064bdc75b63.gif height=200>
</p>

## SOPHISTICATED SURROUND 🪡

This feature exclusive for EE `=>7.0.0` (equal to or greater than). Inspired by the video: [Are You Using This EQ Trick? Left and Right Channel EQ](https://www.youtube.com/watch?v=RzRmw4rNY90) by Michael Wynne aka [In The Mix](https://www.youtube.com/@inthemix).

<img src=https://user-images.githubusercontent.com/123143444/223876846-7a4a3463-3ff2-48f3-a8d8-bd61a5c245f0.gif>
<img src=https://user-images.githubusercontent.com/123143444/229336921-4a7655ba-08b0-4863-9e91-70bd4e52a777.png height=225>

## EFFECTS 🎛️

### CROSSFEED 🎧

Reduces the stereo signal via `Feed` / `Cutoff` sets the limit of frequencies it affects.

### EQUALIZER 2 🧬

Expands the signal recreating a Dolby Atmosphere.

### LOUDNESS 📢️

It gives more prominence to the bass in exchange for reducing other frequencies (see graph). Use it with `Auto Gain`

<img src=https://user-images.githubusercontent.com/123143444/229337025-00e7ccc2-6a85-4a43-96a5-8f4c694c7c1c.png height=200>

### REVERBERATION ⛰️

Increase `Wet Level / Amount` to make it more noticeable.

### DELAY 👥️

Switch to full stereo mode. The most common range for the right channel is `20.00 ms` to `35.00 ms`

### AUTO GAIN 🛠

Corrects the volume based on a `Target` = `-10.0 dB` / `Reset History` reevaluates this operation (refresh).

### MAXIMIZER 👂

Prevents the signal from exceeding `0 dB` and becoming distorted.

## TIPS ✨️

### BASS AND HIGHS 💯️

<img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align=right> <img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align=right>

To give them more presence increase the gain of the `50.0 Hz` and `12.8 kHz` frequencies (see graph).

<img src=https://user-images.githubusercontent.com/123143444/222322134-13715ad6-ad24-4918-ba9f-3ee8e9a92ef3.png height=200>

Also turn down the Equalizer Output (a little is enough). This will prevent the dynamics from being messed up as it goes through the Maximizer.

<img src=https://user-images.githubusercontent.com/123143444/222323070-6157e24a-524b-4140-8961-6745b86a1732.png>

### ON OR OFF? 🤔️

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save it by rewriting the original file.

<img src=https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png>
<img src=https://user-images.githubusercontent.com/123143444/216798874-1055f53a-0029-45dd-b58c-1e4f1ee47198.png>

## COMPATIBILITY ISSUES ⚠️

I recommend upgrading / downgrading your version to avoid having to deal with this. EasyEffects changes the structure of its `.js` files from time to time, but for PulseEffects this is different, since their files have no further changes!

## LOOK IT UP ON THE WIKI 📖

FAQ and more can be found [here](https://github.com/p-chan5/EasyPulse/wiki).

## SCHEDULE 📅

0.8.0 - July 8 2023

- Add 3rd Equalizer 🧬
- Add Bass Enhancer 💪

## HELP LINKS 🔗

### Crossfeed

- [Bauer stereophonic-to-binaural DSP](https://bs2b.sourceforge.net/)

### Equalizer

- [LSP Parametric Equalizer x32 LeftRight](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_lr)
- [FL Studio | Fruity Parametric EQ 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Parametric%20EQ%202.htm)
- [Equalizers tutorial | MeldaProduction](https://www.meldaproduction.com/tutorials/text/equalizers)
- [IRR vs FIR: Understanding their differences](https://www.juansaudio.com/post/iir-vs-fir-understanding-their-differences)

### Loudness

- [LSP Loudness Compensator Stereo](https://lsp-plug.in/?page=manuals&section=loud_comp_stereo)

### Reverberation

- [Calf Studio Gear | Reverb](https://calf-studio-gear.org/doc/Reverb.html)
- [FL Studio | Fruity Reeverb 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Reeverb%202.htm)

### Delay

- [LSP Delay Compensator x2 Stereo](https://lsp-plug.in/?page=manuals&section=comp_delay_x2_stereo)
- [FL Studio | Fruity Stereo Enhancer](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Stereo%20Enhancer.htm)

### Maximizer

- [zam-plugins](https://www.zamaudio.com/?p=976)
