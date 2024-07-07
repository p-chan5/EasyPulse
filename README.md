A set of `High Quality` presets for [Easy Effects](https://github.com/wwmm/easyeffects).

## WHAT'S INSIDE 🎁

7 configuration profiles:

- classical 🎻️
- edm 🎹
- hifi 💥️
- indie 🍄
- kpop 🎤️
- lofi 🍃️
- rock 🎸️

Do they sound amazing? Then support us with a ⭐️ and a follow!

## INSTALLATION 🚀️

1. Download the [latest release](https://github.com/p-chan5/EasyPulse/releases/latest) as `zip / tar.gz` or read [HOW TO BUILD THEM](https://github.com/p-chan5/EasyPulse/blob/main/HOW_TO_BUILD_THEM.md).
2. Unzip and move the `.json` files to one of the following paths:
  
* Flatpak: `~/.var/app/com.github.wwmm.easyeffects/config/easyeffects/output`
* Repositories: `~/.config/easyeffects/output`

3. Ready! Load them from `Presets` > `Output`

## EFFECTS 🎛️

### CROSSFEED 🎧

Centers the signal via `Feed` | `Cutoff` sets the limit of frequencies it affects.

### LOUDNESS 📢️

Applies volume corrections giving more prominence to the bass. Use it with `Autogain`

### 1ST EQUALIZER | MULTIBAND COMPRESSOR 🎲

They attenuate the input signal, giving space to the mix.

### BASS ENHANCER 💪

It makes it sound crunchier.

### FILTER 🚿️

Applies a `High-Pass` filter that eliminates bass. Switch to `Low-Pass` to do the opposite.

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

### AUTOGAIN 🛠

Normalizes the volume based on a `Target` | `Reset History` re-evaluates this operation (refresh) | `Maximum History` is arbitrary.

### LIMITER | MAXIMIZER 👂️

They prevent the signal from exceeding 0 dB and becoming distorted | `Threshold` can replace `Autogain` in exchange for messing up dynamics.

### LEVEL METER 🔊️

Helps to find the true perceived loudness of the signal.

## TIPS ✨

### HIGHER QUALITY, HIGHER LATENCY 💎️

You can get more quality in exchange for notable latency. Just follow the steps below:

1. Select Loudness. Set the following values:

FFT Size
:---:
16384

2. Select 1st / 2nd / 3rd / 4th Equalizer. Set the following values:

X|Mode
:---:|:---:
Equalizer|SPM
Filter|(MT)

3. Select Filter. Set the following values:

Mode|Equalizer Mode
:---:|:---:
LRX (MT)|SPM

4. Select 1st / 2nd Multiband Compressor. Set the following values:

Operating Mode
:---:
Linear Phase

> Band Sidechain Options

#|Lookahead
:---:|:---:
X|20.00 ms

5. Select Compressor. Set the following values:

> Sidechain

Lookahead
:---:
20.00 ms

6. Select Limiter. Set the following values:

Mode|Lookahead|Attack|Release
:---:|:---:|:---:|:---:
Herm Wide|20.00 ms|20.00 ms|20.00 ms

### ON OR OFF 🤔

Some effects are disabled by default, be sure to turn them on and try them out. If you liked it, save it by rewriting the original file.

### DOWNWARD / UPWARD COMPRESSION 📈

To achieve different styles, you can set the `Release Time` to 0.00, 100.00, 200.00, 300.00, 400.00 or 500.00 ms, the `Ratio` to 1.20:1, 1.50:1, 2.00:1, 3.00:1 or 6.00:1 and the `Reactivity` to 10.00 or 250.00 ms

## COMPATIBILITY ISSUES ⚠️

Since we **DO NOT** support old versions, it is vital that you have the current stable branch for them to work.

## HELP LINKS 🔗

### Crossfeed

- [Bauer stereophonic-to-binaural DSP](https://bs2b.sourceforge.net/)

### Loudness

- [LSP Loudness Compensator Stereo](https://lsp-plug.in/?page=manuals&section=loud_comp_stereo)

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
