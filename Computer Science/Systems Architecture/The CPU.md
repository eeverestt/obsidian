# The Central Processing Unit (CPU)

The [[The CPU|Central Processing Unit (CPU)]] is the primary component responsible for processing instructions in a computer. It is often described as the **brain of a computer** because it performs calculations, makes decisions, and controls the operation of other components.

## [[The CPU#CPU Components|CPU Components]]

### Control Unit (CU)

The **Control Unit (CU)** directs the operation of the [[The CPU|CPU]] by sending **control signals** and **timing signals** to other components.

These signals coordinate activities within the [[The CPU|CPU]] and with external components such as **RAM**.

The **Control Unit (CU)** also **decodes instructions** as part of the [[Registers and FE Cycle#FE Cycle|FE Cycle]].

A [[Registers and FE Cycle#Registers|register]] is a **temporary storage location** used to hold a single instruction, address, or piece of data.

Different [[Registers and FE Cycle#Registers|registers]] are used during the [[Registers and FE Cycle#FE Cycle|FE Cycle]].

### Arithmetic Logic Unit (ALU)

The **Arithmetic Logic Unit (ALU)** performs **arithmetic calculations** and **logical operations**.

Examples include addition, subtraction, comparisons, and logical tests.

The **Arithmetic Logic Unit (ALU)** also stores the [[Registers and FE Cycle#Accumulator|Accumulator (ACC)]], which holds the results of calculations.

### [[CPU Performance#Cache Memory|Cache Memory]]

[[CPU Performance#Cache Memory|Cache memory]] stores **frequently accessed data and instructions** so they can be retrieved quickly.

[[CPU Performance#Cache Memory|Cache]] is organised into **multiple levels**, which prioritise the most frequently used data.

[[CPU Performance#Cache Memory|Cache memory]] is **slower than [[Registers and FE Cycle#Registers|registers]]**, but **much faster than RAM**, making it useful for improving [[CPU Performance|CPU performance]].

## [[The CPU#Architecture|Architecture]]

The [[The CPU#Architecture|architecture]] of a computer refers to the **overall design and structure of its components**.

One of the most common architectures is the **Von Neumann architecture**.

A **Von Neumann computer** stores both **instructions** and **data** in the same memory (**RAM**) and represents both using the **same binary format**.

Although instructions and data share the same memory, they are **not the same thing**:

- An **instruction** tells the computer **what operation to perform**.
- **Data** is the **value used by that instruction**.

For example:

`ADD 43`

- **ADD** is the **instruction**.
- **43** is the **data**.

The **Von Neumann architecture** also contains all of the key [[The CPU#CPU Components|CPU Components]].

---

# Flashcards
#flashcards/cs/systems-architecture/cpu

Central Processing Unit (CPU)::The main component of a computer that processes instructions and controls system operations.

Control Unit (CU)::The CPU component that sends control and timing signals to coordinate the operation of the computer.

Arithmetic Logic Unit (ALU)::The CPU component that performs arithmetic calculations and logical operations.

Accumulator (ACC)::A [[Registers and FE Cycle#Accumulator|register]] used to store the results of calculations.

Register::A small, fast temporary storage location in the CPU used to hold instructions, addresses, or data during processing.

Cache memory::Small, fast memory used to store frequently accessed data and instructions.

Von Neumann architecture::A computer architecture where instructions and data are stored in the same memory and use the same binary format.