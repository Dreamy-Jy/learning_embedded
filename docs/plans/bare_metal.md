Bare Metal Focus

A stretch goal would be FPGA/ASIC design.

One part of this will be getting up to speed on bare metal programming, and figuring out how to find best practices with each new chip.

## Focuses

These are the chips I'll be focusing on:
- RP2040 on RP Pico 1
- RP2350 on RP Pico 2
- nRF52840 on nice!nano
- BCM2712 on RP CM5

RISC Architecture Focuses
- ARM Cortex-M (M0+, M33, M4)
- ARM Cortex-A (A76)
- RISC-V Hazard3

Boot Loader
Concurrency
- Schedulers, Runtimes, Async
Configure Chip
How Chip boots

## Resources

[Raspberry Pi Pico Lectures 2025](https://www.youtube.com/playlist?list=PLDqMkB5cbBA4GisLzRSqw5x5G38M4zlkr)
---

What System Characteristics:
- memory usage
- power consumption
- reliability
- security
- vaguily speed

What ARM, Chip, and Board Features will I focus on.

I'm going to learn across Bare Metal and Operating Systems programs.


Building drivers for:
- Device configuration
- Device Modification
- General Use of Features
Build Abstractions with drivers
Follow best practices in the space.

For Bare Metal we're going to take core board features and understand how to design with them.
Read the ARM, Chip, and Board docs to determine
Cross reference with best practices (generate a list of target qualities like security, performance, power management).

Move with the understanding that you can only know as you go.


Embedded Intelligence Systems


- Creating the versions of the component, understanding used production ready tools.
- understanding and contributing to versions used in production software.
  - embassy and RTIC
  - lilos or tock


Operating Systems Chips
- BCM2712 on RP CM5
- Nvidia Jetson Oirin Nano (chip unnamed)

The glaring blind spot is that I haven't looked at x86 chips.

The problems I'm having here are sorting knowledge into a structured list of topics

Pick Chips and boards and learn on them:
RP2040 on RP Pico 1
RP2350 on RP Pico 2
nRF52840 on nice!nano
BCM2712 on RP CM5

Bare Metal

Interrupts

How do Malloc and Free work?

Memory Allocation
- Memory Management
- Memory Allocation
- Internal vs External Memory
- Memory Organization
- Memory Mapped IO
- Direct Memory Access
- Flash, RAM, Disk
- How to select memory sizes

Memory
- Memory Management
- Stack vs. Heap
- Static vs Dynamic Allocation
- Flash, RAM, Disk

Concurrency

Design Questions
- How to select memory sizes, and types.

Bootloaders


Power Management

Products
  - Bone conduction Headphones
  - Keyboards
  - Mice (Spacemouse)
  - XR Headsets

core and alloc.

How does core and alloc interact with embedded systems.
- write an allocator.

What counts as a bless choice in embedded rust?
- blessed choice as in a I know this is right why to do something.
Under what circumstances would I need to write my own allocator?
How do Send + Sync work in embedded systems?

https://github.com/rust-embedded/wg#the-libs-team
In embedded systems what does memory allocation get you??

Have the library work on the OS and BM.

Design Questions:
When would I need to do something like this?
How do I do this robustly?

How does async contribute to power management?

How to make sure my program responds with a time limit? (eg. will respond within 100ms)

Architecture 
Memory
Async Rust
