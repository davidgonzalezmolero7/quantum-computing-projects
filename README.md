# Quantum Computing Projects

This repository contains my personal and academic projects as a 4th-year Physics student at the University of Alicante. My work currently focuses on learning and implementing Quantum Error Correction (QEC) foundations, which serves as the core of my Undergraduate Thesis (TFG).

## Project Overview

These projects are part of my journey into the practical aspects of Fault-Tolerant Quantum Computing. I use Qiskit to bridge the gap between theoretical quantum mechanics and actual circuit implementation.

### Featured Notebook

#### 1. 3-Qubit Repetition Codes (`3-qubit-repetition-codes.ipynb`)
Implementation of the fundamental 3-qubit repetition codes to protect a single logical qubit against specific discrete errors.
* **Bit-Flip Correction**: Direct implementation of state encoding, deterministic error simulation (X gate), and in-place decoding. It utilizes CNOT gates for parity checking and a Toffoli (CCX) gate to perform a majority vote and correct the targeted qubit.
* **Phase-Flip Correction**: Extension of the bit-flip logic to protect against phase errors (Z gate). It demonstrates the principle of basis change by wrapping the noisy channel and the correction logic in Hadamard gates.
* **Simulation**: Validated using the `qasm_simulator` from Qiskit Aer to demonstrate recovery under targeted single-qubit errors.

---

## Technical Stack and Learning Path

* **Core Framework**: Qiskit SDK (IBM Quantum).
* **Languages & Libraries**: Python, NumPy, Matplotlib.
* **Key Skills**: Quantum Circuit Design, Error Mitigation, Logic Gates.
* **Ongoing Specialization**: Supplementing my university studies with the "Hands-on Quantum Error Correction" course by Google Quantum AI.

---

## Getting Started

### Prerequisites
To run these notebooks locally, you will need Python 3.x and the following libraries:
```Bash
pip install qiskit qiskit-aer matplotlib pylatexenc
```
## How to Use
Clone the repository:

[https://github.com/davidgonzalezmolero7/quantum-computing-projects.git](https://github.com/davidgonzalezmolero7/quantum-computing-projects.git)


## Navigate to the directory:

```Bash
cd quantum-computing-projects
```


Launch the notebooks:
Open the directory using Jupyter Notebook, JupyterLab, or VS Code to explore, modify, and run the .ipynb files locally.

## About Me
I am a 4th-year Physics undergraduate at the University of Alicante with a strong interest in the intersection of foundational physics and computer science. My academic focus is currently centered on Fault-Tolerant Quantum Computing (FTQC) and Quantum Error Correction.

I am currently applying for the Master's Degree in Quantum Computing at UAM to transition into advanced quantum software engineering and R&D. To further my specialization, I am also supplementing my university studies with the "Hands-on Quantum Error Correction" course by Google Quantum AI.

Feel free to connect or reach out if you are interested in Quantum Error Correction or algorithm implementation.
