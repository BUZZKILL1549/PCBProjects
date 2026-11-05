# FM Radio V1
## What this board does
A USB-C powered FM reciever. An Si4732-A10-GS tunes the station, an ESP32-S3-WROOM-1-N16R8 controls it, and a TPA2005D1DGNR Class-D amplifier drives a speaker. A headphone jack feeds the same amp through a 2x680R mixer, and a Bourns rotary encoder controls the tuning and volume. The ESP32-S3 also serves as the radio's UI and webapp.

## Why this board exists
There were many reasons for making a board such as this:
- Primarily, I just really like radios and I hate that we have less of them nowadays, so I figured, why not build one?
- On another note, radios require learning proper RF radio design and RF is something I have no experience in.

## Design notes
- FM only, no AM
- First spin is USB only. The battery connector will be left DNP.

## Status
- Schematic: final verification in progress
- Layout: -
- Routing: -
