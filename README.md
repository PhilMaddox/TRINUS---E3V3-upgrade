# TRINUS---BTT_E3V3-control board
Firmware files to operate a BTT E3V3 control board on a Trinus printer
Based on the Marlin 2.1.1 released version. 

## Trinus basic model - No heated bed 
This firmware contains the operational PID controller for the bed just set the bed temp to zero in your slicer

## Heated Bed 
There are 2 types of trinus heated bed

Type 1 - Has onboard control for bed temp 60 or 90 deg via a switch This board needs 12VDC power

Type 2 - Upgraded bed with manual leveling system.  Kodama Heated Bed is controlled from the Bardo control board but has
         non standard wiring as the temp control MOSFET is on the bed boad itself.
         A solution to allow the bed to be controlled from the E3V3 main control is to be found in the Heated Bed Mod folder
         The modification will suit most commonly avaible control boards

## STL Folder
Contains STL files for an adapter plate to fit the E3V3 board to a Trinus printer and a bracket for a
control board "case" cooling fan. Either 30X30X10 or 40X40X10 
