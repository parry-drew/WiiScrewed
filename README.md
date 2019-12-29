# WiiScrewed - Archive

This Pure Data patch uses OSC communications with a Wiimote to perform chopped and screwed tracks.

Note: The software Darwiin Remote OSC is used to convert the IR information from the WiiMote to Pure Data via OSC. However it appears that  it does not work OSX beyond version 10.4.  

## Dependencies:
1. Soundtouch
 http://www.katjaas.nl/pitchshift/soundtouch~.html

2. Darwiin Remote OSC
https://code.google.com/p/darwiinosc/downloads/detail?name=darwiinremoteOSC_0.3.2_pre.zip&can=2&q=

3. Candles with big wicks (optional).

## Directions:
1. Make sure your computers bluetooth is on and discoverable.
2. Open Darwiin Remote OSC and discover your WiiRemote. Follow prompts.
3. Open WiiScrewed_IR.pd and use the patch to control sample pitch, delay between samples, and cross fade between samples.
