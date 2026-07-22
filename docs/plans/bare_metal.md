# Programming in Bare Metal Environments

> *note on the name:*
> Reguradless of processor class, bare metal programming changes little in principle

***Anything written is subject to change with my growing understanding.***

Bare Metal programming is about creating abstractions over hardware, and building applications with those abstractions.

In this case hardware is defined as "the processor, it's ISA, and all other hardware features provides by the device". Building hardware is out of scope for this document, comprehending hardware documentation is not.

## Curriculum

Most of active learning will be in building & understanding core abstractions and 
core abstractions along with debugging and testing method.

Side effects of this jurney are learning to build applications and comprehend hardware documentation.
<!--
Dispite them not being core focues you should still track:

Application Building Patterns
Technical Document Literacy (ISA, Chip, Periphals, Errata???)
-->

### Abstractions
To the best of my understanding these are the core abstractions These are core abstractions, critical to the smooth implementation of embedded systems.

**Runtime** - the setup for the program to compile and run.

**Bootloader** - system for updating programs

___*Memory:___
- **Memory Allocators** - dynamic RAM usage
- **File Systems** - data persistace.

___*Drivers:___
- **Microcontroller drivers** - interfaces to functions on the excuting processor.
- **Peripherial drivers** - interfaces with other hardware connected to the excuting processor.

___*Concurrency:___
- **Framework** - concurrency added to your program.
- **Operating Systems** - concurrency you add your program to.

### Debugging and Testing

Testing and debugging represent a significant challenges in bare metal. Standard tools are not often not available and a degree of ingenuity is required to reliable systems.

As I learn more I'll fill this out.
<!--

Most of the

Debugging happens throughout the process.
Hardware → Software Abstractions → Application


The hardware
- the ISA
- the chip
- the board

Common Concepts

The fundation is the ISA, Chip, & Board.
Hardware foundation (ISA > Processor(s) > Board(s))

You produce software abstractions

With abstractions you build application

On Top of these you produce

Fundamental programs/functionality
Bootloader

bootloaders, drivers, allocators, operating systems


-->

## Beyond the Pale

That which is out of scope
- FPGA

---

# Projects

## Fundamentals

Study the composition of all of the fundamental tools and abstractions used in embedded programming.
<!--
-->

## Products

### Ergonomic Keyboard & Mice

#### Keyboard

##### Lap Keyboard

Alice-like + TrackPoint layout, ultra low profile, pen & touch track pad keyboard.

The real innovation here is that

- Touch and EMR Pen Track Pad
- Interface Upgrades
  - Screen
  - Haptics
  - Sound
  - Light
- Erogonomic Layout
  - ultralow profile click encoder (horizontal and vertical)
  - latching buttons
  - monentary buttons
  - flexpoints


##### Desk Keyboard

Nth-D press keys, palm track balls not much thought here yet


### True Wireless Headphones

- IEM + Bone Conducting
- Active Noise Cancelling

### Music Player

- Press Turntable Play Physical UI (Haptic Turntable)
- Filters
- Editing

### Game Controller

### Electric Micro-Mobility

bikes, skateboards, and scooters oh my.

### Pick and Place Machine


<!--
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

Fundamentals
- Boot Loader
- Runtime
- Memory
  - Allocators
  - File Systems
- Driver
  - Microcontroller drivers
    - Interrupts
    - DMA
  - Peripherial drivers
- Concurrency
  - Framework
  - Operating Systems
    - Small OS (RTOS)
    - Full OS (Linux)
- Debugging


Concepts
- Power Management
- Clock Management
- Thermal Management


Boot Loader
- Dual-bank bootloader with rollback protection
Concurrency
- Schedulers, Runtimes, Async

Configure Chip
How Chip boots


## Fundamentals Projects



## Resources

---


What System Characteristics:
- memory usage
- power consumption
- reliability
- security


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


Static vs Dynamic Allocation
Flash, RAM, Disk

Concurrency
Design Questions
- How to select memory sizes, and types.



otloaders



wer Management

Products
<https://github.com/rust-embedded/wg#the-libs-team>
  - Keyboards

  - Mice (Spacemouse)
  - XR Headsets


core and alloc.

How does core and alloc interact with embedded systems.
- write an allocator.
<https://github.com/rust-embedded/wg#the-libs-team>
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

How do i build a debugging probe? like the pico 1?
-->
