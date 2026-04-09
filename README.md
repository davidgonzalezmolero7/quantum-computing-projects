# Quantum Computing Projects

This repository contains my personal and academic projects as a 4th-year Physics student at the University of Alicante. My work currently focuses on learning and implementing Quantum Error Correction (QEC) foundations, which serves as the core of my Undergraduate Thesis (TFG).

## Project Overview

These projects are part of my journey into the practical aspects of Fault-Tolerant Quantum Computing. I use Qiskit to bridge the gap between theoretical quantum mechanics and actual circuit implementation.

### Featured Notebooks

#### 1. 3-Qubit Repetition Code (`3repetitioncode-corrector.ipynb`)
Implementation of a basic repetition code designed to protect a single logical qubit against bit-flip errors.
* **Status**: Undergraduate research project.
* **Focus**: Understanding redundancy and the role of majority voting in quantum states.
* **Learning Outcome**: Analyzing how gate fidelity affects the success probability of the correction.

#### 2. Bit-Flip Syndrome Extraction (`bitflip-corrector.ipynb`)
Exploring the use of stabilizer measurements to detect errors.
* **Mechanics**: Implementation of ancillary qubits to perform parity checks (syndrome extraction) without destroying the data qubit's superposition.
* **Implementation**: Designed using CNOT and Toffoli gates to automate the recovery process in a simulated environment.

---

## Technical Stack and Learning Path

* **Core Framework**: Qiskit SDK (IBM Quantum).
* **Languages & Libraries**: Python, NumPy, Matplotlib.
* **Key Skills**: Quantum Circuit Design, Error Mitigation, Syndrome Extraction.
* **Ongoing Specialization**: Supplementing my university studies with the "Hands-on Quantum Error Correction" course by Google Quantum AI.

---

## Getting Started

### Prerequisites
To run these notebooks locally, you will need Python 3.x and the following libraries:
```bash
pip install qiskit qiskit-aer matplotlib pylatexenc
