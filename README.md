# CPU Scheduling Simulator

A C++17, object-oriented simulator for comparing CPU scheduling policies.

## Current status

The repository contains a buildable project scaffold and an FCFS demonstration.
The following policies are planned: SJF, SRTF, Round Robin, Priority, MLFQ, and Stride.

## Planned capabilities

- Model processes with arrival time, CPU bursts, and scheduling metadata.
- Simulate process states and CPU/I/O bursts.
- Compare waiting, turnaround, completion, and response times.
- Export timeline data for Gantt-chart visualization.

## Build

```powershell
cmake -S . -B build
cmake --build build
.\build\Debug\cpu_sim.exe
```

On single-configuration generators, the executable may be located directly in `build/`.

## Project structure

```text
include/cpu_sim/  Domain models and scheduler interfaces
src/              Application entry point
```

