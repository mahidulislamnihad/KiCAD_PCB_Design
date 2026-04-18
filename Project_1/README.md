This is a PCB learing project that is abailable on youtube.

Link: https://youtube.com/playlist?list=PLn6004q9oeqGl91KifK6xHGuqvXGb374G&si=GqsR4Hr5gDptUJy9 

This project is a digital diya PCB design that automatically lights up by detecting darkness and responding to audio signals.

# Learning Outcome
1. [Circuit Schametic](Circuit_Diagram.png) was created with all necessary components. However, the initial schematic contained overlapping wires, making it difficult to read and potentially problematic for complex designs.
2. To improve clarity, the schematic was refined using net labels, resulting in a cleaner and more understandable design. The updated version is available here:[ Modified Circuit Schematic](Modified_Clean_Circuit_Diagram.png)
3. After finalizing the schematic, an ERC (Electrical Rules Check) was performed to identify any design errors. The ERC results confirmed that no critical issues were present. The report is included here:[ ERC Check](ERC_Check.png)
4.  Once the schematic passed the ERC, component footprints were assigned. The assigned footprints can be viewed in this Screenshot: [Assigned Footprints](Assigned_Footprints.png). For the condenser microphone, an exact footprint was not available in the KiCad library, so a closely matching default footprint was selected based on its physical dimensions.
5. Learned to use the Board Setup tool in KiCad to design a 2-layer PCB. Design constraints were defined based on [PCBWay manufacturing tolerances.]([url](https://www.pcbway.com/pcb_prototype/PCB_Manufacturing_tolerances.html))
6. The configured design rule constraints can be viewed here: [DRC Constraints](DRC_Constaints.png)
7. After setting up the DRC rules, the initial 3D view of the PCB was analyzed to understand its physical appearance: [Initial PCB 3D View](Initial_PCB_3D_View.png)
8. [Top layer](Routed_PCB_Top_Layer.png) and [Bottom layer](Routed_PCB_Bottom_Layer.png) routing has been done.
9. Microcontroller pin was connected to an LED using a via to understand inter-layer connectivity in a 2-layer PCB.
10. Copper fill was applied, and its role in grounding and overall PCB performance has been understood.
11. [DRC report](DRC_Check.png) has been checked to ensure no design error.
12. Why we use Gerber file and how to generate it in KiCAD has been understood.
13. Gerver file view:
    [Top Layer](Gerber_View_Bottom_Layer.png)
    [Bottom Layer](Gerber_View_Bottom_Layer.png)
    
# Next Step
1. In gerber view GND panels is not shown as CU traces rather it is showing as a shape. Checked video need to find proper answer.
   Answer: It is suppose to show in such way.
2. Doing another hands on project on KiCAD.
3. Plan is to design a voltage regulator. [Project_2_REF]([https://www.hackatronic.com/5-volt-power-supply-using-lm-7805-ic/])

# P.S.
This project is based on a YouTube tutorial, followed for PCB design learning purposes, including the provided circuit diagram etc.
The design might not be standard trying to ipmrove and learn improved PCB design with timely progress is the goal.
