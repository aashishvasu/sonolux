# Sonolux
The Sonolux project aims to send LED data over the network, which can then be read by any recipient device which is capable of handling UDP signals.

## Overview
This project aims to create a robust and scalable option for sending sound visualization data over a network to multiple devices. The idea is to send the data and use it in mainly LED projects although I'll try to keep the project more open-ended than that. To that effect, there is probably going to be another companion repo to this which will have client side code for arduino/rpi etc when I am able to get to it. Project built using [openFrameworks](https://openframeworks.cc/).

## TODO List

### v0.1
#### General

- [ ] Detect input audio devices and allow user to choose one
- [ ] Save/Load settings using ofxXmlSettings
- [ ] Add navigation buttons to set defaults, save settings, and proceed.
- [ ] Simple DSP

#### UI

- [ ] Fully navigable settings panel
- [ ] Fully navigable main screen panel
- [ ] Some sort of visual feedback for various visualization settings (graphs?)
- [ ] Visual representation of LEDs

#### Network
- [ ] Send UDP data over single broadcast port

### Future
#### General
- [ ] Backend support for multiple clients to connect
- [ ] More visualizations
- [ ] Better DSP

#### UI
- [ ] Smoother UI
- [ ] Better visualizations with dragging and dropping

#### Network
- [ ] Automatic UDP port switching
- [ ] Send different visualizations to different clients who are registered.
