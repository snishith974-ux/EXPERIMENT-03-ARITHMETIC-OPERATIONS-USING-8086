# EXPERIMENT 3 :8086 MICROPROCESSOR – BASIC ARITHMETIC OPERATIONS
ARITHMETIC OPERATIONS
DATE: 17/11/2026
NAME: KARUNAKARAN R
ROLL NUMBER: RA2511030010324
DEPARTMENT: NETWORKING & COMMUNICATIONS (NWC)
AIM:
To write and execute 8086 Assembly Language programs to perform basic arithmetic operations such as Addition, Subtraction, Multiplication, and Division using an Online 8086 Emulator.

SOFTWARE REQUIRED:
Computer or Laptop
Web Browser (Google Chrome / Microsoft Edge)
Online 8086 Emulator
Internet Connection
THEORY:
8086 Microprocessor
The Intel 8086 is a 16-bit microprocessor developed by Intel. It has a 16-bit data bus and a 20-bit address bus, which allows it to access up to 1 MB of memory. It consists of an Execution Unit (EU) and a Bus Interface Unit (BIU).

The 8086 microprocessor supports various arithmetic and logical instructions to perform mathematical and logical operations.

Technical Specifications of 8086:
Specification	Description
Microprocessor	Intel 8086
Architecture	16-bit
Data Bus	16-bit
Address Bus	20-bit
Maximum Memory	1 MB
Operating Modes	Minimum and Maximum
Registers	AX, BX, CX, DX, SI, DI, BP, SP
Instruction Set	Arithmetic, Logical, Data Transfer, Control Transfer
Clock Frequency	5 MHz, 8 MHz or 10 MHz (depending on version)
8086 REGISTER ORGANIZATION
The 8086 microprocessor contains general-purpose registers used for arithmetic and data manipulation.

AX (Accumulator): Used for arithmetic and logical operations.
BX (Base Register): Used for addressing and data storage.
CX (Count Register): Used for loop and count operations.
DX (Data Register): Used in multiplication and division operations.
ARITHMETIC INSTRUCTIONS
Instruction	Description
ADD	Adds two operands
SUB	Subtracts the second operand from the first
MUL	Performs unsigned multiplication
DIV	Performs unsigned division
MOV	Transfers data between registers
HLT	Stops program execution
PROCEDURE:
Open the Online 8086 Emulator.
Select the 8086 microprocessor environment.
Enter the required Assembly Language program.
Assemble or compile the program.
Check the program for errors.
Execute the program using the Run or Step option.
Observe the register values.
Verify the output for each arithmetic operation.
ONLINE 8086 EMULATOR:
https://yjdoc2.github.io/8086-emulator-web/

EXPERIMENT 1: ADDITION
AIM:
To perform the addition of two 8-bit numbers using the 8086 microprocessor.

PROGRAM:
MOV AL, 05H
MOV BL, 03H
ADD AL, BL
HLT
EXPLANATION:
Load the first number 05H into AL.
Load the second number 03H into BL.
Perform addition using the ADD instruction.
The result is stored in AL.
EXPECTED OUTPUT:
Register	Value
AL	08H
BL	03H
Result: 05H + 03H = 08H.

EXPERIMENT 2: SUBTRACTION
AIM:
To perform the subtraction of two 8-bit numbers using the 8086 microprocessor.

PROGRAM:
MOV AL, 09H
MOV BL, 04H
SUB AL, BL
HLT
EXPLANATION:
Load the first number 09H into AL.
Load the second number 04H into BL.
Perform subtraction using the SUB instruction.
The result is stored in AL.
EXPECTED OUTPUT:
Register	Value
AL	05H
BL	04H
Result: 09H - 04H = 05H.

EXPERIMENT 3: MULTIPLICATION
AIM:
To perform the multiplication of two 8-bit unsigned numbers using the 8086 microprocessor.

PROGRAM:
MOV AL, 05H
MOV BL, 04H
MUL BL
HLT
EXPLANATION:
Load the first number 05H into AL.
Load the second number 04H into BL.
Perform multiplication using the MUL instruction.
The 16-bit result is stored in AX (AH:AL).
EXPECTED OUTPUT:
Register	Value
AL	14H
AH	00H
AX	0014H
Result: 05H × 04H = 14H.

EXPERIMENT 4: DIVISION
AIM:
To perform the division of two 8-bit unsigned numbers using the 8086 microprocessor.

PROGRAM:
MOV AX, 0014H
MOV BL, 04H
DIV BL
HLT
EXPLANATION:
Load the dividend 0014H into AX.
Load the divisor 04H into BL.
Perform division using the DIV instruction.
The quotient is stored in AL.
The remainder is stored in AH.
EXPECTED OUTPUT:
Register	Value
AL	05H
AH	00H
Result: 14H ÷ 04H = 05H, Remainder = 00H.

OUTPUT OF SIMULATION:
FIGURE-01: ADDITION OUTPUT
image
FIGURE-02: SUBTRACTION OUTPUT
image
FIGURE-03: MULTIPLICATION OUTPUT
image
FIGURE-04: DIVISION OUTPUT
image
RESULT:
The 8086 Assembly Language programs for Addition, Subtraction, Multiplication, and Division were successfully written and executed using the Online 8086 Emulator. The results were verified by observing the corresponding register values.

LEARNING OUTCOMES:
Understand the architecture and register organization of the 8086 microprocessor.
Learn basic arithmetic instructions in 8086 Assembly Language.
Understand the working of ADD, SUB, MUL, and DIV instructions.
Execute assembly programs using an online emulator.
Analyze the results stored in 8086 registers.
Platform: Online 8086 Emulator
Programming Language: 8086 Assembly Language
Experiment: Basic Arithmetic Operations
