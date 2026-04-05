# HOW TO BUILD THEM 🏗️

To set decimal values (Hz) ​​open and edit the `.json` file or set them in the plugin GUI.

0. Reset each effect to its default values.

1. Add Crossfeed. Set the following values:

Toggle this effect
:---:
Off

Cutoff|Feed
:---:|:---:
1760.00 Hz|6.0 dB

2. Add 1st Equalizer. Set the following values:

> classical

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|392.00 Hz|-18.00 dB|0.00

> edm

Bands
:---:
2

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Low-shelf|LRX (BT)|x1|138.59 Hz|12.00 dB|0.00
2|Low-shelf|LRX (BT)|x1|4434.92 Hz|-12.00 dB|0.00

> hifi

Bands
:---:
2

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Low-shelf|LRX (BT)|x1|138.59 Hz|18.00 dB|0.00
2|Low-shelf|LRX (BT)|x1|4434.92 Hz|-18.00 dB|0.00

> kpop

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|783.99 Hz|-12.00 dB|0.00

> lofi

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|392.00 Hz|-12.00 dB|0.00

> rock

Bands
:---:
1

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (BT)|x1|783.99 Hz|-18.00 dB|0.00

3. Add Bass Enhancer. Set the following values:

Toggle this effect
:---:
Off

Blend harmonics|Amount|Harmonics|Scope|Floor active|Floor
:---:|:---:|:---:|:---:|:---:|:---:
-10|-6.0 dB|10.0|233.08 Hz|On|116.54 Hz

4. Add Filter. Set the following values:

Toggle this effect
:---:
Off

Type|Filter mode|Slope|Frequency
:---:|:---:|:---:|:---:
High-pass|LRX (BT)|x4|329.63 Hz

5. Add 2nd Equalizer. Set the following values:

Toggle this effect
:---:
Off

Bands|Split channels
:---:|:---:
1|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|932.33 Hz|6.00 dB|0.00|3.00 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|7458.62 Hz|6.00 dB|0.00|3.00 oct

6. Add 3rd Equalizer. Set the following values:

Toggle this effect
:---:
Off

Bands|Split channels
:---:|:---:
2|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|554.37 Hz|6.00 dB|0.00|1.50 oct
2|Ladder-pass|LRX (BT)|x4|4434.92 Hz|6.00 dB|0.00|1.50 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|1567.98 Hz|6.00 dB|0.00|1.50 oct
2|Ladder-pass|LRX (BT)|x4|12543.85 Hz|6.00 dB|0.00|1.50 oct

7. Add 4th Equalizer. Set the following values:

Toggle this effect
:---:
Off

Bands|Split channels
:---:|:---:
3|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|466.16 Hz|6.00 dB|0.00|1.00 oct
2|Ladder-pass|LRX (BT)|x4|1864.66 Hz|6.00 dB|0.00|1.00 oct
3|Ladder-pass|LRX (BT)|x4|7458.62 Hz|6.00 dB|0.00|1.00 oct

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality|Width
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Ladder-pass|LRX (BT)|x4|932.33 Hz|6.00 dB|0.00|1.00 oct
2|Ladder-pass|LRX (BT)|x4|3729.31 Hz|6.00 dB|0.00|1.00 oct
3|Ladder-pass|LRX (BT)|x4|14917.24 Hz|6.00 dB|0.00|1.00 oct

8. Add 2nd Multiband Compressor. Set the following values:

Toggle this effect
:---:
Off

Stereo split
:---:
Enable

Band|Enable|Start|Compression mode|Bypass|Attack Time|Attack Threshold|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes||Upward||0.00 ms|0.00 dB|1.2|0.0 dB
2|Yes|138.59 Hz|Upward||0.00 ms|0.00 dB|1.2|0.0 dB
3|Yes|4434.92 Hz|Upward||0.00 ms|0.00 dB|1.2|0.0 dB
4|No|||Enable||||
5|No|||Enable||||
6|No|||Enable||||
7|No|||Enable||||
8|No|||Enable||||

> indie

Band|Release Time
:---:|:---:
1|0.00 ms
2|0.00 ms
3|0.00 ms

> Band # - Sidechain

#|Reactivity
:---:|:---:
1|250.0 ms
2|250.0 ms
3|250.0 ms

9. Add Compressor. Set the following values:

Toggle this effect
:---:
Off

Stereo split
:---:
Enable

Mode|Ratio|Knee|Attack Threshold|Attack Time|Release Time|Sidechain Mode|Reactivity
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
Upward|1.5|0.00 dB|0.0 dB|0.00 ms|200.00 ms|RMS|250.00 ms

> indie

Release Time
:---:
0.00 ms

10. Add Reverberation. Set the following values:

Toggle this effect
:---:
Off

Room size|Decay time|Pre delay|Diffusion|High frequency damping|Bass cut|Treble cut|Wet
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
Large/smooth|0.40 s|20 ms|0.00 %|12543.85 Hz|196.00 Hz|12543.85 Hz|-6.0 dB

11. Add Stereo Tools. Set the following values:

Toggle this effect
:---:
Off

Delay
:---:
20.00 ms

12. Add Autogain. Set the following values:

Toggle this effect
:---:
Off

Target
:---:
-10.00 dB

13. Add Limiter. Set the following values:

Automatic level
:---:
Enable

Stereo Link|Al Attack|Al Release|Knee|Smooth
:---:|:---:|:---:|:---:|:---:
0.0 %|0.10 ms|1000.0 ms|12.00 dB|0.00 dB

> indie

2. Add 1st Multiband Compressor. Set the following values:

