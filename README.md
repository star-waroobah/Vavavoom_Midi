# Vavavoom: Custom USB-C MIDI Keypad

[![View PCB on KiCanvas](https://hack.club/pcb-badge)](https://kicanvas.org/?repo=https://github.com/star-waroobah/Vavavoom_Midi)

Vavavoom is a custom-designed USB-C MIDI keypad built for interactive music creation and Digital Audio Workstation (DAW) control. Designed entirely in KiCad, it puts music production hardware right at your fingertips using mechanical switches, a rotary encoder, and a custom capacitive touch strip. I made it as my Half-Life Week 3 project, to learn more about KiCad PCB design and to try out a capacitive touch strip.

## Features

* **Microcontroller:** Powered by the Waveshare ESP32-S3-Zero, which handles USB connectivity and processes user inputs.
* **Mechanical Switches:** 3 Kailh Choc mechanical switches for triggering notes or shortcuts.
* **Rotary Encoder:** An Alps EC11 encoder used for volume control, scrolling, or parameter adjustments.
* **Capacitive Touch Strip:** A custom 7-pad touch interface connected to the ESP32's touch pins to act as a pitch bend or mini touch keyboard.

## Schematic
<img width="1258" height="850" alt="vavavoom_schematic" src="https://github.com/user-attachments/assets/0b4b344a-a6a7-40ce-91fd-0e0031dfb58e" />

## PCB
![Component placement](<Screenshot (476).png>)<img width="981" height="805" alt="vavavoom_pcb" src="https://github.com/user-attachments/assets/e69e090c-fc9c-4ba4-88e8-52b6adc20b47" />

## 3D view
![Component placement](<Screenshot (475).png>)

## Bill of Materials
See [bom.csv](bom.csv)
