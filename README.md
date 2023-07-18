# LED-SEQUENCER-DESIGN

- This is my third PCB project

- In this project, I design a 10-Led Sequencer

- There are 3 main processes of this PCB design

  # 1. SCHEMATIC Drawing:

  -  All the element required for this project:
 
 # 2. ROUTING PROCEDURE: 
 
- Make sure TOP Layer is selected while drawing routing track on PCB (Via can be tented in option of solder mask expansion)

- Select BOTTOM layer, Place --> Polygon Pour --> In Properties select Net to GND --> draw copper pour/polygon pour

- Check if any Error (DRC), Tools --> Design Rule Check --> Run Design Rule Check Button

- Select PCB Board file --> Open PCB Rules and Violation view --> in popup select all rules

- Design --> Rules --> Silk to Solder Mask Clearence under Manufacturing --> 0.1 mm --> ok --> Re-Run Rule Check, Tools --> DRC --. Run DRC --> Check

![alt text](https://github.com/binaryupdates/altium-tutorial/blob/main/schematic.png)

 
 # 3. GENERATE GERBER, NC DRILL FILES and Pick and Place File: 
 
- File --> Fabrication output --> gerber Files

- File --> fabrication output --> NC Drill Files --> Ok

- File --> Assembly output  --> Generate Pick and Palce file --> Click "Ok"
