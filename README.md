# Raspberry-Pi-Audio-DAC-Cases

<p align="left">
<img src="images/case1.jpg" width="285" />  
<img src="images/case3.jpg" width="300" />   
</p>

Two fan-cooled Raspberry Pi 4B cases with two different audio DAC hats, had been 3d-printed. The cases, fan covers, and honeycomb mesh patterns, are sourced from:

[**Fan Grill Covers**](https://www.thingiverse.com/thing:2802474) - Creative Commons - Attribution - Non-Commercial - Share Alike license.

[**Honeycomb mesh**](https://www.thingiverse.com/thing:1701435) - GNU - GPL license and CC.

[**Raspberry Pi 4 Case**](https://www.thingiverse.com/thing:4859828) - [**also here**](model/Case.stl) - Creative Commons with Attribution license.

The RPi4 case above had been modified [**1**](model/Case1.stl) and [**2**](model/BlankCase.stl) and [**3**](model/BlankCase2.stl), so that (allmost) any DAC hat can be fitted. This was used, after drilling the three extra holes, for the second PCM5122 DAC. The first DAC case housed the ESS DAC without any modifications. Additional openings had also been added and the top covers modified.

The [**PCM5122 PiFi DAC+**](https://www.seeedstudio.com/Raspberry-pi-B-2B-HIFI-DAC-p-2801.html) is an inexpensive substitute for the HiFi Berry Pi DAC+ Hat and can be configured in exactly the same way - replace the line dtparam=audio=on from /boot/config.txt if with dtoverlay=hifiberry-dacplus.

The other DAC is an [**ESS ES9023**](http://www.suptronics.com/miniPCkits/x900.html) Sabre 24-bit/192kHz DAC and is configured by replacing the line dtparam=audio=on from /boot/config.txt if with dtoverlay=hifiberry-dac. 

The two audio DAC hats are also used [**here**](https://github.com/TobiasVanDyk/Teensy4-USB-Audio-DAC-and-Volume-Control) and  [**here**](https://github.com/TobiasVanDyk/Raspberry-Pi-PC-PSU-Desktop-Computer-with-a-Hard-Disk-Drive-and-Fan-and-Switch/edit/master/Readme.md) (at the very bottom).

All the modelling variations/customisation were made using [**OpenSCAD**](https://openscad.org/) and [**TinkerCAD**](https://www.tinkercad.com/).

The cases were printed using PLA (with no post-print finishing) using a [**Creality CR-20 Pro 3D-printer**](https://www.creality3dofficial.com/products/creality-cr-20-pro-3d-printer) <img src="images/CR-20 Pro - Unboxing and Printing Test.jpg" width="16" height="16"/>

The two DAC's were tested using a classic 1970's discrete transistor op-amp design:<br>
[**1976 November Wireless World An Advanced Preamplifier by Douglas Self**](DougSelf1976Preamp) <img src="DougSelf1976Preamp/DSelfPreamp.jpg" width="16" height="16"/> <img src="DougSelf1976Preamp/DSelfPreamp1.jpg" width="16" height="16"/><img src="DougSelf1976Preamp/pcb-layouts.jpg" width="16" height="16"/><br>

<p align="left">
<img src="images/case2.jpg" width="260" />  
<img src="images/case4.jpg" width="180" />  
<img src="images/case5.jpg" width="235" />  
</p>

<p align="left">
<img src="images/pcm5122.jpg" width="300" />  
<img src="images/x900.jpg" width="300" />    
</p>

