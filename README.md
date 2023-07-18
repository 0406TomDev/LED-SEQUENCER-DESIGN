# LED-SEQUENCER-DESIGN

- This is my third PCB project

- In this project, I design a 10-Led Sequencer

- There are 3 main processes of this PCB design

  # 1. SCHEMATIC Drawing:

  -  All the element required for this project:

    .  Instrument NE555DR (you can reference the datasheet here: https://datasheet.ciiva.com/46395/1874740-46395978.pdf?src-supplier=Element14)
  

    ![image](https://github.com/0406TomDev/LED-SEQUENCER-DESIGN/assets/126463997/fbd521df-5b70-451c-ae6c-af225e801b3a)
  


   .  Instrument CD4017BM (you can reference the datasheet here: https://datasheet.ciiva.com/6623/cd4017b-6623853.pdf?src-supplier=Digi-Key)
  

     ![image](https://github.com/0406TomDev/LED-SEQUENCER-DESIGN/assets/126463997/5c5ecb19-b66d-4e98-8711-8f82cc998aa1)
  
  

      . Instrument M20-9990246 (you can reference the datasheet here: https://datasheet.ciiva.com/8046/315376-8046930.pdf?src-supplier=Element14)

   ![image](https://github.com/0406TomDev/LED-SEQUENCER-DESIGN/assets/126463997/408a518e-e208-479a-baf6-7c0e94db3b87)
  


      . 10 Red LED (HLMP-1301) ( https://datasheet.ciiva.com/11773/0900766b800a3de2-11773734.pdf?src-supplier=Rs)
  

  ![image](https://github.com/0406TomDev/LED-SEQUENCER-DESIGN/assets/126463997/3bb9e64a-8fc4-4624-aa58-0156f5eaa0c8)



 
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
