CMOS NOR Gate

Introduction
A NOR gate is a digital logic gate that performs the NOT-OR operation.
The output becomes HIGH only when all inputs are LOW.

Boolean Expression
Y = NOT(A OR B)

Truth Table
| A | B | Y |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

CMOS NOR Structure

Pull-Up Network (PUN)
Two PMOS transistors connected in Series

Pull-Down Network (PDN)
Two NMOS transistors connected in Parallel

Why Series PMOS?
The output should connect to VDD only when both inputs are LOW.
Since PMOS transistors turn ON for LOW inputs, both PMOS transistors must be ON to create a path to VDD.

Why Parallel NMOS?
The output should connect to GND when any input is HIGH.
Parallel NMOS transistors allow a path to GND whenever at least one NMOS transistor turns ON.

Working for A = 0 and B = 0
PMOS A = ON
PMOS B = ON
NMOS A = OFF
NMOS B = OFF

The output is connected to VDD.

Output = 1

My Understanding
In a NOR gate, PMOS transistors are connected in series because the output should become HIGH only when all inputs are LOW.
NMOS transistors are connected in parallel because any HIGH input should create a path to GND.

Conclusion
The CMOS NOR gate is another fundamental logic gate and demonstrates the complementary nature of PMOS and NMOS transistor networks.