Band|Enable|Start|Bypass|Attack Time|Attack Threshold|Release Time|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes||Enable|||||
2|Yes|138.59 Hz||0.00 ms|-60.00 dB|0.00 ms|1.5|0.0 dB
3|Yes|4434.92 Hz|Enable|||||
4|No||Enable|||||
5|No||Enable|||||
6|No||Enable|||||
7|No||Enable|||||
8|No||Enable|||||

> Band # - Sidechain

#|Reactivity
:---:|:---:
2|250.0 ms

> analog

1. Add 1st Multiband Compressor. Set the following values:

Operating mode
:---:
Linear phase

Band|Enable|Start|Bypass|Attack Time|Attack Threshold|Release Time|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes||Enable|||||
2|Yes|116.54 Hz||0.00 ms|-60.00 dB|0.00 ms|1.5|0.0 dB
3|Yes|5274.04 Hz|Enable|||||
4|No||Enable|||||
5|No||Enable|||||
6|No||Enable|||||
7|No||Enable|||||
8|No||Enable|||||

> Band # - Sidechain

#|Reactivity|Lookahead
:---:|:---:|:---:
2|250.0 ms|20.0 ms

2. Add 1st Equalizer. Set the following values:

Toggle this effect
:---:
Off

Mode|Bands|Split channels
:---:|:---:|:---:
SPM|5|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (MT)|x1|466.16 Hz|3.00 dB|1.25
2|Bell|RLC (MT)|x1|932.33 Hz|-0.50 dB|1.00
3|Bell|RLC (MT)|x1|1864.66 Hz|3.00 dB|1.25
4|Bell|RLC (MT)|x1|3729.31 Hz|-0.50 dB|1.00
5|Bell|RLC (MT)|x1|7458.62 Hz|3.00 dB|1.25

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (MT)|x1|932.33 Hz|3.00 dB|1.25
2|Bell|RLC (MT)|x1|1864.66 Hz|-0.50 dB|1.00
3|Bell|RLC (MT)|x1|3729.31 Hz|3.00 dB|1.25
4|Bell|RLC (MT)|x1|7458.62 Hz|-0.50 dB|1.00
5|Bell|RLC (MT)|x1|14917.24 Hz|3.00 dB|1.25

3. Add 2nd Equalizer. Set the following values:

Toggle this effect
:---:
Off

Mode|Bands|Split channels
:---:|:---:|:---:
SPM|5|Enable

> Left

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (MT)|x1|466.16 Hz|6.00 dB|1.50
2|Bell|RLC (MT)|x1|932.33 Hz|-1.00 dB|1.00
3|Bell|RLC (MT)|x1|1864.66 Hz|6.00 dB|1.50
4|Bell|RLC (MT)|x1|3729.31 Hz|-1.00 dB|1.00
5|Bell|RLC (MT)|x1|7458.62 Hz|6.00 dB|1.50

> Right

#|Type|Mode|Slope|Frequency|Gain|Quality
:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Bell|RLC (MT)|x1|932.33 Hz|6.00 dB|1.50
2|Bell|RLC (MT)|x1|1864.66 Hz|-1.00 dB|1.00
3|Bell|RLC (MT)|x1|3729.31 Hz|6.00 dB|1.50
4|Bell|RLC (MT)|x1|7458.62 Hz|-1.00 dB|1.00
5|Bell|RLC (MT)|x1|14917.24 Hz|6.00 dB|1.50

4. Add 2nd Multiband Compressor. Set the following values:

Toggle this effect
:---:
Off

Stereo split
:---:
Enable

Band|Enable|Start|Compression mode|Bypass|Attack Time|Attack Threshold|Release Time|Ratio|Knee
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
1|Yes||Upward||0.00 ms|0.00 dB|0.00 ms|1.2|0.0 dB
2|Yes|116.54 Hz|Upward||0.00 ms|0.00 dB|0.00 ms|1.2|0.0 dB
3|Yes|5274.04 Hz|Upward||0.00 ms|0.00 dB|0.00 ms|1.2|0.0 dB
4|No|||Enable|||||
5|No|||Enable|||||
6|No|||Enable|||||
7|No|||Enable|||||
8|No|||Enable|||||

> Band # - Sidechain

#|Reactivity|Lookahead
:---:|:---:|:---:
1|250.0 ms|20.0 ms
2|250.0 ms|20.0 ms
3|250.0 ms|20.0 ms

## HIGHER QUALITY = HIGHER LATENCY 💎️

You can get more quality in exchange for notable latency. Just follow the steps below:

1. Select 1st / 2nd / 3rd / 4th Equalizer. Set the following values:

X|Mode
:---:|:---:
Equalizer|SPM
Filter|(MT)

2. Select Filter. Set the following values:

Filter mode|Equalizer mode
:---:|:---:
LRX (MT)|SPM

3. Select 1st / 2nd Multiband Compressor. Set the following values:

Operating mode
:---:
Linear phase

> Band # - Sidechain

#|Lookahead
:---:|:---:
X|20.0 ms

4. Select Compressor. Set the following values:

Lookahead
:---:
20.000 ms

5. Select Limiter. Set the following values:

Limiter Attack|Limiter Release|Lookahead
:---:|:---:|:---:
20.00 ms|20.00 ms|20.00 ms

## ALTERNATIVES 🫧️

You can replace some effects by using a variant.

11. Add Delay. Set the following values:

Toggle this effect
:---:
Off

Time (Right)
:---:
20.00 ms

13. Add Maximizer. Set the following values:

Release
:---:
100.00 ms
