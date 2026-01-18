This is a repo for chronicling my process for learning embedded systems.

These are not all my efforts, just a collection of learnings in foundational topics. Additional work is done delivering projects and contributing to open source projects.


# Plan

## Goals
Embedded Systems have Software, Electronics, and Mechanical Components. I will be focusing on becoming a software expert, and having enough skills to prototype in the Electrical and Mechanical areas.

## Software

- Embedded Software is composed of *hardware drivers* and *application runtimes*. Embedded Software happens in 2 contexts *bare metal* and *operating systems*.
  - *hardware drivers* - software that controls or interfaces with hardware (HALs, Component Drivers)
  - *application runtimes* - software that manages application logic, this is distinct from the logic. (RTOS, Async runtimes, Operating Systems)
  - *bare metal* - software written that directly controls hardware.
  - *operating system* - software with no/limited direct access to the hardware.
- I'll build *drivers* and *runtimes* for *bare metal* and *operating systems* contexts.
- I'll start with programming in Rust, and maybe move on to C++.

## Electronics

Implement functionality critical to devices and important for learning electronics.
- use all foundational components

I'm not sure yet how to think about these:
- analog vs. digital
- AC vs DC
- power electronics
- electronics beyond pcbs

## Mechanical

Become a proficient CAD drafter and I'm not sure how to come a good modeler. The goal here is to start mechanical engineering

What are the primary manufacturing processes and how to model for them?
What are the main tools and techniques provided by FreeCAD?

## Notes

One part of this will be getting up to speed on bare metal programming, and figuring out how to find best practices with each new chip.

The other part will be systems programming, and operating systems design(linux distro).

Distributed systems (single and multi machine).
Performance engineering.

On the electronics side it's some what straight forward, AC electronics complicates this, create PCBs using all relevant knowledge.

On the mechanical side I'd need to learn 3D Modeling (CAD and Blender). 3D printing, CNC milling, and Mold making.

Soft robotics and hydraulics would be awesome.

Set a curriculum and a timeline.

Stretch goals
- Contributing to FreeCAD and KiCad.
- Writing FPGA to understand hardware design.
- Writing a compiler for a new language.
