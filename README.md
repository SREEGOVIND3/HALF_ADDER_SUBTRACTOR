# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![0b907ba9-3077-432b-9dca-a424dee398aa](https://github.com/user-attachments/assets/d1f193db-50d5-42ef-93ad-b96ac261489d)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B
![bd58da17-06e5-46a0-8d0c-b3eef6630d72](https://github.com/user-attachments/assets/72addecf-3c36-4168-addb-f454e02965d6)


Figure -02 HALF Subtractor

**Truthtable**
![05a1e503-31d6-420b-9437-e978eaab44d5](https://github.com/user-attachments/assets/8639341d-d798-40c2-a3e1-651508c8d12a)

![edde802b-b16b-4e63-bf2c-405bd2bea195](https://github.com/user-attachments/assets/f1fc365d-e79f-4ce3-a78c-870de8d5ad6a)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Sree Govind
RegisterNumber:24900123

**RTL Schematic**
![6807df09-1697-49cc-bd39-fdf2432d23ba](https://github.com/user-attachments/assets/c6f06ef8-b2eb-470e-9fc7-0889bba71209)
![5d362a69-d7fc-425f-873c-f923750556f6](https://github.com/user-attachments/assets/2727cda9-8119-42b3-b19b-8c28f498b120)

**Output/TIMING Waveform**

**Result:**
Thus the given half adder and half subtractor functions are iplemented and their operators are verified using verilog programming
