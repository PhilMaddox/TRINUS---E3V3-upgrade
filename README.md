# TRINUS---BTT_E3V3-control board
Firmware files to operate a BTT E3V3 control board on a Trinus printer
Based on the Marlin 2.1.1 released version. 

## Trinus basic model - No heated bed 
This firmware contains the operational PID controller for the bed just set the bed temp to zero in your slicer

## Heated Bed 
There are 2 types of trinus heated bed

Type 1 - Has onboard control for bed temp 60 or 90 deg via a switch This board needs 12VDC power

Type 2 - Upgraded bed allowing for temp control from software / gcode 
         Direct replacement for Type 1 style board and came with cable for connection to the Panowin control board.
         
         
![Trinus Panowin bed Type 2](https://user-images.githubusercontent.com/11269947/194803489-c71bce80-5b6c-445e-b9b8-1cc8c5805e0c.jpg)




Type 3 - Upgraded longer bed with manual leveling system.  Kodama Heated Bed is controlled from the Bardo control board but has
         non standard wiring as the temp control MOSFET is on the bed boad itself.
         Was supplied as kit with bed , springs, screws , thumb nuts, glass bed & clips 
         
         Note : A solution to allow the bed to be controlled from the E3V3 main control is to be found in the Heated Bed Mod folder
         The modification will suit most commonly avaible control boards

## STL Folder
Contains STL files for an adapter plate to fit the E3V3 board to a Trinus printer and a bracket for a
control board "case" cooling fan. Either 30X30X10 or 40X40X10 
