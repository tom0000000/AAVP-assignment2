# AAVP-assignment2

This project uses openFrameworks, MaxMSP and Ableton Live to create an audio-visual performance, inspired by Carsten Nicolai/Alva Notos performances with visual artist Markus Heckmann. Ableton sends audio (via ASIO driver) and midi (via OSC) to openFrameworks which triggers certain scenes. There are several processes at play which generate the visuals. MIDI information triggers different envelopes which are sent to the alpha channel of different shaders, so they become visible when a certain sound is played. The MIDI is parsed to osc messages by a simple Max Patch.
![alt text](https://github.com/tom0000000/AAVP-assignment2/blob/master/maxpatch.JPG "screenshot")
As well as manipulating shaders, the sound also triggers a sequence of images and different functions using OSC.
