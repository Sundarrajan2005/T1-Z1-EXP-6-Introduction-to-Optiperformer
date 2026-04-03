
# Exp 6 Simulation of Optical Communication System

## Name : SUNDARRAJAN K
## Reg No : 212223060279

# Introduction to OptiPerformer 

## Aim:

To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory:

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure:

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



## Observation:

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.



## Tabulation:

**Transmission Analysis Across Fiber Lengths**

<img width="1551" height="1671" alt="image" src="https://github.com/user-attachments/assets/187527ce-b4e8-4eb0-95d4-a9937566bf80" />


## MODEL GRAPH:

<img width="1082" height="384" alt="image" src="https://github.com/user-attachments/assets/799ca115-83ee-46ee-bd00-8837f44cdb7a" />

## Graphs:

<img width="940" height="335" alt="image" src="https://github.com/user-attachments/assets/af9b232f-bba7-47bc-8ba4-b82a704547a8" />
<img width="940" height="326" alt="image" src="https://github.com/user-attachments/assets/bde23f03-af46-4334-873d-3ab0a2c1f467" />
<img width="1600" height="626" alt="image" src="https://github.com/user-attachments/assets/aade14b3-c46d-481a-a7bd-4ff83852f1b8" />
<img width="1600" height="557" alt="image" src="https://github.com/user-attachments/assets/64e4cf10-22cc-46ee-88fd-fa75931ea57e" />
<img width="1600" height="554" alt="image" src="https://github.com/user-attachments/assets/153c8efd-c0d1-41fc-85cf-737f4642e7f5" />


## RESULT:

THUS,The Introduction-to-Optiperformer is calculated and output is verified.

