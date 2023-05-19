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

##  Day 7 (16-May, Tuesday): Everything about Valves, DO, DI, Control, Open/Close, Fail alarms?
  ### Understanding Valves
  - Glove Valve Animation: https://youtu.be/KWN9vJq9Z1M?t=100
  - Ball Valve animation: https://youtu.be/NkunrVVtqVQ?t=74
  - Butterfly valve animation: https://youtu.be/E4q42JB-OM0?t=55
  - Gate valve animation: https://youtu.be/C5ZMLWujKGs?t=9
  - Check Valve animation: https://youtu.be/MsHMIaw9QDo?t=42
  - Diaphragm valve animation: https://youtu.be/dxelSWY6bhg?t=43
  - Niddle valve animation: https://youtu.be/CzBB1CEAAS4?t=106
  - Pressure relief Valve animation: (Direct acting) https://youtu.be/bvp7Zqls7Fw?t=54, 
                                     (pilot operated) https://youtu.be/bvp7Zqls7Fw?t=123
                                     
  ### Valve Manufacturers:
  - https://www.spiraxsarco.com/global/en-IN/products/control-systems
  - https://www.circor.com/products/valves
  - https://www.asahi-america.com/valves-and-actuation/actuated-valves
  - https://products.swagelok.com/en/all-products/valves/c/200?clp=true

  ### Understanding IOs/ Connections / Communication with PLC
    - How many IOs required for a valve?
  
  ### Example-1 : Making different valve control logic 

  ### CheatSheet for Agile Framework: https://pdfgate.net/the-definitive-guide-to-scrum-pdf/)

## Day 8 (19-May-2023, Friday): Understanding Instruments & ISA symbols, P&ID, Control Circuit /Electrical Drawing for PLC Programming
- https://theinstrumentguru.com/instrumentation-symbol/
- https://instrumentationtools.com/piping-and-instrumentation-drawing-pid-tutorials-part-3/
- https://blog.projectmaterials.com/instrumentation/pid-symbols/
- https://instrumentationtools.com/isa-codes-symbols-for-process-instrumentation/
- https://hardhatengineer.com/how-to-read-pid-pefs-drawings/
- http://integrated.cc/cse/Instrumentation_Symbols_and_Identification.pdf
  
  ### Creating proper variable, Function Block Names, function name names in PLC Programming
    - Naming Function Blocks
    - Naming Function
    - Naming Variables
    - Structuring Projects
   #### Ref:
   
    - (Intro) https://en.wikipedia.org/wiki/Naming_convention_(programming)
    - https://www.controleng.com/articles/plc-tag-and-address-naming-conventions/
    - https://www.linkedin.com/pulse/plc-naming-conventions-jakob-sagatowski/
    - https://infosys.beckhoff.com/english.php?content=../content/1033/tcplccontrol/12703362827.html&id=1702208969213382648
    - https://infosys.beckhoff.com/english.php?content=../content/1033/te1200_tc3_plcstaticanalysis/3471943051.html&id=
    - https://plcopen.org/guidelines/guidelines
    - https://content.helpme-codesys.com/en/LibDevSummary/varnames.html
    - https://product-help.schneider-electric.com/Machine%20Expert/V1.1/en/LibDevSummary/topics/varnames.htm
    - https://www.ace-net.com/blog/why-you-need-to-standardize-your-plc-variable-naming-conventions
    - https://library.e.abb.com/public/16c8d6530e9c448084913f674a196e8f/AN00244_PLC_coding_style_Rev_A_EN.pdf
    - https://support.industry.siemens.com/cs/document/81318674/programming-guidelines-and-programming-styleguide-for-simatic-s7-1200-and-s7-1500-and-wincc-(tia-portal)?dti=0&lc=en-WW
    - https://support.industry.siemens.com/cs/document/109478084/programming-styleguide-for-s7-1200-1500?dti=0&lc=en-US
  
