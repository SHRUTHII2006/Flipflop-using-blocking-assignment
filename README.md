# EXPERIMENT 3: Simulation of All Flip-Flops using Blocking Statement

## AIM
To design and simulate basic flip-flops (SR, D, JK, and T) using **blocking statements** in Verilog HDL, and verify their functionality through simulation in Vivado 2023.1.

## APPARATUS REQUIRED
- Vivado 2023.1
- Computer with HDL Simulator

## DESCRIPTION
Flip-flops are the basic memory elements in sequential circuits.  
In this experiment, different types of flip-flops (SR, D, JK, T) are modeled using **behavioral modeling** with **blocking assignment (`=`)** inside the `always` block.  
Blocking assignments execute sequentially in the given order, which makes it easier to describe simple synchronous circuits.

## PROCEDURE
1. Open **Vivado 2023.1**.  
2. Create a **New RTL Project** (e.g., `FlipFlop_Simulation`).  
3. Add Verilog source files for each flip-flop (SR, D, JK, T).  
4. Add a testbench file to verify all flip-flops.  
5. Run **Behavioral Simulation**.  
6. Observe waveforms of inputs and outputs for each flip-flop.  
7. Verify that outputs match the truth table.  
8. Save results and capture simulation screenshots.

---

## VERILOG CODE

### SR Flip-Flop (Blocking)

<img width="1918" height="1078" alt="srff_code" src="https://github.com/user-attachments/assets/71f4dfe2-f88d-456d-ba6d-c72759d2c15e" />


### SR Flip-Flop Test bench 

<img width="1918" height="1078" alt="srff_tb code" src="https://github.com/user-attachments/assets/6abc94e9-5510-45c5-8486-60a0f6496717" />


#### SIMULATION OUTPUT

<img width="1917" height="1078" alt="srff_out" src="https://github.com/user-attachments/assets/2970e56a-2937-452e-a00e-4a7440972638" />

#### Testbench

<img width="1918" height="1078" alt="srff _tb output" src="https://github.com/user-attachments/assets/e10de0d9-b574-4a08-83d1-d77c1b5afbb5" />


### JK Flip-Flop (Blocking)

<img width="1918" height="1078" alt="jkff" src="https://github.com/user-attachments/assets/a8f04be6-acd3-41e9-9227-8f5dc7163e72" />


### JK Flip-Flop Test bench 

<img width="1918" height="1077" alt="jkff_tb" src="https://github.com/user-attachments/assets/5878b7a1-8f8a-43f0-967d-864f851c42e9" />


#### SIMULATION OUTPUT

<img width="1918" height="1078" alt="jkff output" src="https://github.com/user-attachments/assets/c25f897a-9e6f-4825-9dcc-96bff8e76a10" />


#### Testbench

<img width="1918" height="1077" alt="jkff_tb output" src="https://github.com/user-attachments/assets/9a13c86d-0427-422a-b438-70bd12a85bf5" />


### D Flip-Flop (Blocking)

<img width="1918" height="1077" alt="dff" src="https://github.com/user-attachments/assets/300dc646-3e13-4734-9046-f2d629306c29" />


### D Flip-Flop Test bench 

<img width="1918" height="1076" alt="dff _tb" src="https://github.com/user-attachments/assets/dd59bf7f-7233-4f08-a8c1-4250f6eb693a" />


#### SIMULATION OUTPUT

<img width="1918" height="1078" alt="dff output" src="https://github.com/user-attachments/assets/2e8da3ef-c705-42a1-b6ff-c0534448e120" />


#### Testbench

<img width="1918" height="1078" alt="dff_tb output" src="https://github.com/user-attachments/assets/1d960f8b-c131-474b-b607-899d6a1138dd" />


### T Flip-Flop (Blocking)


<img width="1918" height="1078" alt="tff code" src="https://github.com/user-attachments/assets/2233485f-f96c-4292-997a-dbe0e5fd8ca7" />


### T Flip-Flop Test bench 

<img width="1918" height="1078" alt="tff_tb " src="https://github.com/user-attachments/assets/72b4a2a7-af43-4692-b903-1a7f3a09c010" />


#### SIMULATION OUTPUT

<img width="1918" height="1078" alt="tff out" src="https://github.com/user-attachments/assets/7e319947-1561-46c4-b485-82114c39c48a" />


#### Testbench

<img width="1918" height="1078" alt="tff_tb output" src="https://github.com/user-attachments/assets/acd23263-64b2-4a21-b907-b062e08538de" />



### RESULT

All flip-flops (SR, D, JK, T) were successfully simulated using blocking statements in Verilog HDL.
The outputs matched the expected truth table values, demonstrating correct sequential behavior.
