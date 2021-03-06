# How To Import Slicer Settings (PrusaSlicer)

1. Install PrusaSlicer from this link (https://www.prusa3d.com/prusaslicer/) if you do not already have it installed. Follow the steps of the installation wizard until the slicer program is installed.

2. Once installed, an initial configuration setup window will popup asking you to select your printer. Feel free to hit "Cancel" and ignore this.

3. Download the "Prusaslicer_config_bundle.ini" file from this folder.

4. On PrusaSlicer, select File > Import > Import Config Bundle... and select the "Prusaslicer_config_bundle" file that you downloaded from this repo. 

5. You're done! The Bioprinter slicer settings should be imported!

*Keep in mind, these slicer settings are just a base, you will most likely have to change settings based on your usage for better results. By default the settings are meant for a bioprinter that uses a syringe of inner diameter 14.5mm and needle gauge 25G. 


# Basic Settings You May Want to Change
If you wish to use a different gauge needle, go to "Printer Settings" > "Extruder 1" and change the nozzle diameter to your desired needle gauge in mm.

If you wish to use a syringe with a different inner diameter, go to "Filament Settings" > "Filament" and change the diameter setting to your desired syringe inner diameter. 

If you notice under/over extrusion of material, going to "Filament Settings" > "Filament" and increasing/decreasing the Extrusion Multipler may be helpful.




