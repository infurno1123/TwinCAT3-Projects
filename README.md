# TwinCAT3-Projects
A collection of big and small projects for practice and practical applications.
Note: Most of these files will be PLC files.
Topics covered so far:
- Sequential Process Control: Designed independent multi-timer cascade relays to handle automated looping structures.

- Digital Interlocking & Latching: Implemented memory tracking arrays, self-holding logic, and two-hand safety circuits with strict time-window constraints (XOR logic).

- Fault Diagnostics: Structured industrially safe Master Fault Latches utilizing automated error-present flags and manual human-reset interlocks to prevent automated machine restarts.

- Data Accumulation & Integer Math: Developed component runtime logging totalizers with automated data roll-overs (INT math).

- Closed-Loop Process Simulation: Engineered real-time thermal loop simulations using REAL floating-point calculations, clock-pulse throttling (TON), and deadband protection (Hysteresis using optimized ELSIF conditions).