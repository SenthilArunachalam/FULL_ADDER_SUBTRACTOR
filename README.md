
### NAME:SENTHIL ARUNACHALAM .P
### REG NO:24900904
### EXP NO 4:Implementation-of-Full-Adder-and-Full-subtractor-circuit

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
### FULL ADDER:![392022409-4f221821-70bf-42e5-a2fc-654c0e2dd2d1](https://github.com/user-attachments/assets/ee7884c3-aaf0-4804-a2f6-3c2305c0d690)




### FULL SUBRACTOR:![392022551-ff1bf36f-7f03-4d61-ba9c-d1fe80c26f1e](https://github.com/user-attachments/assets/22ca93e7-68c6-401f-a215-b89f6dea8d48)

**Procedure**

step-1 Go to quartus software.

step-2 Set new environment.

step-3 Type the code to implement FULL ADDER SUBTRACTOR using verilog and validating their functionality using their functional tables.

step-4 Run the program.

step-5 Give inputs in the waveform table .

step-6 Run the program.

**Program:**
### FULL ADDER:![program](https://github.com/user-attachments/assets/d84e82cd-a59b-4f96-87e8-473fb66322bc)

### FULL SUBRACTOR:![program for full subractor](https://github.com/user-attachments/assets/57ea15f8-0ca4-4d51-921a-1fde98bfd6da)

**RTL Schematic**
### FULL ADDER:![394196174-2335a954-28a1-4074-94e0-4c0731fbe4da](https://github.com/user-attachments/assets/a9607bb2-4775-486f-9752-088d9b399bdf)



### FULL SUBRACTOR:![gate for full subractor](https://github.com/user-attachments/assets/7a848afa-17b8-4a69-8578-8dd0dcbba215)

**Output Timing Waveform**
### FULL ADDER:![timing diagram 4 add](https://github.com/user-attachments/assets/f8e4c03d-fc61-424e-a11c-5f40c59fe9ac)



### FULL SUBRACTOR:![wave form for full subractor](https://github.com/user-attachments/assets/f2851f12-e9df-4420-a302-350f1d86c639)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



