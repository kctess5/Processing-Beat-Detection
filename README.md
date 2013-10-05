Processing-Beat-Detection
=========================

This sketch combines uses a long term average, a short term average and the summation of the delta between those two to detect beats in music. An FFT splits apart the frequency bands, from that the desired band is isolated and processed. The short term average is compared to the  long term average, the the use of a threshold to detect beats. A multiplier is calculated based on the overall volume, and the summation of the delta between the two averages over a relatively long period of time. This adjusts for the different styles of music that require different thresholds.
