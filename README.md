# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

### Procedure

![Screenshot 2023-12-18 202709](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/43082396-a889-4b9e-9143-f5b0579fba96)



Write the detailed procedure here 


### Program:

###Half Subtractor

![Screenshot 2023-12-18 202727](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/2aeca27f-2fa7-4a65-aa72-39be4a6528a2)

###Full Subtractor

![Screenshot 2023-12-18 202734](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/7bccf017-1087-45b2-9fd5-e46b89ae6cd9)


/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Kathiresan-K
RegisterNumber: 23013376
*/

## Output:
###RTL realization

###Half Subtractor

![Screenshot 2023-12-18 202740](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/a5476e3b-1fed-4e17-a339-aef4d545ac3b)

###Full Subtractor

![Screenshot 2023-12-18 202746](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/d3613397-8580-42b7-bf9f-999a095c68b2)

###Truthtable

###Half Subtractor

![Screenshot 2023-12-18 202755](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/0301d4f7-2a50-4c7c-a363-bc12e7c869ae)


###Full Subtractor

![Screenshot 2023-12-18 202802](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/8ad33bbb-ce17-4f14-8071-3b657f76acfd)

###Timing diagram 

###Half Subtractor

![Screenshot 2023-12-18 202810](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/aeb3949e-2e97-47fe-bb81-e2309f3ce3d8)


###Full Subtractor

![Screenshot 2023-12-18 202821](https://github.com/Kathiresan-23013376/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150008375/785024d7-8725-433e-bf57-af813a6bb644)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
