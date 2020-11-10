These files were last updated in September of 2020.

I created these files for the CR-10 using the SKR Mini E3 V1.2

This was accomplished by going line by line and adjusting all the values that were different in the standard marlin code (which drivers to use for motors, bed size, etc)

I made two files.  One for a 3x3 mesh grid and one for a 4x4 mesh grid.

Make sure in your printer settings you add G29 to the startup G code (this triggers the printer to use the mesh bed leveling).


~~Changelog~~
10-Nov-2020
Added configuration and configuration_adv files for reddit user to browse through changes for them to see differences in their code (having an issue on their CR-10S).