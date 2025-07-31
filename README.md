# systemc-fairness-arbiter-32port
This repository contains the design, implementation, and simulation results of a pointer-based round-robin arbiter built using SystemC. The project is part of the Architectures for Hardware Acceleration course and focuses on ensuring fair and deterministic access to shared resources among multiple requesters in a digital system.

The arbiter supports up to 32 input request ports and uses a 5-bit rotating pointer mechanism to track the next eligible port after each successful grant. It guarantees that no port is starved, making it ideal for real-time embedded systems, SoCs, memory controllers, and network-on-chip (NoC) routers. Simulations were run using a synchronous clocked design with VCD waveform tracing for analysis.

This project demonstrates scalable and modular arbitration logic suitable for real-world integration in high-performance hardware architectures.[AHA_Presentation...pdf](https://github.com/user-attachments/files/21524814/AHA_Presentation.pdf)
