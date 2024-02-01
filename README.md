# ObsidianMetrics  - AIDA 5x4 Sensor panel for the G.Skill WigiDash display.

ObsidianMetrics is my first ever [AIDA64](https://www.aida64.com/products) sensor panel, designed from scratch for my own [WigiDash](https://www.gskill.com/product/412/415/1702982997/WigiDash) PC command panel. While I made this for myself, I know the device is new and there aren't many sensor panels available for it yet, so, I decided to make one and share it here for everyone to use and edit as they please, and since I made it with sharing it in mind, it is packed with many [features](https://github.com/Infinite-Patience/Aida64-Panels/blob/main/README.md#key-features):

![image](https://github.com/Infinite-Patience/Aida64-Panels/assets/157330778/f34022c0-26e5-4f9f-bb1e-e3acbdfda9fa)


# Download

 

You can get the latest release [here](https://github.com/Infinite-Patience/Aida64-Panels/releases/tag/ObsidianMetrics_v1.0)

Asset source files for the default skin are currently Macromedia Fireworks only but can be downloaded [here](https://github.com/Infinite-Patience/Aida64-Panels/releases/tag/ObsidianMetrics_Fireworks_PNG_Sources_v1.0)

# Key features

- All visible text that isn't a sensor value is editable from within AIDA, and therefore customisable.
- Hand made, slightly Winamp Inspired, dark theme by [me](https://www.deviantart.com/hameed) specifically for the WigiDash community. With all colour and brightness values tweaked for optimal display on the WigiDash, with unique gauges, and an (hopefully) intuitive default color scheme.
- Includes both background and foreground images for the various sections, this means the subpanels/widgets can be moved as a whole section and re-arranged (by bulk selecting the layers within the AIDA UI). E.g. You could have the two main CPU and GPU graphs change places, or move the entire left column of clock + 5 graphs to the right side instead, etc. If so desired.
- Extensive IO support with sensors from up to four drives, with working blinking read/write LED's for each one (a possible first, since ive not seen this implemented using AIDA before), as well as live useage monitoring, and bars for utilisation.
- Shared with experienced AIDA tweakers in mind, all assets used follow an intuitive naming convention, making Aida's decades old feeling UI a tiny bit easier to navigate.
- All inlcuded image assets are provided with [source files](https://github.com/Infinite-Patience/Aida64-Panels/releases/tag/ObsidianMetrics_Fireworks_PNG_Sources_v1.0), and are meant for you to use/edit/replace as you please. However these are currently Macromedia Fireworks only, I will be moving to photoshop going onwards though, as i plan on releasing some skin packs for this in the future, i only used Fireworks for this first version, since its quicker for this type of pixel design.

# Sensor modules:-
The panel pulls sensor data from many sensors, and is designed around a one second update interval. I decided to go overboard with the amount of sensors, since its easier to disable/remove the ones you dont need from within AIDA, than adding them.

## GPU Utilisation

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/65511fc7-3f11-4704-9e5a-39650250e9ed)

Large graph for quick glances, with info for temps and fps nearby, as well as power draw.


## CPU Utilisation

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/c8fb7411-893a-4b52-97ea-ba6a8de89af9)

Large graph for quick glances, with info for temps, current CPU clock speed, and power draw nearby.

## IO panel

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/1306278a-7497-471f-b6ef-cd00cb5539c1)


Detailed support for up to 4 drives, with useage gauges, and per-drive, blinking, read-write activity LED's!

## Memory Utilisation

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/1b512826-2d8e-4128-b0a1-4116aba0d4c8)

VRAM and RAM clock speeds, as well as currently available and used values, with large circular gauges for quick glance.
VRAM fills clockwise, while RAM fills counter-clockwise, because why not.

## Clock

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/ecf8d01f-afea-42cd-90d7-36bb20e4fc98)

It took some doing, but I managed to make a 2D [font](https://www.dafont.com/digital-7.font) look 3D-ish while accounting for it changing in real-time, it was fun to do though. 
It looks a little funky here in the preview, but the colours/pixels are tuned for the WigiDash, and (i think) it looks awesome on there.


## LAN/NET/ Meter

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/0e50b8c1-c596-4f5a-b75a-966009b3b134)

Monitor Up and Down data flow, at a glance and with a combined Graph, with blinking red and green arrows to highlight what is active at any given second.
The default graph is tuned for a 120Mb connection.

## Average FPS

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/deb9a20a-61b5-45c9-b988-38d588a3687b)

Measures 0 - 120fps by default, can be changed up in AIDA if needed.


## GPU Temps

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/5a578cdd-8113-4d64-98c3-31bead58da4f)

Graph covers a range of 20 - 85 °c by default. Hotspot sensor value also highlighted.


## CPU Temp

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/b9b1a19a-0488-441f-ac1a-8d6e715a6907)

Monitor temp of time, as well as fan speed here.


## RAM Utilisation

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/3baf7d52-6ae7-4290-ab7a-76f3780a2f43)

Main memory as used over time, and other related info.


## CPU and GPU name panels

![image](https://github.com/Infinite-Patience/AIDA64-Panels/assets/157330778/6b206993-b5bf-456a-aad3-59e23853414b)

GPU & CPU manufacture logo's can be changed by overwriting or replacing the default image. (Looking at you, team red.)
The motherboard name (as seen under the CPU name) is a true sensor value, but both the GPU & CPU names, and driver version, are only editable labels from within AIDA.
Sadly, none of those three are shown as a sensor value in AIDA64, and need to be updated/tweaked manually.



