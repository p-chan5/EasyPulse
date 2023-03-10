A set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/224163501-4ec7f1a0-340f-4c8b-829d-e28e1a23954f.gif height=185> <img src=https://user-images.githubusercontent.com/123143444/224163527-0cad887d-2f04-4c77-a77a-c1030e905ac3.gif height=185>
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
- hifi 💥️
- kpop 🎤️
- lofi 🍃️
- podcast 🎙
- rock 🎸️
- surround 🧬
  
</p>
</details>
  
- Support for new versions included in the [Ubuntu repositories](https://packages.ubuntu.com/).
- A guide on how to build them.

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

You don't need expensive headphones or speakers to achieve good results. At first they were created to clean the signal from my `sony-mdr-zx110` but then I realized that they work on any other architecture!

## THE EQUALIZER IS EVERYTHING 🤯️

<img src=https://user-images.githubusercontent.com/123143444/219545184-953ee563-9730-4f98-b28a-d4eb71031288.png height=250 align=right>

Achieving professional results is difficult even with the right tools. You might think that something is much more complicated than it seems but in reality you just need to look back. In this case, a clean sound will be the result of a correct EQ or commonly known as [Subtractive EQ](https://producerhive.com/music-production-recording-tips/subtractive-vs-additive-eq/).

Both versions include LSP equalizer (the best FOSS option so far) so you just need to find the most pleasing range and parameters `(25Hz - 12.8kHz)` `(RLC (MT) / Slope x4 / Q 5.00)` and you're done!

For testing purposes I migrated this setting to `para-equalizer-x32-stereo` and toggled between `5 dB` and `-5 dB`

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/224163786-8fd6f226-bc37-457e-bf1b-182a70777f47.gif height=200> <img src=https://user-images.githubusercontent.com/123143444/223950404-f540e6dc-cf83-4eee-92b8-d064bdc75b63.gif height=200>
</p>

## SOPHISTICATED SURROUND 🪡

We have put all our effort into this advanced preset. We hope this is the definitive answer to the demand imposed by Linux users for years: ***"Quality sound, without much chatter..."*** Inspired by the video [Are You Using This EQ Trick? Left and Right Channel EQ](https://www.youtube.com/watch?v=RzRmw4rNY90) by user Michael Wynne aka [In The Mix](https://www.youtube.com/@inthemix).

> hifi 💥️ + `Split Channels` = surround 🧬

<img src=https://user-images.githubusercontent.com/123143444/223876846-7a4a3463-3ff2-48f3-a8d8-bd61a5c245f0.gif>
<img src=https://user-images.githubusercontent.com/123143444/223869569-7d9ac67f-9263-4116-a0d6-9c1f618997eb.png height=200>

## EFFECTS 🎛️

### CROSSFEED 🎧

Center the signal via `Feed` / `Cutoff` sets the limit of frequencies it affects (these values are maxed out so you can hear them).

### REVERBERATION ⛰️

Increase `Wet Level / Amount` to make it more noticeable. Try going beyond these values, you can achieve creative results with some practice.

### DELAY 👥️

Switch to full stereo mode. The most common range for the right channel is `20.00 ms` to `35.00 ms`

### AUTO GAIN 🛠

Corrects the signal volume based on a `Target` We use `-10.0 dB` but it can also be a value equal to or greater than `-6.0 dB` / `Reset History` reevaluates this operation (refresh).

### MAXIMIZER 👂

Prevents the signal from exceeding `0 dB` and becoming distorted.

## TIPS ✨️

### BASS AND HIGHS 💯️

<img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align=right> <img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align=right>

If you want to give them more presence increase the gain of the `50.0 Hz` and `12.8 kHz` frequencies (see graph).

<img src=https://user-images.githubusercontent.com/123143444/222322134-13715ad6-ad24-4918-ba9f-3ee8e9a92ef3.png height=200>

Also lower the output volume of the Equalizer (a little is enough). This will prevent the dynamics from being ruined as it goes through the Maximizer.

<img src=https://user-images.githubusercontent.com/123143444/222323070-6157e24a-524b-4140-8961-6745b86a1732.png>

### ON OR OFF? 🤔️

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save this setting by rewriting the original file.

<img src=https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png>
<img src=https://user-images.githubusercontent.com/123143444/216798874-1055f53a-0029-45dd-b58c-1e4f1ee47198.png>

## COMPATIBILITY ISSUES ⚠️

I recommend upgrading or downgrading your version to avoid having to deal with this. EasyEffects changes the structure of its `.js` files from time to time (so they need to be rebuilt) but for PulseEffects this is different, since their files have no further changes!

## HOW TO BUILD THEM 🏗️

This is a manual process summarized in 11 steps:

1. Add them in the following order: Crossfeed > Equalizer > Reverberation > Delay > Auto Gain > Maximizer (reset each to its default values).

<img src=https://user-images.githubusercontent.com/123143444/216802921-bbd53003-2f54-477f-8a96-534f4ea7b6fa.png>

2. Select Crossfeed. Set the following values:

Cutoff|Feed
:---:|:---:
2000 Hz|1.0 dB

3. Select Equalizer. Set the following values:

Bands
:---:
10

1|2|3|4|5|6|7|8|9|10
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz

Band|Mode|Slope|Quality
:---:|:---:|:---:|:---:
All|RLC (MT)|x4|5.00

4. Select Reverberation. Set the following values:

High Frequency Damping|Room Size|Diffusion|Pre Delay|Decay Time|Wet Level / Amount|Bass Cut|Treble Cut
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
12800 Hz|Large/smooth|0.00|25.00 ms|0.40 s|-6.0 dB|200 Hz|12800 Hz

5. Select Delay. Set the following values:

Right
:---:
25.00 ms

6. Select Auto Gain. Set the following values:

EasyEffects:

Target|Reference
:---:|:---:
-10.0 dB|Integrated

PulseEffects:

Use Geometric Mean|Target|Integrated
:---:|:---:|:---:
Disable|-10.0 dB|100

7. Turn off Crossfeed > Reverberation > Delay > Auto Gain
8. Save as `custom`
9. Select Equalizer. Reduce band gain and save each setting according to its name. Load `custom` to start over.

Name|25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
classical 🎻️|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00|0.00
custom 🎨|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00
hifi 💥️|0.00|0.00|0.00|-15.00|-12.00|-12.00|-12.00|-15.00|0.00|0.00
kpop 🎤️|0.00|0.00|0.00|-4.00|-8.00|-12.00|-8.00|-4.00|0.00|0.00
lofi 🍃️|0.00|0.00|0.00|-6.00|-12.00|-12.00|-6.00|0.00|0.00|0.00
podcast 🎙|0.00|0.00|-3.00|-6.00|-9.00|-9.00|-6.00|-3.00|0.00|0.00
rock 🎸️|0.00|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00

10. Load `hifi` > Select Equalizer. Set the following values:

Split Channels
:---:
Enable

Channel|25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
Left|0.00|0.00|0.00|-15.00|-9.00|-12.00|-12.00|-12.00|0.00|0.00
Right|0.00|0.00|0.00|-12.00|-12.00|-12.00|-9.00|-15.00|0.00|0.00

11. Save as `surround`

## LOOK IT UP ON THE WIKI 📖

FAQ and more can be found [here](https://github.com/p-chan5/EasyPulse/wiki).

## SCHEDULE 📅

0.7.0 - 6 April 2023

- Add Loudness 📢️
- Enhance Surround 🧬
- Improve Reverberation ⛰️

0.8.0 - ???

- Add Bass Enhancer 💪
- Add Multiband Compressor 🔥

## HELP LINKS 🔗

### Crossfeed

- [Bauer stereophonic-to-binaural DSP](https://bs2b.sourceforge.net/)
- [bs2b: GStreamer Bad Plugins 1.0 Plugins](https://gstreamer.freedesktop.org/data/doc/gstreamer/head/gst-plugins-bad/html/gst-plugins-bad-plugins-bs2b.html)

### Equalizer

- [LSP | Parametric Equalizer x32 LeftRight](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_lr)
- [FL Studio | Fruity Parametric EQ 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Parametric%20EQ%202.htm)
- [Equalizers tutorial | MeldaProduction](https://www.meldaproduction.com/tutorials/text/equalizers)
- [IRR vs FIR: Understanding their differences](https://www.juansaudio.com/post/iir-vs-fir-understanding-their-differences)

### Reverberation

- [Calf Studio Gear | Reverb](https://calf-studio-gear.org/doc/Reverb.html)
- [FL Studio | Fruity Reeverb 2](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Reeverb%202.htm)

### Delay

- [LSP | Delay Compensator x2 Stereo](https://lsp-plug.in/?page=manuals&section=comp_delay_x2_stereo)
- [FL Studio | Fruity Stereo Enhancer](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/Fruity%20Stereo%20Enhancer.htm)

### Maximizer

- [zam-plugins](https://www.zamaudio.com/?p=976)
