# MAC-Datapath-for-Neural-Networks

Designing a 45nm CMOS neural network accelerator with a 1GHz frequency, incorporating SRAM bit cells, decoders, multiplier-adder architecture, and registers, followed by simulation for DC and Transient analysis, including testing for noise margin in read and write operations.

## Table of Contents

### System Goal 
- Design multiplication and accumulation path for neural network using 45nm technology (CMOS) with a targeted frequency of 1GHz and regular voltage transistor (VTG) as transistor specifications.
- Design SRAM 6T bit cell using Cadence Software.
- Implementing an array of 32x32 SRAM cells using 6T SRAM cells.
- Design row and column decoder to read 4-bit data.
- Design Multiplier and Adder architecture.
- Design 4-bit and 8-bit registers.
- Simulate the result to generate DC and Transient analysis.
- Test for noise margin for read and write operation.

## System Overview
<img width="302" alt="image" src="https://github.com/akhilnvs/MAC-Datapath-for-Neural-Networks-/assets/74815494/1042a59a-1913-4c86-a2ad-9e8e61c8df13">


## Inverter Chain 
To calculate the optimal number of stages

<img width="346" alt="image" src="https://github.com/akhilnvs/MAC-Datapath-for-Neural-Networks-/assets/74815494/6b28f507-e816-404f-9c4f-1f50623ffb20">  <img width="325" alt="image" src="https://github.com/akhilnvs/MAC-Datapath-for-Neural-Networks-/assets/74815494/0063b1ab-7e1d-4c02-bb5b-e2f6e2b9ef7d">


## Operation Results for Inverter Chain
![image](https://github.com/akhilnvs/MAC-Datapath-for-Neural-Networks-/assets/74815494/3fa57dce-324a-4790-acb5-d3c35304b12f)


![image](https://github.com/akhilnvs/MAC-Datapath-for-Neural-Networks-/assets/74815494/9861138f-3a9f-471e-aa28-fa9de906d3e6)
