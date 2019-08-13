# Kicad versions of Joulescope front panel 

This is a conversion from the pdf dimensioned drawing of the baseline Joulescope JS110 front panel.

## Main features

* All files were initially generated in Kicad Application Version: (5.1.0)-1, release build
* The board edge, SMD pads, pin3 via, screw holes, light pipe hole are implemented in a .kicad_mod footprint file
* The copper pours are implemented in the .kicad_pcb file, as they will need to be recalculated every time you add or move additional components
* There is a specific .lib kicad symbol included, which may make your schematics easier to read, as opposed to a generic 5 pin header

Initial conversion by @SimonMerrett 
Please submit all pull requests and issues to @mliberty1 but be aware that the Kicad files are a community contribution