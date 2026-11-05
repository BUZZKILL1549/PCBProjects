# Standalone Hardware Music Player
## What this board does
A battery-powered player for local FLAC files. A PCM5102A DAC and a TPA6111A2 headphone amp drive a 3.5mm jack. One rotary encoder scrubs through the track and another sets the volume. A small display shows track info and buttons handle play/pause/next/prev. Tracks are selected through a webapp served from the ESP32-[variant]. 

## Why this board exists
I built an app-based music player to a decent level but then dropped it because firmware, embedded C and PCB design are what I would rather build. This is a dedicated player for my personal FLAC library, meant for IEMs.

## Design notes
- Both battery and USB-C powered
- Display: TFT preferred over OLED or LCD for full Unicode text (to be confirmed)
- MCU: ESP32-[variant] (variant is to be confirmed)

## Status
Schematic: in design
Layout: -
Placement: -
