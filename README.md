# 3ph-MIG-thyristor-control-board
Control board for my DIY 3 phase MIG welder that uses six thyristors(SCR) for rectifying the output of a old, soviet era three phase isolation transformer (~5kW). 
Raspberry Pico board is used to monitor and control all the functions

# The board features:

Welding current regulation using a potentiometer
Isolated input for all phases (missing phase detection)
Isolated output for controlling six SCR's using ferrite transformers and 20KHz carrier frequency
Three high current outputs for gas solenoid, main contactor (380V side) and auxiiary output for other functions
Two DRV8825 stepper motor drivers for wire feed 
Gun trigger switch input
I2C connector for LCD 
ADC inputs for Wire speed and current adjust
Wire motor balance for driving two wire motors (one motor in welder, other in gun- for aluminium wire)
+24V input voltage


<img width="1723" height="960" alt="3ph_thyristor controller_top" src="https://github.com/user-attachments/assets/fafa20a5-f6e0-49c6-b1b7-873be8620ea4" />
