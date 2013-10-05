Processing-Beat-Detection
=========================

This sketch combines uses a long term average, a short term average and the summation of the delta between those two to detect beats in music. An FFT splits apart the frequency bands, from that the desired band is isolated and processed. The short term average is compared to the  long term average, the the use of a threshold to detect beats. A multiplier is calculated based on the overall volume, and the summation of the delta between the two averages over a relatively long period of time. This adjusts for the different styles of music that require different thresholds.


Usage
=====

1) Ensure that the .pde file is enclosed in a folder of the same name

2) If you don't have Processing, you will need to install it

3) If you don't have Soundflower, install it. Sorry non-mac users, you will either have to use the built in microphone or figure out some higher quality input or Soundflower alternative. Once you have done that, set both computer audio input and output to 'Soundflower (2ch),' this is done through the 'Sound' menu on System Preferences. If you did it correctly, when you play some music you should not hear anything. Go into the Soundflower settings by opening Soundflower and setting the output to the correct system audio output, and you should be able to hear again.

4) You may or may not need to install some packages for the sketch to run, if so, look here

5) Run the sketch, assuming everything is working it should look a lot like the above video. Play your favorite songs through your computer and enjoy!