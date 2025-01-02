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

![Screenshot 2025-01-02 153408](https://github.com/user-attachments/assets/e2a764b0-187e-4f78-b9e2-bd2a81beb6ea)


FULL ADDER truth table

![Screenshot 2025-01-02 153549](https://github.com/user-attachments/assets/5bdb0d28-e3c5-40d2-adcd-1f6f791a8ec9)


**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin


 Full Subtractor Truth table

 ![Screenshot 2025-01-02 153739](https://github.com/user-attachments/assets/bc0b3b0a-8e9f-4758-b9dc-d53542d0850a)

**Procedure**
1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:ishwarya R RegisterNumber:24900725
*/

**Full adder**

![Screenshot 2025-01-02 165836](https://github.com/user-attachments/assets/d9e8bce0-d59c-4528-8855-643b405026b2)


 **full subtractor**

![Screenshot 2025-01-02 165812](https://github.com/user-attachments/assets/a3a29a57-1879-4763-acbd-ae2684c6a671)

**RTL Schematic**

**full adder**

![WhatsApp Image 2024-12-08 at 14 33 17_9951e924](https://github.com/user-attachments/assets/07d8cafe-cb55-4a22-ae42-b08dc73498c2)

**full subtractor**

![WhatsApp Image 2024-12-08 at 14 33 18_5a3f5004](https://github.com/user-attachments/assets/d7858aa3-04ac-4c44-a4a1-fae2fe30c807)

**Output Timing Waveform**

**full adder**

![WhatsApp Image 2024-12-08 at 14 33 17_9d29a5e2](https://github.com/user-attachments/assets/4e6957ad-6947-4f12-bd94-0be56075d03e)

**full subtractor**

![WhatsApp Image 2024-12-08 at 14 33 18_5ebf0d92](https://github.com/user-attachments/assets/3c2e8907-6648-4474-8e01-406825220fd2)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



