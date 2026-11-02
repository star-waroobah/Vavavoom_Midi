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
<img width="981" height="805" alt="vavavoom_pcb" src="https://github.com/user-attachments/assets/e69e090c-fc9c-4ba4-88e8-52b6adc20b47" />

## 3D view
<img width="967" height="859" alt="Screenshot 2026-11-02 182628" src="https://github.com/user-attachments/assets/4beb2a65-b567-4571-a4c1-b7add3a25328" />


## Bill of Materials

| Designator | Footprint | Quantity | Value | Total Cost |
|------------|-----------|----------|-------|------------|
| D1, D2, D3 | LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount | 3 | SK6812MINI-E | $3.36 |
| J1 | Capacitive Keys | 1 | Capacitive Touch Buttons | |
| RV1, RV2 | Potentiometer_Bourns_PTA1543_Single_Slide | 2 | Slider | $3.16 |
| SW1, SW2, SW3 | Kailh Choc Low-Profile Switches | 3 | SW_Push | $6.04 |
| SW4 | RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | 1 | RotaryEncoder_Switch_MP | $1.44 |
| U1 | Waveshare ESP32-S3-Zero | 1 | Waveshare ESP32-S3-ZERO | $6.62 |

### Totals

| Vendor | Cost |
|--------|------|
| AliExpress | $19.59 |
| DigiKey | $12.35 |
| JLCPCB | $12.29 |
| **Total** | **$44.23** |
