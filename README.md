# RTSA:Scheduling & Resource Access Protocols

This repository analyzes a 3‑task set under different resource access protocols (NPP and HLP), including utilization & feasibility checks and timeline illustrations.

## Quick summary
- **Task set:** t1 (Sensor Data Acquisition), t2 (Trajectory Computation), t3 (Actuator Command Transmission).  
- **CPU Utilization:** U ≈ 96.67%.  
- **Feasibility (RTA):** R₁=7≤10, R₂=18≤20, R₃=20≤24 → all feasible.  
- **Protocols compared:** NPP vs HLP; HLP reduces blocking via priority inheritance and avoids priority inversion seen under NPP.

> See the PDF for full derivations, Gantt timelines, and SystemViewer evidence.

**License:** MIT (see `LICENSE`).  
**Notes:** This repo includes original submission artifacts for transparency.
