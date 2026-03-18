A set of `High Quality` presets for [Easy Effects](https://github.com/wwmm/easyeffects).

## WHAT'S INSIDE 🎁

15 configuration files divided into two categories:

Classic: with `min` and `max` latency versions.

- classical
- edm
- hifi
- indie
- kpop
- lofi
- rock

Special: they don't have many effects, but they do have some interesting features.

- analog: includes 2 vintage surround equalizers.

Do they sound amazing? Then support us with a ⭐️ and a follow!

## INSTALLATION 🚀️

1. Download the [latest release](https://github.com/p-chan5/EasyPulse/releases/latest) as `zip / tar.gz` or read [HOW TO BUILD THEM](https://github.com/p-chan5/EasyPulse/blob/main/HOW_TO_BUILD_THEM.md).
2. Unzip and move the `.json` files to one of the following paths:
  
* Flatpak: `~/.var/app/com.github.wwmm.easyeffects/data/easyeffects/output`
* Repositories: `~/.local/share/easyeffects/output`

3. Ready! Load them from `Output` > `Presets` > `Local`

## EFFECTS 🎛️

### CROSSFEED 🎧

Centers the signal via `Feed` | `Cutoff` sets the limit of frequencies it affects.

### 1ST EQUALIZER | MULTIBAND COMPRESSOR 🎲

They attenuate the input signal, giving space to the mix.

### BASS ENHANCER 💪

It makes it sound crunchier.

### FILTER 🚿️

Applies a `High-pass` filter that eliminates bass. Switch to `Low-pass` to do the opposite.

### 2ND / 3RD / 4TH EQUALIZER 🧬

They expand the signal recreating a simple / smooth / harsh `Dolby Atmos`

### 2ND MULTIBAND COMPRESSOR ❤️‍🔥

Increases the dynamic range of bass, midrange and treble.

### COMPRESSOR 🔥️

Increases the dynamic range of the signal making it sound fuller.

### REVERBERATION ⛰️

Creates a bedroom. Try going beyond these values, you can achieve creative results with some practice.

### DELAY | STEREO TOOLS 👥️

They create a stereo separation effect.

### AUTOGAIN 🛠️

Normalizes the volume based on a `Target` | `Reset history` re-evaluates this operation (refresh) | `Maximum history` is arbitrary.

### LIMITER | MAXIMIZER 👂️

They prevent the signal from exceeding 0 dB and becoming distorted | `Threshold` can replace `Autogain` in exchange for messing up dynamics.

## TIPS ✨

### BASS TREATMENT 🩺

It's hard to find a perfect setup for every user, although it is possible to make some adjustments to customize its behavior:

1. Load `hifi` or `edm` > Open the 1st Equalizer band 1 options > Change the `Frequency` and/or reduce the `Gain` and/or change the `Mode` to BWC (BT)/(MT) as appropriate.

2. Select Bass Enhancer > Set the `Amount` to -6, -3 or 0 dB and/or the `Floor` to 29, 58 or 116 Hz

3. Select 1st/2nd Multiband Compressor and edit Band 1 options (Bypass/Compression mode/Attack Threshold/Ratio) and/or Band 2 Frequency (Start).

### DOWNWARD / UPWARD COMPRESSION 📈

To achieve different styles, you can set the `Release Time` to 0.00, 100.00, 200.00, 300.00, 400.00 or 500.00 ms, the `Ratio` to 1.20:1, 1.50:1, 2.00:1, 3.00:1 or 6.00:1 and the `Reactivity` to 10.00, 25.00, 50.00, 125.00 or 250.00 ms

### DYNAMICS LOSS 🦴️

It should not be noticeable unless the Limiter signal is oversaturated, but if that is the case, select the `Smooth` parameter and set a value between 0 dB and -48 dB and/or reduce the `Knee` or the `Input` level.

### MIN VS MAX LATENCY 🥊️

Choose the one that best suits your needs. From a practical standpoint, the `min` version is stable and works in all possible scenarios, while the `max` version requires more processing and is experimental, but may sound more professional.

### NATIVE PLUGIN WINDOW 🔬️

You can show or hide the native plugins interface to see the applied settings in more detail. Go to `Preferences` > `Experimental Features` and enable `Native window of effects`

### ON OR OFF 🤔

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save it by rewriting the original file.

## COMPATIBILITY ISSUES ⚠️

Since we **DO NOT** support old versions, it is vital that you have the current stable branch for them to work. In any case, see: [Easy Effects Changelog](https://wwmm.github.io/easyeffects/community/CHANGELOG.html).

## HELP LINKS 🔗

### App Manual

- [Easy Effects Manual](https://wwmm.github.io/easyeffects/)

### Crossfeed

- [Bauer stereophonic-to-binaural DSP](https://bs2b.sourceforge.net/)

### Equalizer

- [LSP Parametric Equalizer x32 LeftRight](https://lsp-plug.in/?page=manuals&section=para_equalizer_x32_lr)

### Bass Enhancer

- [Calf Bass Enhancer](https://calf-studio-gear.org/doc/Bass%20Enhancer.html)

### Filter

- [LSP Filter Stereo](https://lsp-plug.in/?page=manuals&section=filter_stereo)

### Multiband Compressor

- [LSP Sidechain Multiband Compressor Stereo x8](https://lsp-plug.in/?page=manuals&section=sc_mb_compressor_stereo)

### Compressor

- [LSP Sidechain Compressor Stereo](https://lsp-plug.in/?page=manuals&section=sc_compressor_stereo)

### Reverberation

- [Calf Reverb](https://calf-studio-gear.org/doc/Reverb.html)

### Delay

- [LSP Delay Compensator x2 Stereo](https://lsp-plug.in/?page=manuals&section=comp_delay_x2_stereo)

### Stereo Tools

- [Calf Stereo Tools](https://calf-studio-gear.org/doc/Stereo%20Tools.html)

### Limiter

- [LSP Sidechain Limiter Stereo](https://lsp-plug.in/?page=manuals&section=sc_limiter_stereo)

### Maximizer

- [zam-plugins](https://www.zamaudio.com/?p=976)
