This is a PCB learing project that is abailable on youtube.

Link: https://youtube.com/playlist?list=PLn6004q9oeqGl91KifK6xHGuqvXGb374G&si=GqsR4Hr5gDptUJy9 

This project is a digital diya PCB design that automatically lights up by detecting darkness and responding to audio signals.

# Learning Outcome
1. [Circuit Schametic](Circuit_Diagram.png) was created with all necessary components. However, the initial schematic contained overlapping wires, making it difficult to read and potentially problematic for complex designs.
2. To improve clarity, the schematic was refined using net labels, resulting in a cleaner and more understandable design. The updated version is available here:[ Modified Circuit Schematic](Modified_Clean_Circuit_Diagram.png)
3. After finalizing the schematic, an ERC (Electrical Rules Check) was performed to identify any design errors. The ERC results confirmed that no critical issues were present. The report is included here:[ ERC Check](ERC_Check.png)
4.  Once the schematic passed the ERC, component footprints were assigned. The assigned footprints can be viewed in this Screenshot: [Assigned Footprints](Assigned_Footprints.png). For the condenser microphone, an exact footprint was not available in the KiCad library, so a closely matching default footprint was selected based on its physical dimensions.
5. Use of Board setup tool has been learned and to design a 2 layer PCB. Design constain has been setup by analyzing [PCB way manufacturing capabilities tolerances]([url](https://www.pcbway.com/pcb_prototype/PCB_Manufacturing_tolerances.html)).
6. Check the setup Design Rule Constraints here: [DRC Constraints](url)
7. After setting up DRC Rule Intial PCB 3D view has been checked to understand PCB appearence. See here: [Intial PCB 3 View](Initial_PCB_3D_View.png)
8. [Top layer](Routed_PCB_Top_Layer.png) and [Bottom layer](Routed_PCB_Bottom_Layer.png) routing has been done.
9. Microcontroller pin with LED has been conneted through a VIA to learn how to connect two layers.
# Next Step
1. Going through DRC Rules.
2. Tracing

# P.S.
This project is based on a YouTube tutorial, followed for PCB design learning purposes, including the provided circuit diagram etc.
