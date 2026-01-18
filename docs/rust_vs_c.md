_State:_ Draft
_Started:_ 06-02-2026 (DD-MM-YYYY)

Differences between Rust and C in embedded systems

- CMSIS Is a C/C++ Thing.
- SVD File based driver generation is a Rust thing
  - This may be only applicable to ARM chips.
  - Rust likes to wrap unsafe code in safe abstractions and this is a scalable solution created for embedded systems.
