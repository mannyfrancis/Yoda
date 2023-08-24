# Smoothing Filter
A  Smoothing  filter consisting of Finite  Impulse  Response  (FIR) and Low  Pass  Filter (LPF)  algorithms.
The  hardware used is a NEXYS A7 Field Programmable Gate  Array  (FPGA)  programmedin Verilog. 

<img src = "https://github.com/mannyfrancis/Yoda/assets/53186851/c0899b8b-4763-487c-b48e-021218b19134" width = "440" height ="280">

**The main objective of this project was to experiment with parallel features of an FPGA, with regards to smoothing data from different sources (sensors).**

It was proposed that the Smoothing filter would be prototyped on a Nexys4 board, simulating the sourceand destination addresses in BRAM. 
The filter would be implemented using the Mean filter smoothing method. Two plans were proposed to implement the system; plan A and plan B. 
Plan A would represent a simple working implementation of the system while plan B would be an extension of the features of plan A.

<img src = "https://github.com/mannyfrancis/Yoda/assets/53186851/849a6724-8e99-4a5e-8768-35e7417220ad" width = "440" height ="280">
