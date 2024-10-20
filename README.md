# Geetech-A20M-chimera-mod-klipper-config
Got this printer as a gift couple of years ago and decided it's time to upgrade to klipper.
My first few tries were duds and I had to reflash printer 3 times with marlin to get it back to function
but now I managed to connect to printer via klipper with help from klipper Discord group.

This mod was done following the steps from the YouTube video by Paul's Projects. Paul takes off the standard
hotend which is 2-in-1-out and converts it to 2-in-2-out Chimera hotend. I would highly recommend getting the
original one as it has screws on the side of the aluminum heatsink instead of back which will greatly help align
the nozzles to same height.

This is my modified printer.cfg file that works for me for that mod config and I thought I might share it for
someone who wants to do this as well. Keep in mind that this config was not tested on second extruder (left one for me;
i use right one as extruder 1) and that some settings may need tweaking. PrintsLeo3D on YouTube has a very good
step-by-step video on setting up the BL Touch and it's boundries. That's something you might need to check for 
your setup. Z_offset is one you will certainly need to adjust as we all mount BL Touch on different height.

If something doesn't work, you can ask me here, maybe I can do something about it or you can try Discord channel
for Klipper which is very active and will most likely get you to a solution.
