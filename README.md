A set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/230702814-1daf5bfa-836b-4eb3-9ce6-b403979827b7.gif height=185> <img src=https://user-images.githubusercontent.com/123143444/230702819-1c902967-d224-43e4-899c-f5c9fc60a9e6.gif height=185>
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
<img src=https://user-images.githubusercontent.com/123143444/230702849-20a4a13d-6515-43a0-8d79-456387e11a03.gif height=200> <img src=https://user-images.githubusercontent.com/123143444/223950404-f540e6dc-cf83-4eee-92b8-d064bdc75b63.gif height=200>
</p>

## SOPHISTICATED SURROUND 🪡

This feature is exclusive for users of EasyEffects `7.0.0` or higher. For it to work you must turn on one of the other two Equalizers (without forgetting the first one) and that's it :) **Please don't do more than that!** Editing them is our job (means they can be easily broken by the end user).

Inspired by the video: [Are You Using This EQ Trick? Left and Right Channel EQ](https://www.youtube.com/watch?v=RzRmw4rNY90) by Michael Wynne aka [In The Mix](https://www.youtube.com/@inthemix).

<img src=https://user-images.githubusercontent.com/123143444/223876846-7a4a3463-3ff2-48f3-a8d8-bd61a5c245f0.gif>
<img src=https://user-images.githubusercontent.com/123143444/230560382-809e22ec-a12c-4167-a59f-988d62fe9d2f.gif height=230>

## EFFECTS 🎛️

### CROSSFEED 🎧

Reduces the stereo signal via `Feed` / `Cutoff` sets the limit of frequencies it affects.

### BASS ENHANCER 💪

It will make it sound crunchier.

### 2ND EQUALIZER 🧬

Expands the signal recreating a **smooth** `Dolby Atmos` (for modern music).

### 3RD EQUALIZER 🧬

Expands the signal recreating a **harsh** `Dolby Atmos` (for heavy music).

### LOUDNESS 📢️

It gives more prominence to the bass in exchange for reducing other frequencies (see graph). Use it with `Auto Gain`

<img src=https://user-images.githubusercontent.com/123143444/229337025-00e7ccc2-6a85-4a43-96a5-8f4c694c7c1c.png height=200>

### REVERBERATION ⛰️

Increase `Wet Level / Amount` to make it more noticeable.

### DELAY 👥️

Switch to full stereo mode. The most common range for the right channel is `20.00 ms` to `35.00 ms`

### AUTO GAIN 🛠

Corrects the volume based on a `Target` = `-10.0 dB` / `Reset History` reevaluates this operation (refresh) / `Maximum History` is arbitrary.

### MAXIMIZER 👂

Prevents the signal from exceeding `0 dB` and becoming distorted.

## TIPS ✨️

### BASS AND HIGHS 💯️

<img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align=right> <img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align=right>

To give them more presence increase the gain of the `50.0 Hz` and `12.8 kHz` frequencies of the 1st Equalizer.

### ON OR OFF? 🤔️

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save it by rewriting the original file.

<img src=https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png>
<img src=https://user-images.githubusercontent.com/123143444/216798874-1055f53a-0029-45dd-b58c-1e4f1ee47198.png>

## COMPATIBILITY ISSUES ⚠️

Since we **DO NOT** support old versions, it is vital that you have the current stable branch (either EE or PE) for them to work.

## LOOK IT UP ON THE WIKI 📖

FAQ and more can be found [here](https://github.com/p-chan5/EasyPulse/wiki).

## SCHEDULE 📅

0.9.0 - ???

We'll put something here when we feel more creative...

## HELP LINKS 🔗

### Crossfeed

- [Bauer stereophonic-to-binaural DSP](https://bs2b.sourceforge.net/)

### Equalizer

- [LSP Parametric Equalizer x32 LeftRight](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_lr)
- [FL Studio | Fruity Parametric EQ 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Parametric%20EQ%202.htm)
- [Equalizers tutorial | MeldaProduction](https://www.meldaproduction.com/tutorials/text/equalizers)
- [IRR vs FIR: Understanding their differences](https://www.juansaudio.com/post/iir-vs-fir-understanding-their-differences)

### Bass Enhancer

- [Calf Studio Gear | Bass Enhancer](https://calf-studio-gear.org/doc/Bass%20Enhancer.html)

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
