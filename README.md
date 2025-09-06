# RTSA – Assignment 2: Scheduling & Resource Access Protocols

**Author:** Saad Ali (ID: 0001061473)  
**Academic Year:** 2024/2025

This repository contains my Assignment 2 for **Real‑Time Systems for Automation**. It analyzes a 3‑task set under different resource access protocols (NPP and HLP), including utilization & feasibility checks and timeline illustrations.

## Contents
- `report/Assignment 2.pdf` – full write‑up with formulas, timelines, and system viewer results.
- `code/assignment_zip/` – extracted files from “Assignment 2. (Report + Assignment).zip” (if any code/artifacts were provided).
- `code/task_zip/` – extracted files from “Task Zip file..zip” (if provided).
- `artifacts/` – original uploaded archives for provenance.

## Quick summary
- **Task set:** t1 (Sensor Data Acquisition), t2 (Trajectory Computation), t3 (Actuator Command Transmission).  
- **CPU Utilization:** U ≈ 96.67%.  
- **Feasibility (RTA):** R₁=7≤10, R₂=18≤20, R₃=20≤24 → all feasible.  
- **Protocols compared:** NPP vs HLP; HLP reduces blocking via priority inheritance and avoids priority inversion seen under NPP.

> See the PDF for full derivations, Gantt timelines, and SystemViewer evidence.

## How to use
If the assignment includes code or VxWorks projects inside `code/`, follow any README there. Otherwise, the `report/` contains all results and methodology.

## Repo metadata (for GitHub)
- **Name:** `rtsa-assignment-2-scheduling-protocols`
- **Description:** Real-Time Systems Assignment 2 — analysis of a 3-task set under NPP/HLP, with utilization, RTA, and timelines (AY 2024/2025).

## Push to GitHub (step‑by‑step)
```bash
# 1) Unzip and enter the project
unzip rtsa-assignment-2-scheduling-protocols.zip
cd rtsa-assignment-2-scheduling-protocols

# 2) Initialize git and make the first commit
git init
git add .
git commit -m "RTSA Assignment 2: scheduling & resource access protocols"

# 3) Create the remote (replace <username>)
git branch -M main
git remote add origin https://github.com/<username>/rtsa-assignment-2-scheduling-protocols.git

# 4) Push
git push -u origin main
```

---

**License:** MIT (see `LICENSE`).  
**Notes:** This repo includes original submission artifacts for transparency.
