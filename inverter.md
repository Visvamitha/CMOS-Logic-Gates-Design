CMOS Inverter

Introduction
A CMOS inverter is the most basic CMOS logic gate. It produces the opposite output of the input.

Circuit Structure

A CMOS inverter consists of:
* One PMOS transistor connected to VDD
* One NMOS transistor connected to GND
* Input connected to both transistor gates
* Output taken from the connection between PMOS and NMOS

## Truth Table

| Input (A) | Output (Y) |
| 0         | 1          |
| 1         | 0          |

Working
Case 1: Input = 0
* PMOS = ON
* NMOS = OFF
* Output is connected to VDD

Therefore:Output = 1

Case 2: Input = 1
* PMOS = OFF
* NMOS = ON
* Output is connected to GND

Therefore:Output = 0

Key Points
* NMOS turns ON when the input is HIGH.
* PMOS turns ON when the input is LOW.
* PMOS forms the Pull-Up Network (PUN).
* NMOS forms the Pull-Down Network (PDN).

Conclusion
The CMOS inverter always produces the complement of the input signal and is the fundamental building block of digital CMOS circuits.
