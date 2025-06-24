# The Groove Window (Embedded Audio Mixer)

**The Groove Window** is an all-in-one embedded audio controller designed for beginner composers. Built on an STM32 Microcontroller, it enables real-time musical input and control through a velocity-sensitive keyboard, drum pads, equalization knobs, and USB MIDI communication to a software DAW (Digital Audio Workstation).

---

## Project Overview

This repo is a showcase of project architecture, hardware design, software integration, and media demos.

### Key Features:
- 12-key velocity-sensitive piano interface with octave shifting
- 4 responsive drum pads
- 3 equalization knobs for real-time audio manipulation
- USB MIDI integration with Digital Audio Workstation
- Real-time embedded firmware on STM32 Microcontroller using C

---

## System Diagrams

### Block Diagram
<img src="diagrams/block_diagram.png" width="60%">

### Firmware Flow (Embedded)
<img src="diagrams/embedded.png" width="65%">

---

## Hardware Photos

### Bird’s Eye View
<img src="images/birdseye1.png" width="50%">
<img src="images/birdseye2.JPG" width="50%">

### Internal Layout
<img src="images/inside1.png" width="60%">

### Sensor and Encoder Hardware
#### Hall-Effect Sensor
<img src="images/hall_effect_sensors.png" width="60%">

#### Rotary Encoders
<img src="images/rotary_encoders.png" width="60%">

### USB Connectivity
<img src="images/micro_to_usb.png" width="60%">

---

## Software Snapshots

### Digital Audio Workstation
<img src="images/software1.png" width="85%">
<img src="images/software2.png" width="85%">


---

## Demo Videos

### Piano Input
[piano.mov](demo/piano.mp4)

### Drum Pads
[drum.mov](demo/drum.mp4)

### Equalizer Control
[equalizer.mov](demo/equalizer.mp4)

> You can download or preview these `.mp4` files depending on your browser or GitHub client.
