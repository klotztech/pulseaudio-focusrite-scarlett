# pulseaudio-focusrite-scarlett
This PulseAudio configuration provides remappings of the individual input channels (mono) to multiple stereo input devices, so that you can use mono input (e.g. an XLR microphone) in applications, that require you to pass a full input device (e.g. TeamSpeak or Discord).

This also fixes issues with applications expecting a stereo device but only getting a single channel, and therefore just muting the other (e.g. TeamSpeak with CELT Music codec).

The interesting bits where appended at the bottom of the ``default.pa`` file.

# Screenshot (pavucontrol)
![Configuration for the Scarlett 2i2 USB Interface](/.images/scarlett.png)

# Supported Devices
This configuration currently provides individual input channel mappings for the following devices:
- Focusrite Scarlett 2i2 USB (2nd Gen) `1235:8202`

# PulseAudio? 💪 Srsly?! 👊
Yes, I know. It's PulseAudio. Basically just cuz like every mildly user-friendly desktop Linux distro's got it installed out-of-the-box. Feel free to post an issue on how useless I am for not using JACK or at least ALSA ffs 🙃

# Contributing
Feel free to add similar channel remappings for more devices, just send me a PR 😃
