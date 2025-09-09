# Qiskit Hands-On

This repository contains my first hands-on experiments with **Qiskit** and IBM Quantum systems.  
The goal was to understand the basics of quantum circuit design, simulation, and execution on real quantum hardware.

---

## What I Learned

### 1. Quantum Circuit Simulation
- Creating and running circuits in Qiskit using the `AerSimulator`.
- Measuring qubits and interpreting measurement results.
- Using basic quantum gates:
  - **X (NOT)**: flips a qubit state.
  - **H (Hadamard)**: creates superposition.
  - **Z**: phase-flip.
  - **CNOT**: entangles two qubits (control-target logic).
- Constructing and simulating the **Bell State**, one of the simplest entangled states.

### 2. Noisy Simulation
- Running circuits with a **noise model** to approximate real device imperfections.
- Comparing ideal simulations vs. noisy simulations.
- Understanding how decoherence and gate errors affect measurement outcomes.

### 3. Real Quantum Hardware
- Connecting to IBM Quantum services.
- Transpiling circuits for a real backend (`ibm_torino`).
- Executing circuits on a physical quantum device.
- Collecting and analyzing the output bitstrings from real hardware.

---

## Skills Acquired
- Building quantum circuits in Python with Qiskit.
- Understanding and applying quantum gates.
- Working with simulators (ideal and noisy).
- Executing quantum programs on IBM Quantum hardware.
- Handling results: counts, histograms, and interpretation.

