# Registers and FE Cycle

## Registers

Each register has a **specific role**. There are **four essential registers** used in the FE Cycle.

### Program Counter

The Program Counter is a register that tracks the **RAM address** of the **next instruction** to be **fetched**.

### Memory Address Register

The Memory Address Register stores the **RAM address** of the **current instruction** the [[The CPU|CPU]] needs to **access**.

### Memory Data Register

The Memory Data Register stores the **instruction** that **has been transferred from RAM** to the [[The CPU|CPU]].

### Accumulator

The Accumulator (ACC) stores the **result** of **mathematical or logical calculations**.

## FE Cycle

The essential idea of the FE Cycle is that **instructions are fetched from RAM**, then **decoded** (understood) and **executed** (run) by the [[The CPU|CPU]].

1. The Program Counter displays the **address in RAM** of the **next instruction** to be processed. This value is copied into the Memory Address Register.
2. The Program Counter is **incremented by 1**. This prepares the [[The CPU|CPU]] for the next instruction to be fetched.
3. The [[The CPU|CPU]] checks the **address in RAM** which matches the address held in the Memory Address Register.
4. The **instruction in RAM** is transferred into the Memory Data Register.
5. The instruction is **decoded** by the [[The CPU#Control Unit (CU)|Control Unit (CU)]], which splits the instruction into an **action** and a **piece of data or an address**.
6. The instruction is **executed**.
7. Any **result of the execution** is stored in the Accumulator (ACC), such as calculations in the [[The CPU#Arithmetic Logic Unit (ALU)|Arithmetic Logic Unit (ALU)]].

---

# Flashcards
#flashcards/cs/systems-architecture/cpu

Register::A small, fast storage location in the CPU that temporarily holds instructions, addresses, or data.

Program Counter::A register that stores the RAM address of the next instruction to be fetched.

Memory Address Register::A register that stores the RAM address of the instruction or data the CPU needs to access.

Memory Data Register::A register that stores the instruction or data transferred from RAM to the CPU.

Accumulator::A register that stores the result of arithmetic or logical operations.

Fetch-Execute Cycle::The process where the CPU fetches an instruction from RAM, decodes it, and then executes it.