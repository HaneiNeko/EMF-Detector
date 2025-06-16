[![Made with](https://img.shields.io/badge/arduino-00878F.svg?style=for-the-badge&logo=arduino)](https://www.arduino.cc)
[![Made with](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=cplusplus)](https://isocpp.org/)
[![Made with](https://img.shields.io/badge/FreeCad-418FDE.svg?style=for-the-badge&logo=freecad)](https://www.freecad.org/)
[![Made with](https://img.shields.io/badge/PlatformIO-F5822A.svg?style=for-the-badge&logo=platformio)](https://platformio.org/)

# EMF Detector

Original project : https://www.instructables.com/Attiny85-EMF-detector/

## What is an EMF detector ?
An EMF detector is a device used to measure the presence and intensity of electromagnetic fields in a particular area.

Using in the ghosts detection 👻, this device is very famous.

## How does it work ?
An antena detect a electromagnetic fields, and depending on the electromagnetic field's force, a led will be turn on, and make a noise.

## This project
This project is an EMF detector using the Arduino framework.

## Content
```
EMF-Detector
├── README.md
├── schematics/
│   ├── libs/
│   │   └── ATTINY85-20PU/
│   │       ├── ATTINY85-20PU.kicad_sym
│   │       ├── ATTINY85-20PU.pretty/
│   │       │   └── DIP762W46P254L927H533Q8B.kicad_mod
│   │       └── ATTINY85-20PU.step
│   ├── Emf_detector.kicad_sch
│   └── Emf_detector.kicad_pcb
├── code/
│   └── emf_detector.ino
└── src/
    └── images/
        ├── schematic.png
        └── final.png
```

## Usage
1. Use the schematic for create the PCB
2. Push the code into the microcontroller
3. Print the case (optional)
4. Enjoy ! 👻😉