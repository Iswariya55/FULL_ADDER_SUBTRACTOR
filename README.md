# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![WhatsApp Image 2024-12-10 at 08 03 01_c70df803](https://github.com/user-attachments/assets/509426a3-c2f0-487c-86e0-21e0be0fdd03)
![WhatsApp Image 2024-12-10 at 08 03 01_9fd92486](https://github.com/user-attachments/assets/8e469a07-1e69-41ec-8fb2-9a431b57e978)

**Procedure**


**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![WhatsApp Image 2024-12-08 at 14 33 17_9951e924](https://github.com/user-attachments/assets/07d8cafe-cb55-4a22-ae42-b08dc73498c2)
![WhatsApp Image 2024-12-08 at 14 33 18_5a3f5004](https://github.com/user-attachments/assets/d7858aa3-04ac-4c44-a4a1-fae2fe30c807)

**Output Timing Waveform**
![WhatsApp Image 2024-12-08 at 14 33 17_9d29a5e2](https://github.com/user-attachments/assets/4e6957ad-6947-4f12-bd94-0be56075d03e)
![WhatsApp Image 2024-12-08 at 14 33 18_5ebf0d92](https://github.com/user-attachments/assets/3c2e8907-6648-4474-8e01-406825220fd2)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



