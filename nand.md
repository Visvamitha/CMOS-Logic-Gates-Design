CMOS NAND Gate

Introduction
A NAND gate is one of the most important logic gates in digital design. NAND stands for NOT-AND.
The output becomes LOW only when all inputs are HIGH.

Boolean Expression
Y = NOT(A AND B)

 Truth Table
| A | B | Y |
| - | - | - |
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

CMOS NAND Structure
Pull-Up Network (PUN)
Two PMOS transistors connected in Parallel

Pull-Down Network (PDN)
Two NMOS transistors connected in Series

Why Series NMOS?
The output should connect to GND only when both inputs are HIGH.
When NMOS transistors are connected in series, both transistors must be ON to create a path to GND.

Why Parallel PMOS?
The output should become HIGH whenever at least one input is LOW.
Parallel PMOS transistors allow a path from VDD to the output if any PMOS transistor is ON.

Working for A = 1 and B = 1
PMOS A = OFF
PMOS B = OFF
NMOS A = ON
NMOS B = ON

The output is connected to GND.

Output = 0

My Understanding
If any NMOS transistor in a series connection turns OFF, the path to GND breaks.
Therefore, a NAND gate produces a LOW output only when both inputs are HIGH.

Conclusion
The CMOS NAND gate uses complementary PMOS and NMOS networks to achieve low power consumption and reliable logic operation.
