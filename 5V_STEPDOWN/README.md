# 5V Stepdown
## What this project does
This is a PCB that takes 5V input from a USB-C and splits it into 3 seperate rails (5V/3.3V/1.8V).
It uses the AP2112K-3.3V and AP2112K-1.8V ICs to convert the 5V input into 3.3V and 1.8V outputs respectively.
It provides approximately 600mA in current post conversion for the 3.3V and 1.8V rails.

The main reason to go with the AP2112K series over an IC with a bigger current output was to make the footprint as small as i could. Currently, the board is a simple 2-layer board being only 40mmx20mm. Outputs are taken using 2.54mm pitch pinheaders.
