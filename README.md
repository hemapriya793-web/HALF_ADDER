# HALF_ADDER

AIM:

To design a half adder and half subtracter circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

program:

module half_adder ( input wire a, b, // Inputs output wire sum, // Sum output output wire carry // Carry output );
// Logic equations
assign sum   = a ^ b;   // XOR for sum
assign carry = a & b;   // AND for carry
endmodule 

NAME: B.TAMIZHAN
REF NO: 25018064

image:
[image.pdf](https://github.com/user-attachments/files/24082684/image.pdf)

waves:
[unknown.bmp](https://github.com/user-attachments/files/24082690/unknown.bmp)

output: we got the expected output in program
