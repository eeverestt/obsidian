# CPU Performance

CPU performance is affected by three main factors: **Cache Memory**, **Clock Speed**, and **Cores**.

## Cache Memory

Cache memory is located closer to the [[The CPU|CPU]] than RAM, allowing it to provide **data and instructions** to the CPU at a faster rate. 

A computer with more cache memory generally has higher performance because **frequently used instructions can be accessed faster**. 

However, cache memory is costly, so most computers only include a small amount.

## Clock Speed

Clock speed measures how quickly a [[The CPU|CPU]] can process instructions, typically in **Gigahertz (GHz)**. 

For example, a desktop CPU with a clock speed of 3.5 GHz can perform **3.5 billion cycles per second**. 

Higher clock speed allows the CPU to complete the **FE cycle** faster, resulting in better performance because more instructions can be processed per second.

## Cores

A core is a complete set of CPU components capable of performing its own **FE cycle**. 

A **multi-core CPU** contains multiple sets of components within the same [[The CPU|CPU]]:

- A **single-core processor** executes one instruction at a time.
- A **dual-core processor** can execute two instructions simultaneously.
- A **quad-core processor** can execute four instructions simultaneously.

A CPU with more cores can process more instructions at once, potentially improving performance. 

However, performance may not increase if **one core is waiting for another**, or if **software is not designed to use multiple cores**, in which case multi-core CPUs may not run tasks any faster.

---

# Flashcards
#flashcards/systems-architecture

Cache Memory::Memory located closer to the CPU than RAM that stores frequently used data and instructions for faster access.

Clock Speed::The rate at which a CPU can process instructions, measured in Gigahertz (GHz).

Core::A complete set of CPU components capable of executing its own FE cycle; multi-core CPUs contain multiple cores to process instructions simultaneously.