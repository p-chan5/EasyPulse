# HOW TO BUILD THEM

Up to date with [1.2.0](https://github.com/p-chan5/EasyPulse/releases/latest)

0. Reset each effect to its default values.

1. Add Crossfeed. Set the following values:

Enable
:---:
No

Cutoff|Feed
:---:|:---:
1864 Hz|6.0 dB

2. Add Loudness. Set the following values:

Enable
:---:
No

Output Volume
:---:
-24.0 dB

3. Add 1st Equalizer. Set the following values:

Enable
:---:
Yes

> classical 🎻️

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|392 Hz|-18.00 dB|0.00

> edm 🎹

Bands
:---:
2

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Low-Shelf|LRX (BT)|x1|138 Hz|12.00 dB|0.00
2|Low-Shelf|LRX (BT)|x1|4434 Hz|-12.00 dB|0.00

> hifi 💥️

Bands
:---:
2

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Low-Shelf|LRX (BT)|x1|138 Hz|18.00 dB|0.00
2|Low-Shelf|LRX (BT)|x1|4434 Hz|-18.00 dB|0.00

> kpop 🎤️

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|783 Hz|-12.00 dB|0.00

> lofi 🍃️

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|392 Hz|-12.00 dB|0.00

> rock 🎸️

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|783 Hz|-18.00 dB|0.00

4. Add Bass Enhancer. Set the following values:

Enable
:---:
No

Blend Harmonics|Amount|Harmonics|Scope|Floor
:---:|:---:|:---:|:---:|:---:
-10|-6.0 dB|10.0|233 Hz|Enable / 116 Hz

5. Add Filter. Set the following values:

Type|Mode|Slope|Frequency
:---:|:---:|:---:|:---:
High-Pass|LRX (BT)|x4|329

6. Add 2nd Equalizer. Set the following values:

Enable
:---:
No

Bands|Split Channels
:---:|:---:
1|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|932 Hz|6.00 dB|0.00|3.00 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|7458 Hz|6.00 dB|0.00|3.00 oct

7. Add 3rd Equalizer. Set the following values:

Enable
:---:
No

Bands|Split Channels
:---:|:---:
2|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|554 Hz|6.00 dB|0.00|1.50 oct
2|Ladder-Pass|LRX (BT)|x4|4434 Hz|6.00 dB|0.00|1.50 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|1567 Hz|6.00 dB|0.00|1.50 oct
2|Ladder-Pass|LRX (BT)|x4|12543 Hz|6.00 dB|0.00|1.50 oct

8. Add 4th Equalizer. Set the following values:

Enable
:---:
No

Bands|Split Channels
:---:|:---:
3|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|466 Hz|6.00 dB|0.00|1.00 oct
2|Ladder-Pass|LRX (BT)|x4|1864 Hz|6.00 dB|0.00|1.00 oct
3|Ladder-Pass|LRX (BT)|x4|7458 Hz|6.00 dB|0.00|1.00 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-Pass|LRX (BT)|x4|932 Hz|6.00 dB|0.00|1.00 oct
2|Ladder-Pass|LRX (BT)|x4|3729 Hz|6.00 dB|0.00|1.00 oct
3|Ladder-Pass|LRX (BT)|x4|14917 Hz|6.00 dB|0.00|1.00 oct

9. Add 2nd Multiband Compressor. Set the following values:

Enable
:---:
No

Stereo Split Mode
:---:
Enable

#|Enable|Band Start|Compression Mode|Band Bypass|Attack Time|Attack Threshold|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes|0 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
2|Yes|138 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
3|Yes|4434 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
4|No|||Enable||||
5|No|||Enable||||
6|No|||Enable||||
7|No|||Enable||||
8|No|||Enable||||

> Band Sidechain Options

#|Reactivity
:---:|:---:
1|250.00 ms
2|250.00 ms
3|250.00 ms

10. Add Compressor. Set the following values:

Enable
:---:
No

> Compressor

Mode|Attack Time|Attack Threshold|Release Time|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:
Upward|0.00 ms|0.0 dB|200.00 ms|1.50|0.0 dB

> Sidechain

Stereo Split Mode|Reactivity
:---:|:---:
Enable|250.00 ms

11. Add Reverberation. Set the following values:

Enable
:---:
No

High Frequency Damping|Room Size|Diffusion|Pre Delay|Decay Time|Wet Level|Bass Cut|Treble Cut
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
12543 Hz|Large/smooth|0.00|20.00 ms|0.40 s|-6.0 dB|196 Hz|12543 Hz

12. Add Stereo Tools. Set the following values:

Enable
:---:
No

> Stereo Matrix

Invert Phase (Right)
:---:
Enable

> Output

Delay L/R
:---:
20.00 ms

13. Add Autogain. Set the following values:

Enable
:---:
No

Target|Reference
:---:|:---:
-10.0 dB|Integrated

14. Add Limiter. Set the following values:

Enable
:---:
Yes

Stereo Link|Auto Leveling (ALR)|ALR Attack|ALR Release|Knee
:---:|:---:|:---:|:---:|:---:
0.00 %|Enable|0.10 ms|1000.00 ms|10.0 dB

15. Add Level Meter. Set the following values:

Enable
:---:
No

> indie 🍄️

3. Add 1st Multiband Compressor. Set the following values:

Enable
:---:
Yes

#|Enable|Band Start|Band Bypass|Attack Time|Attack Threshold|Release Time|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes|0 Hz|Enable|||||
2|Yes|116 Hz||0.00 ms|-48.0 dB|300.00 ms|2.00|0.0 dB
3|Yes|5274 Hz|Enable|||||
4|No||Enable|||||
5|No||Enable|||||
6|No||Enable|||||
7|No||Enable|||||
8|No||Enable|||||

> Band Sidechain Options

#|Reactivity
:---:|:---:
2|250.00 ms

9. Add 2nd Multiband Compressor. Set the following values:

Enable
:---:
No

Stereo Split Mode
:---:
Enable

#|Enable|Band Start|Compression Mode|Band Bypass|Attack Time|Attack Threshold|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes|0 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
2|Yes|116 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
3|Yes|5274 Hz|Upward||0.00 ms|0.0 dB|1.20|0.0 dB
4|No|||Enable||||
5|No|||Enable||||
6|No|||Enable||||
7|No|||Enable||||
8|No|||Enable||||

> Band Sidechain Options

#|Reactivity
:---:|:---:
1|250.00 ms
2|250.00 ms
3|250.00 ms

12. Add Delay. Set the following values:

Enable
:---:
No

Delay (Right)
:---:
20.00 ms

14. Add Maximizer. Set the following values:

Enable
:---:
Yes

Release
:---:
100.00 ms
