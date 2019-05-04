# IILTSpice
This project consists in an synchronous circuit which adds two numbers of two digits. 
The numbers in input are provided by two synchronous registers and the result can be saved in an output register.
The adder has three operating modes that can be selected from the outside:
+ MOD0: every result is saved in the output register.
+ MOD1: are saved only the results that are obtained from the sum of equal numbers .
+ MOD2: are saved only the results that are obtained from the sum of numbers that generate a carry.

The circuit has RESET, PRESET and ENABLE.
RESET sets all the digits of the input registers to 0.
PRESET sets all the digits of the input registers to 1.
ENABLE enables the sum. If the ENABLE is 1 the circuit works in the selected MOD, else the system is in HOLD.
Are managed the FAULT states resulting from incorrect mode commands.
