# Tutorial 4 - STEMMA Speaker, I2S Microphone and Raspberry Pi

This tutorial introduces audio sensing and audio feedback using the Raspberry Pi, an I2S microphone, and a STEMMA speaker.

The experiment shows how to record sound using the I2S microphone, play audio through the STEMMA speaker, visualize the recorded waveform, extract simple audio features, and apply fuzzy-style interpretation to produce meaningful audio feedback.

## Main Contents

- Connecting the I2S microphone and STEMMA speaker to the Raspberry Pi
- Configuring Raspberry Pi audio input and output
- Recording audio using arecord
- Playing audio using aplay
- Reading WAV files in Python
- Visualizing recorded audio waveforms
- Extracting simple audio features such as loudness, activity, and impulsiveness
- Applying fuzzy-style interpretation to audio data
- Producing STEMMA speaker feedback based on the fuzzy result

## Files Included

- Tutorial 4 - STEMMA Speaker, I2S Microphone and PI.ipynb
- Tutorial 4 - STEMMA Speaker, I2S Microphone and PI.html
- Tutorial 4 - STEMMA Speaker, I2S Microphone and PI.pdf
- Stemma Pictures/
- week4_mic_test.wav
- week4_mic_test_loud.wav
- requirements.txt

## Requirements

The notebook uses NumPy, Matplotlib, and gpiozero.

The Raspberry Pi also uses system audio tools such as arecord, aplay, and speaker-test.

## Note

This tutorial combines audio sensing, signal playback, signal processing, fuzzy-style interpretation, and physical feedback in one integrated Raspberry Pi experiment.
