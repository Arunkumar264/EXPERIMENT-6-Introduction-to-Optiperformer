
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

![WhatsApp Image 2025-11-16 at 10 33 39_19ead266](https://github.com/user-attachments/assets/27031b2a-c1e8-42d4-8106-2a6fb63afd17)


---

## Graphs

<img width="526" height="733" alt="Screenshot 2025-08-25 132058" src="https://github.com/user-attachments/assets/85891bba-3b15-46e7-9d3c-4707c8c98b32" />
<img width="772" height="724" alt="Screenshot 2025-08-25 132453" src="https://github.com/user-attachments/assets/8de87318-419b-48ea-8ebe-18b48abad2c6" />
<img width="767" height="735" alt="Screenshot 2025-08-25 132649" src="https://github.com/user-attachments/assets/58a33e64-e6ae-4701-afe1-392f81f0bda2" />
<img width="777" height="732" alt="Screenshot 2025-08-25 132828" src="https://github.com/user-attachments/assets/452238e0-b847-499f-95ca-a42c39427fc1" />
<img width="697" height="547" alt="Screenshot 2025-09-08 100852" src="https://github.com/user-attachments/assets/a534f493-7549-41ab-82e0-49b0a116088f" />



---

## RESULT

Thus , the simulation of optical communication system was done.
