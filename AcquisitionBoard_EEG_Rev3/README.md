# EEG Acquisition Board Revision 3
## What this board does
This board takes EEG (electroencephalography) input from the user's scalp using electrodes and passes it into an ADS1299-4PAGR. Once the signals have been properly amplified and digitized, it is passed via SPI to an ESP32-S3. This ESP32-S3 will send the digital signal to a computer for further analysis.

## Why does this board exist
This board exists as a centerpiece for a project to produce a brain-controlled prosthetic hand. I have a working model that was made using EMG alone. In the future, I plan to combine EEG and EMG to produce a prosthesis that has fine control and excellent accuracy.

## What happened to the other revisions
Revisions 1 and 2 were made when I had much less knowledge on schematic capture, PCB layout, library management, good practices, placing testpoints, etc. Now, I have improved a lot as a developer so I am tackling this project again with the intention of making it smaller, safer, more accurate, and better overall.

Key targets:
- Board size of 50x30mm compared to 60x40mm of Rev2. 
- Proper placement of test points, mounting holes
- Proper utilization of ground planes and short return paths.

## Revision History
| Rev | Board | Changes / issues |
|:---:|:-----:|------------------|
| 1 | ~130×150 mm, 2-layer | • No real ground pours<br>• No impedance control on USB data traces<br>• No input protection on electrodes |
| 2 | ~60×40 mm, 4-layer | • No test points<br>• Wrong footprints on headers and some passives<br>• Decoupling caps far from pins |
| 3 | ~50×30 mm target, 4-layer | • Test points on key nets<br>• Footprints verified<br>• Two-sided placement for a smaller board<br>• Proper ground layers and stitching vias |
