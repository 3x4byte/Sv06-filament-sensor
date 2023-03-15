# Forked Repository

forked from: [https://github.com/Sovol3d/Sv06-Source-Code](https://github.com/Sovol3d/Sv06-Source-Code)

# Changes

- added functionality for filament runout sensor
- changed version name to V1.9.2_A_modified

# Hot to Flash

1. download the **custom-firmware.bin**
2. get an empty sd-card *(maximum 16gb)* and format it to **FAT23**
3. put the **custom-firmware.bin** onto that sd-card
4. turn your SV06 off
5. plug in the sd-card
6. turn the SV06 on
7. wait until you see the satus screen
8. turn the SV06 off again
9. unplug the sd-card (and delete the **custom-firmware.bin** if you are using that sd-card for printing)

You can also download this repository, tweak some things to your needs and compile your own .bin file.

# How to connect the sensor

1. turn off your SV06
2. open the mainboard box (there is a screw on one side, facing away the printbed, which has to be removed first)
3. find the cable that is labeled **DET** (position is shown in the image below)
4. unplug that cable
5. plug your filament sensor into that connector
6. close the mainboard box

<img src=https://user-images.githubusercontent.com/105000853/225328203-bf1f0165-b582-4831-b124-b204d78fd254.png width="235" height="310"></img>

position of the connector (in my case the runout sensor is already connected, in your case there should be a black cable labeled **DET**)

# Enjoy your SV06 with a filement runour sensor!
