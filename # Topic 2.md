- [Topic 2 Computer Organization](#topic-2-computer-organization)
  - [2.1 Computer Architecture](#21-computer-architecture)
    - [2.1.1 CPU/ALU/CU/Registers](#211-cpualucuregisters)
    - [2.1.2 Primary memory, RAM/ROM](#212-primary-memory-ramrom)
    - [2.1.3 Cache memory](#213-cache-memory)
    - [2.1.4 Machine Instruction cycle](#214-machine-instruction-cycle)
  - [Secondary memory](#secondary-memory)
    - [2.1.5 Persistent storage](#215-persistent-storage)
    - [2.1.6 Main functions of an OS](#216-main-functions-of-an-os)
    - [2.1.7 Use of Application software](#217-use-of-application-software)
    - [2.1.8 Commmonalities of application software](#218-commmonalities-of-application-software)
    - [2.1.9 Bit, Byte, Binary, Denary, Hexadecimal](#219-bit-byte-binary-denary-hexadecimal)
    - [2.1.10 Data representation](#2110-data-representation)
  - [Logic gates](#logic-gates)
    - [2.1.11 AND/OR/NOT/NAND/NOR/XOR](#2111-andornotnandnorxor)
    - [2.1.12 Truth tables](#2112-truth-tables)
    - [2.1.13 Logic diagrams](#2113-logic-diagrams)

# Topic 2 Computer Organization


## 2.1 Computer Architecture

### 2.1.1 CPU/ALU/CU/Registers

![](2020-03-21-10-54-48.png)

> CU - controls other components in the system; decodes instructions into machine code

> ALU - performs arithmetic and logic to carry out instructions

> Program counter register - stores address for the **next** function

> MAR - stores the address in memory that has been read/will be read; MAR stores where in memory an instruction was executed; sends signals to primary memory and CPU

> MDR - stores data that was read or will be read to memory; MDR stores data in memory; 

> Instruction register - Stores data that was transferred to MDR and will be executed next

### 2.1.2 Primary memory, RAM/ROM

> Primary memory - memory directly accessed by the CPU; includes processor cache, ROM, RAM.; internal/main memory; 
> RAM - random access memory, volatile, often larger than ROM
> ROM - flashed once; also random access; read-only; writing to it(flashing) takes a long time

### 2.1.3 Cache memory

> Cache memory - faster than RAM; closer physically to CPU; holds common data operations;

### 2.1.4 Machine Instruction cycle

Fetch → Decode → Execute → Store
- Fetch - PC stores next instruction's address
  - PC copied to MAR, PC += 1
  - Address put on bus
  - Data returned on data bus
- Decode 
  - instruction carried by the MDR copied to instruction register in CPU
  - Translated into machine code for the ALU
- Execute 
  - ALU does the operation/instruction
- Store
  - Results carried to primary memory




## Secondary memory

> non-volatile storage; persistent storage; used for memory swap sometimes; 

### 2.1.5 Persistent storage

### 2.1.6 Main functions of an OS

- Manage memory
- Manage peripherals
- Manage hardware interfaces
- Allocate storage
- Swap between programs/time-slicing

### 2.1.7 Use of Application software

> A type of software allowing you to perform specific tasks
- Word processor; spreaksheets; web browsers; games; etc

### 2.1.8 Commmonalities of application software

- May share toolbars; menus; dialogue boxes
- Managed by the OS

### 2.1.9 Bit, Byte, Binary, Denary, Hexadecimal

> Bit - 0 or 1, smallest amount of data
> Byte - 8 bits
> Binary - base 2
> Denary - base 10
> Hex - base 16 (one digit = 4 bits since 2&4 = 16)

### 2.1.10 Data representation

- more bits = more different values can be stored

## Logic gates

### 2.1.11 AND/OR/NOT/NAND/NOR/XOR

- OR - either or both inputs
- XOR - <mark>exclusive or, true if the inputs are the same, false if they are different</mark>
- NOT - reverses the state
- NAND - AND gate + NOT gate, flip the and result
- NOR - OR gate + NOT gate 
- XNOR - XOR gate + NOT gate

### 2.1.12 Truth tables

### 2.1.13 Logic diagrams

