# Tutorial 3 - USB Speaker Audio Output Control

This tutorial introduces USB audio output using the Raspberry Pi Zero 2 W.

The experiment shows how to connect a USB speaker to the Raspberry Pi, check whether the speaker is detected, list available playback devices, test basic audio output, generate audio tones using Python, visualize waveforms, and use simple fuzzy-style reasoning to select audio feedback.

## Main Contents

- Connecting a USB speaker to the Raspberry Pi using a USB OTG cable
- Checking the USB speaker using lsusb
- Checking playback devices using aplay -l
- Testing basic audio output using speaker-test
- Generating low, medium, and high audio tones in Python
- Playing WAV files through the USB speaker
- Visualizing generated audio waveforms
- Applying simple fuzzy-style audio feedback logic
- Optional extension for microphone recording

## Files Included

- Tutorial 3 - USB Speaker Audio Output Control.ipynb
- Tutorial 3 - USB Speaker Audio Output Control.html
- Tutorial 3 - USB Speaker Audio Output Control.pdf
- USB pictures/
- low_tone.wav
- medium_tone.wav
- high_tone.wav
- requirements.txt

## Requirements

The notebook uses NumPy, SciPy, and Matplotlib.

The Raspberry Pi also uses system audio tools such as lsusb, aplay, and speaker-test.

## Note

The USB speaker may appear as Jieli Technology UACDemoV1.0.

In this setup, the playback device is usually plughw:1,0.

Therefore, playback commands in the notebook use aplay with the plughw:1,0 device.
