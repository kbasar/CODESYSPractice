# CODESYSPractice [ MUCT AUTOMATION ]
PLC Programming using Codesys

## Day 1 Session 1 - Overview: PLC Programming using Codesys ( Day 1 Session 1 - Overview )
  
  * Topic Covered * 
  1. Introductions of Trainer and Joinee
  2. Have gone through the PLC Training Material Sequence.pdf file to say what are the topics to be covered in the upcoming trainingprograms.
  2. Have gone through the jobs available for engineers for various roles in different companies, specially in Agile framework.
    ..1. Site Engineer/ troubleshooting jobs
    ..2. Project Engineer / Developer
    ..3. Software / Application Tester
    ..4. Integration Engineer
    ..5. Commissioning engineer
    ..6. Sales / marketting Engineer
    ..7. PO - Product Owner,
    ..8. Architect or SME ( Subject Matter expert)
    ..9. Consultant Engineer
    ..10. Automation Engineer / Professional
    ..11. Scrum Master / RTE
    and so on.
    
  3. Have gone through the use case of CODESYS with Github:
  How to develop codesys project and have public repository in Github, so everyone can contribute and share same project across the globe.
  
  4. We will update this notes and other notes here and gitrepository after every training session.
    
    
## Day 1 Session 2 - Overview: PLC Programming using Codesys ( Day 1 Session 2 - Overview )
We have gon through more detail about the PLC Training Program.
1. We shall start from installation of the Codesys software ( including how to download it)
2. We have plan to start with basic ST ( Structured text) instructions and then moving towards implementing sensors, actuators and finally creating some example projects.
3. Talked about how we use Github to store our Codesys codes in repository as Public, so every one can access it from anywhere.
4. Talked in detail: How to choose company, when to switch company, knowing each others.

## Day 2 - Installation and preparing PLC first project: PLC Programming using Codesys ( Day 2 - Installation and Basics of Codesys Project, Blocks and Variables )
1. Downloading & Installation of Codesys software
2. Finding Soft PLC in Start Menu and How to Start it.
3. Creating very first Codesys Project
4. Different Codesys blocks - PRG, FB & FC: How they are called inside another block.
5. Declaring Standard Variables inside blocks.
6. Assigning variable or values into another variable: through the example of Starting or stopping a motor.
7. NO/NC (Normally open/Normally Close) type pushbutton/Switch/Sensor: How it behaves in real-life with PLC software.
8. Single line Comment/ Multi-line comments

## Day 3 - Simple Temperature COntrol System: PLC Programming using Codesys
1. Started with creating new Codesys project from Empty Template vs Standard Template. 
2. Working with multiple instances of codesys software
3. Exporting by OpenExport/Import option
4. Creating Codesys blocks - PRG, FB & FC
5. Declaring Standard Variables inside blocks.
6. Example 1: Temperature COntrol is implemented where one temperature sensor and one digital Control Output is control based on Hi limit and low limit.
Output is off when temperature is higher than Hi limit and output is On when Temperature lower than low limit. There is two timers - OnDelay (5s) and OffDelay(5s) is also used to prevent quick on/off of heating element connected to the Output.
### Problem to fix
There was one issue we faced - we declared the TON inside FB but it was saying the variable is not defined. It was due to library not available in the newly installed Codesys.
Single line Comment/ Multi-line comments

## Day 4 - Simple Temperature COntrol System Logic used for Flashing Light: How to adapt one logic to other different tasks & FOR LOOP
### Example -1 Flashing light logic created using two TON timers.  
2. Simulated the logic.
3. Made explanation as how to adapt one logic to others tasks - such as temperature control logic used in flashing light solution.

### Example -2  - FOR LOOP : A simple example project 
1. FOR LOOP is programmed to calculate average of 5 power monitor's KW variable and also return total KW
2. Used ChatGPT to write code for FOR LOOP, WHILE DO loop and Repeat Until Loop - possibility is too impressive

## Day 5 (9-May, Tuesday): What is Laser Sensor & How it Works?
1. Laser (Light Amplification by Simulated Emission of Radiation)
2. Link to Automation.com article: 
  - https://automationforum.co/what-is-laser-sensor-how-it-works/ 
  - https://www.elprocus.com/laser-sensor-working-and-its-applications/
  - https://www.apogeeweb.net/electron/The-Function-And-Principle-Of-Laser-Sensor.html
  - https://www.keyence.com/products/sensor/positioning/
  - https://www.youtube.com/watch?v=RBqidWX7B3E&t=968s   
  - https://www.youtube.com/watch?v=cSe7kQiASPY&t=65s
  - https://www.youtube.com/watch?v=DVq10SGKHMU&t=225s (sensor, transmitter, transducer)
  - https://www.youtube.com/watch?v=2pdvvqkguA4&t=44s (pnp, npn sensor)
4. ### Example-1: Detect box and count.

##  Day 6 (12-May, Friday): What are alarm, trip point, and alarm priority in DCS & PLC?
1. Refer following article: https://automationforum.co/what-are-alarm-trip-point-and-alarm-priority-in-dcs-plc/
2. Understanding various types of alarms
3. ###Example-1 : Making alarm logic
4. Understanding Remote Job in PLC/HMI/SCADA (Automation/Test/Dev) job: Cloud Computing/ AWS/Azure
####> Random function in codesys to generate number
