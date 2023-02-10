A complete set of `High Quality` presets for [EasyEffects](https://github.com/wwmm/easyeffects) and [PulseEffects](https://github.com/wwmm/pulseeffects).

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/215234342-4a49f39b-9092-4916-94c1-3d8e0c6a9b06.gif height=185> <img src=https://user-images.githubusercontent.com/123143444/215234349-585700f8-f45e-4162-8de5-3141da05573f.gif height=185>
</p>

<p align=center>
Made to be Easy. Made with the Pulse of the Soul. ❤️
</p>

## WHAT'S INSIDE? 🎁

<details>
<summary>15 presets with bedroom and stereo effects included.</summary>
<p>
  
- acoustic 🥁
- bass 🔊️
- classical 🎻️
- club 🍸
- custom 🎨
- hifi 💥️
- jazz 🎷️
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
  
- Support for new versions included in the [Ubuntu repositories](https://packages.ubuntu.com/).
- A simple guide on how to build them.

Sounds amazing!? Then support me with a ⭐️ and a follow! 😎️

## INSTALLATION 🚀️

1. Go to [Releases](https://github.com/p-chan5/EasyPulse/releases) and download the latest version as `Source code` (zip) or (tar.gz)
2. Unzip and move the `.js` files to one of the following paths or use the `Import a preset` button:

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

## INSPIRATION 💡

At first I replicated the macOS equalizer configuration. This sounded unnatural so I decided to find my identity taking into account the needs of each user. The result is in your ears.

<img src=https://user-images.githubusercontent.com/123143444/215025761-689f1011-f8bb-4bb0-aebe-6c206148c670.jpg height=250> <img src=https://user-images.githubusercontent.com/123143444/215027219-54166db1-a36d-4f0b-bcd8-b717db550f6a.jpg height=250>

## PHILOSOPHY 🧠

All ideas and comments are welcome as long as you are respectful of others. Feel free to suggest changes or make them on a [fork](https://github.com/p-chan5/EasyPulse/fork) after all, we do this for fun!

## UNLOCK THE POTENTIAL OF YOUR EQUIPMENT 🔓

You don't need expensive headphones or speakers to achieve good results. They were created with the goal of cleaning up the signal rather than boosting it. So if they sound amazing with my `sony-mdr-zx110` maybe yours is no exception!

## THE EQUALIZER IS EVERYTHING 🤯️

<img src=https://user-images.githubusercontent.com/123143444/215235039-93d2e6a0-2aaf-488f-b8a7-6a02f0b7c749.png height=250 align=right>

Achieving professional results is difficult even with the right tools. You might think that something is much more complicated than it seems but in reality you just need to look back. In this case, a clean sound will be the result of a correct EQ or as it is commonly called: [Subtractive EQ](https://producerhive.com/music-production-recording-tips/subtractive-vs-additive-eq/).

Both versions include [LSP equalizer](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_stereo) (the best FOSS option so far) so you just need to find the most pleasant frequency `(25Hz - 12.8kHz)` plus the right parameters `(Slope x4 / Q 5.00)` and you're done!

For testing purposes I migrated this setting to `lsp-plugins-para-equalizer-x32-stereo` and toggled between `5 dB` and `-5 dB`

<p align=center>
<img src=https://user-images.githubusercontent.com/123143444/215234666-ac75f0bf-35ed-45a7-8e30-1905b49ccb58.gif height=200> <img src=https://user-images.githubusercontent.com/123143444/216798159-87db5cf8-4605-4d60-b5ee-8c4079913e15.gif height=200>
</p>

## EFFECTS 🎛️

### REVERBERATION ⛰️

Increase the `Amount` to make it more noticeable. Try going beyond these values, you can achieve creative results with some practice.

### DELAY 👥️

Sets a delay in `ms` on the right channel (the most common) achieving a stereo effect. Try ranges from `20.00 ms` to `35.00 ms`

## TIPS ✨️

### BASS AND HIGHS 💯️

<img src=https://user-images.githubusercontent.com/123143444/215235895-87678de3-354c-4ba2-809f-b31e7ac3806f.png align=right> <img src=https://user-images.githubusercontent.com/123143444/215235885-465b77b5-8c2a-44c2-8a68-5d986d1701eb.png align=right>

If you want to give them more presence increase the gain of the `50.0 Hz` and `12.8 kHz` frequencies (see graph).

<img src=https://user-images.githubusercontent.com/123143444/216798644-428aceab-8321-4733-8706-567839324f8e.gif height=200>

### ON OR OFF? 🤔️

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save this setting by rewriting the original file.

<img src=https://user-images.githubusercontent.com/123143444/215234907-d390dbc2-db7e-4a4a-a706-f00c236a6060.png>
<img src=https://user-images.githubusercontent.com/123143444/216798874-1055f53a-0029-45dd-b58c-1e4f1ee47198.png>

### LIMITER ON STAGE 🎭

The limiter has a good and a bad side (this will depend on how much you force it to act) on the one hand it will prevent the modified signal from exceeding `0 dB` and distorting, on the other hand it could kill the dynamics of the source.

You can achieve transparent results with the right settings (still working on it). For now the simplest solution is to lower the Equalizer `Output Volume` or the Limiter `Input Level` but don't even think of turning it off! or any incoming signal above `0 dB` could be harmful to your hearing or your equipment.

<img src=https://user-images.githubusercontent.com/123143444/215234944-83711bc0-f037-4a1d-badd-42e0eeeb2e8b.png>

## COMPATIBILITY ISSUES ⚠️

I recommend upgrading or downgrading your version to avoid having to deal with this. EasyEffects regularly changes the structure of its `.js` files (which is why they need to be rebuilt) but for PulseEffects this is different, since their files have no further changes! It's up to you...

## HOW TO BUILD THEM 🏗️

This is a manual process summarized in a few steps:

1. Add them in the following order: Equalizer > Reverberation > Delay > Limiter (reset each one if you've used them before).

<img src=https://user-images.githubusercontent.com/123143444/216802921-bbd53003-2f54-477f-8a96-534f4ea7b6fa.png>

2. Select Equalizer. Set `10` bands. Select a slope of `x4` and a quality of `5.00` for all. See the table below: You must set the frequency for each.

1|2|3|4|5|6|7|8|9|10
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz

3. Select Reverberation. Set the following values:

High Frequency Damping|Room Size|Diffusion|Pre Delay|Decay Time|Wet Level / Amount|Bass Cut|Treble Cut
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
3200 Hz|Large/smooth|0.00|25.00 ms|0.40 s|-6.0 dB|200 Hz|12800 Hz

4. Select Delay. Set `25.00 ms` to right.
5. Select Limiter. Set the following values:

EasyEffects:

Lookahead|Attack|Release|Auto Leveling|ALR Attack|ALR Release|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:
20.00 ms|10.00 ms|20.00 ms|Enable|10.00 ms|1000.00 ms|6.0 dB

PulseEffects:

Automatic Leveling|Automatic Smoothing Control (ASC)|Lookahead|Release
:---:|:---:|:---:|:---:
Enable|Enable|10.00 ms|1000.00 ms

6. Turn off Reverberation / Delay
7. Save this configuration as `custom`
8. Select Equalizer. See the following table: You must reduce the band gain. Save each setting according to its name. Load `custom` to start over.

Preset|25 Hz|50 Hz|100 Hz|200 Hz|400 Hz|800 Hz|1600 Hz|3200 Hz|6400 Hz|12800 Hz
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
acoustic 🥁|0.00|0.00|-12.00|-10.00|-8.00|-8.00|-10.00|-12.00|0.00|0.00
bass 🔊️|0.00|-2.00|-4.00|-6.00|-8.00|-10.00|-10.00|-10.00|-10.00|-10.00
classical 🎻️|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00|0.00
club 🍸|0.00|0.00|0.00|-10.00|-10.00|-10.00|-10.00|-10.00|0.00|0.00
custom 🎨|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00|0.00
hifi 💥️|0.00|0.00|0.00|-15.00|-10.00|-12.00|-10.00|-15.00|0.00|0.00
jazz 🎷️|0.00|0.00|-3.00|-6.00|-9.00|-12.00|0.00|0.00|0.00|0.00
laptop 💻️|-10.00|-10.00|-10.00|-10.00|-10.00|-10.00|-10.00|-10.00|0.00|0.00
latin 👠️|0.00|-3.00|-6.00|-9.00|-9.00|-9.00|-9.00|-6.00|-3.00|0.00
lofi 🍃️|0.00|0.00|-4.00|-8.00|-12.00|-12.00|-8.00|-4.00|0.00|0.00
podcast 🎙|0.00|-2.00|-4.00|-6.00|-8.00|-8.00|-6.00|-4.00|-2.00|0.00
pop 🎤️|-8.00|-4.00|0.00|-4.00|-8.00|-12.00|-8.00|-4.00|0.00|0.00
radio 📻️|-4.00|-8.00|-12.00|-8.00|-4.00|0.00|-4.00|-8.00|-12.00|-8.00
rock 🎸️|0.00|0.00|-3.00|-6.00|-9.00|-12.00|-9.00|-6.00|-3.00|0.00
vocal 👄️|-10.00|-10.00|-10.00|-10.00|-10.00|-8.00|-6.00|-4.00|-2.00|0.00
