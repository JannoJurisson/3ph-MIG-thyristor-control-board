# 3ph-MIG-thyristor-control-board
Control board for my DIY 3 phase MIG welder that uses six thyristors(SCR) for rectifying the output of a old, soviet era three phase isolation transformer (~5kW). 
Raspberry Pico board is used to monitor and control all the functions

## Board Specifications

| Feature | Description |
| :--- | :--- |
| **Power Input** | +24V DC |
| **Current Control** | Potentiometer adjustment for welding current.   |
| **Phase Monitoring** | Isolated inputs for all phases for missing phase detection. |
| **SCR Drive** | Isolated output for six SCRs via ferrite transformers (20KHz). |
| **High-Current Outputs** | Gas solenoid, Main Contactor, Auxiliary Output. |
| **Motor Drivers** | 2x `DRV8825` stepper motor drivers. |
| **User Inputs** | Gun trigger switch, ADC for wire speed/current pots. |
| **Expansion** | `I2C` connector for displays and peripherals. |
| **Special Feature**| Wire motor balancing for dual-motor setups (e.g., spool gun).|

<img width="1723" height="960" alt="3ph_thyristor controller_top" src="https://github.com/user-attachments/assets/fafa20a5-f6e0-49c6-b1b7-873be8620ea4" />
