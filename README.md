# EX 3 HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**


![halfadder truthtable](https://github.com/user-attachments/assets/623249d6-5404-4df1-a73c-fe83b0c0369a)




![halfsub truthtable](https://github.com/user-attachments/assets/a0c0cabb-23b9-4255-a0ce-fad4e333be87)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![halfadder code](https://github.com/user-attachments/assets/acb44cbc-f22e-45e9-b284-4ff8c491d6e5)


![halfsub code](https://github.com/user-attachments/assets/e4c960ec-2785-4c99-b785-15e57c78cd83)




**RTL Schematic**

![half adder diagram](https://github.com/user-attachments/assets/a96598a6-9fb9-4a39-af2b-f06887f2ad98)


![halfsub diagram](https://github.com/user-attachments/assets/24b6a3e9-3740-4835-8417-54aa878e5bf4)


**Output/TIMING Waveform**


![halfadder wave form](https://github.com/user-attachments/assets/76e0ef46-dbb1-46c8-8fb5-e4ebf382b25c)


![halfsub waveform](https://github.com/user-attachments/assets/65b797a3-81e9-4b4b-b000-0a80b10d086c)


**Result:**
Thus, the half adder and half subtractor are studied and the truth table,circuit diagram and waveform are verified.
