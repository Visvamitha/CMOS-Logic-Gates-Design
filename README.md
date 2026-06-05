CMOS-Logic-Gates-Design
A beginner-friendly VLSI project explaining CMOS Inverter, CMOS NAND, and CMOS NOR gates using NMOS and PMOS transistors.

About This Project
This is my first VLSI-related GitHub project. I created it while learning the fundamentals of CMOS logic design.
The goal of this project is to understand how digital logic gates are implemented using NMOS and PMOS transistors. Instead of only studying truth tables, I wanted to learn how logic gates are actually built at the transistor level.

This repository includes the design and explanation of:
CMOS Inverter
CMOS NAND Gate
CMOS NOR Gate

Along with circuit diagrams, truth tables, and working principles.


What I Learned

During this project, I learned:
How NMOS and PMOS transistors work
Why CMOS technology uses both NMOS and PMOS
How a CMOS inverter produces the complement of the input
Why NAND gates use series NMOS and parallel PMOS networks
Why NOR gates use parallel NMOS and series PMOS networks
The concepts of Pull-Up Networks (PUN) and Pull-Down Networks (PDN)
How transistor arrangements determine logic behavior

Project Structure

CMOS-Logic-Gates-Design
│
├── README.md
├── inverter.md
├── nand.md
├── nor.md
└── images/
    ├── inverter.png
    ├── nand.png
    └── nor.png

Implemented CMOS Gates

CMOS Inverter
The CMOS inverter is the most basic CMOS logic circuit.

Uses one PMOS transistor and one NMOS transistor
Produces the opposite of the input
Forms the foundation of digital CMOS design

CMOS NAND Gate
The NAND gate is one of the most important gates in digital electronics.

PMOS transistors connected in parallel
NMOS transistors connected in series
Output becomes LOW only when both inputs are HIGH

CMOS NOR Gate
The NOR gate is another fundamental CMOS logic gate.

PMOS transistors connected in series
NMOS transistors connected in parallel
Output becomes HIGH only when both inputs are LOW


## Circuit Diagrams
This project includes transistor-level CMOS circuit diagrams for:

* CMOS Inverter
* CMOS NAND Gate
* CMOS NOR Gate

The diagrams were created as part of the learning process to understand CMOS design at the transistor level.


Why I Built This Project
I am currently learning VLSI Design from scratch and wanted to document my understanding through practical projects.

Rather than only reading theory, I wanted to create a project that demonstrates:

* CMOS fundamentals
* Logic gate implementation
* Circuit-level thinking
* Technical documentation skills

This repository represents one of my first steps toward becoming a VLSI Design Engineer.

Future Improvements
In future versions, I plan to add:

* CMOS XOR Gate
* CMOS XNOR Gate
* Half Adder Design
* Full Adder Design
* Verilog Implementations
* Circuit Simulations
* VLSI Design Flow Concepts

Author
Visvamitha
Electronics and Communication Engineering Student
Aspiring VLSI Design Engineer
