# Programming on Operating System Capable Chips

***Anything written is subject to change with my growing understanding.***

This is about programming in and above operating systems. With special focus on Linux.

## Curriculum

This is the conceptual path that guides the decisions I make in this journey

The description here are sparse. Covering only artifacts produced and interfaces and tools used to produce them. All of theses are conceptually very dense, and as I become more familiar with them I'll map them out.

### Configuring Linux

> Creating the operating systems

I don't know enough about building linux operating systems to write a comprehensive description.

<!--
Your desire is to make purpose built operating systems (embedded, server, and distro)
LFS -> Build Pipeline(s) (you'll need to know the long term consequences of the choice.)
I know of Yocto and LFS but am not sure
how to package this.
-->

### Modifying Linux

> Writing programs run in kernel space

You'll be writing **kernel module** & **kernel modifications** using the kernel's [Core APIs](https://docs.kernel.org/core-api/index.html), [Driver APIs](https://docs.kernel.org/driver-api/index.html#), [Subsystems](https://docs.kernel.org/subsystem-apis.html), [Locking Primitives](https://docs.kernel.org/locking/index.html) and [Development Tools](https://docs.kernel.org/dev-tools/index.html).

Additionally You'll be writing **eBPF programs** using the [eBPF tool suite](https://docs.kernel.org/bpf/index.html).

#### Resources

[The Linux Kernel Documentation](https://docs.kernel.org/)

### Programming Linux

> Writing programs run in users space

You'll writting **userspace programs** using [system calls](https://man7.org/linux/man-pages/man2/syscalls.2.html) and [files systems](https://docs.kernel.org/filesystems/vfs.html).

Other topics may include: GPU programming, UI Programming, Rust Interop

#### Resources

Man Pages ([syscall(2)](https://man7.org/linux/man-pages/man2/syscall.2.html))

The Linux Kernel Documentation ([The Linux Virtual File System](https://docs.kernel.org/filesystems/vfs.html))

*The UNIX TimeSharing System* : bell labs paper (Dennis M. Ritchie and Ken Thompson)

## Prior Art
<!-- A section for projects in this area done by others. Prioritize industry standards -->

## Beyond the Pale

That which is out of scope

Just out of scope
- Distributed systems (single & multi node)
- Performance engineering
- Systems Programming

Far out of scope
- Compiler Design
- Browser Design
- Operating System Design
- Game Engine Design

---

# Projects

## Fundamentals

## Products

### Folding Tablet Workstation

Dual Touch and Pen Screen Laptop. Example devices: ROG Zephyrus Duo (2026) GX651, Lenovo ThinkPad X1 Fold Gen 1.

Consider: foldable screen.
Consider: MxM GPU.

### Portable Game Console

Detachable grip PC Gaming Handheld.

Play modern PC games and emulate consoles.

### Drone Systems

Autonomous Drone Systems. Full autonomy and Full human control.

Build drones in all UAV form factors.
Try all major autonomy hardware.

- Full system
  - transceiver(controller)
  - monitor(headset, handheld)
  - drone
  - camera(s)

### Motion Capture System


### General Robotics

Create robots of all form factors. Arm, cartesian, dog, UAV
Use all major mathematical tools found in robotics.
Use all major software components of robotics

<!--
___
Modifying Operating Systems
- Linux
  - Artifacts
    - Kernel Module
    - Kernel Modification
    - eBPF Program
    - Supporting Artifacts
  - Interfaces
    - Core API [Documentation/core-api/]
      - Core Utilities & Data Structures
      - Concurrency Primitives
      - Memory Management
      - Hardware Interfaces
      - Debugging Interfaces
      - Kernel Entry and Exit
    - Driver API [Documentation/driver-api/]
      - Bus Interfaces
      - Other Subsystems
    - Development Tools [Documentation/dev-tools/]
    - eBPF Tool Suite [Documentation/bpf/]
  - Concepts
    - Kernel Module Lifecycle
    - Kernel Testing
    - Kernel Tracing
    - Driver (a type of module)
    - Configuring and Building the Kernel
    - Userspace Surface
    - Hardware Surface
    - Upstreaming Process
    - more
Develop on Operating Systems
- On Linux
  - Interfaces
    - System Calls
    - File Systems
    - In Kernel User Space API (https://docs.kernel.org/userspace-api/index.html)
  - Concepts (https://claude.ai/chat/8c377ddb-2d5b-4bdc-858e-27193d74e1b1 , fill this out later)
    - Processes
    - IPC
    - Memory
    - Security
      - Credentials
      - File authorization
      - Capabilities
      - Namespaces
      - cgroups v2
      - Syscall Filtering
      - MAC/LSM
- On GPU
- On GUI egui or iced
Books
- The Linux Programming Interface
- Advanced Programming in the UNIX Environment
- UNIX Network Programming
- Linux Kernel Development
---
This a path to coming every level of a system programmer.


Embedded Linux vs Actual Linux (Android, Full Distro)
- Does your devices need to run software made by others?
- Which path is easier(meets spec by deadline)?
How to choose an ISA(x86, ARM, RISC-V)?


When to choose an iGPU vs dGPU.
Classes of CPUs and when to use each.

Operating Systems
- Understanding Operating Systems
- Understanding Linux
- Building Linux Distros
  - an embedded distro vs. a actual distro

Learning to interface with hardware features (ARM Cortex Features, Specific Chip Features, Board Level Features)
- ARM Cortex-M*
- The Chips
Learning to develop software abstractions on hardware.
Best Practices in the space.
Core Chip Features & Drivers and ()Runtimes

ARM Cortex-M And Cortex-A Features

Programming MMUs

  3D Printers
  Drone Systems
  Game controllers

Developing Operating Systems
- Not a priority, we'll develop this overtime
- ISA Programming manual
- Chip datasheet
- Concepts
  - Virtualization
  - Concurrency
  - Persistence
  - Security

ACPI and SMBIOS and Memory Map
Linux Boot Process
Firmware → Bootloader

Why do you need to use assembly to make system calls without libc

Linux Kernel Development
Linux Device Drivers
Understanding the Linux Kernel
OpenOCD, GNU Debugger,

Study Rust Interop (Python, C, C++)
-->
