# Traffic-Light-Controller-RSLogix-MicroLogix-1100
This project implements a multi-directional traffic signal controller using an Allen-Bradley MicroLogix 1100 PLC programmed in RSLogix 500. It demonstrates sequential control, timer-based logic, and safe interlocking between light phases.

**You can test this project using:**

RSLogix Micro Starter Lite

RSLinx Classic

MicroLogix 1100 Emulator (Allen-Bradley)

**I implemented:**

Time-based sequencing using timers (TON).

Conditional transitions using comparison gates (LES, GRT).

Manual enable logic using start/stop switches.

Interlocked outputs to prevent cross-direction greens.

Failsafe fallback (“Yellow for all”) when inactive.

**I am using:**

2 switches (Start, Stop)

6 timers (TON)

Comparison gates: LES, GRT

Digital logic: AND, OR (through series/parallel rungs)

10 outputs

END instruction

PLC features: timer bits (EN, DN, TT), comparison logic, and I/O mapping
