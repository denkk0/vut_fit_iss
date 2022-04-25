# ISS

Author: Denis Kramár (xkrama06@vutbr.cz)

This projects is a showcase of how to load .wav file using python, how to split the audio file into frames with overlapping, calculate Discrete Fourier Transformation of the frames, visualise frame using spectrogram, find disruptive frequencies and how to remove them from given audio file.

The input audio sample `xkrama06.wav` comes from TIMIT database, which has been modified to contain disruptive frequencies. Generated audio files are `4cos.wav` which is an audio sample of only the disruptive frequencies, and `clean_bandstop.wav` is an filtered version of the input audio.
