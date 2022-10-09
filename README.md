# TRINUS---BTT_E3V3-control board
Firmware files to operate a BTT E3V3 control board on a Trinus printer
Based on the Marlin 2.1.1 released version. 

# No heated bed 
This firmware contains the operational controller just set the bed temp to zero in your slicer

# Heated Bed 
There are 2 types of trinus heated bed

Type 1 - Has onboard control for bed temp 60 or 90 deg via a switch This board needs 12VDC power

Type 2 - Upgraded bed with manual leveling system.  Bed is controlled from the Bardo control board but has
         non standard wiring as the temp control MOSFET is on the bed itself.
         A solution to allow the bed to be controlled from the main control board is WIP ....TBC
