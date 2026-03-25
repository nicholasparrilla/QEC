# Quantum Error Correction Notebooks

A collection of Jupyter notebooks exploring quantum error correction from first principles up through small-scale surface code simulations and decoding experiments.

The goal of this repository is to build practical intuition for how QEC works, not just at the level of definitions, but through explicit construction, simulation, and analysis.

---

## Overview

This project develops quantum error correction in stages:

* Start with simple repetition codes and explicit error models
* Introduce stabilizers and syndrome extraction
* Build small surface-code instances
* Simulate noisy circuits
* Apply decoding algorithms
* Estimate logical error rates under different noise assumptions

---

## Repository Structure

```
.
├── 01_repetition_code.ipynb
├── 02_stabilizers_and_syndromes.ipynb
├── 03_surface_code_visualization.ipynb
├── 04_decoding_with_pymatching.ipynb
├── 05_threshold_estimation.ipynb
├── src/
├── data/
└── figures/
```

---

## Topics Covered

### 1. Repetition Codes

* Bit-flip and phase-flip protection
* Encoding and decoding circuits
* Simple noise models

### 2. Stabilizer Formalism

* Stabilizer generators and logical operators
* Syndrome measurement
* Connection between parity checks and measurement outcomes

### 3. Surface Codes

* Lattice structure and qubit layout
* Data vs ancilla qubits
* Time evolution of syndromes

### 4. Decoding

* Mapping syndrome data to detection events
* Minimum-weight perfect matching (MWPM)
* Using PyMatching for decoding experiments

### 5. Logical Error Rates

* Monte Carlo sampling of noisy circuits
* Logical vs physical error rate curves
* Basic threshold estimation workflows

---

##

---

## How to Run

1. Clone the repository
2. Create a Python environment (recommended: Python 3.10+)
3. Install dependencies:


---

## Notes on Scope

This repository focuses on small-scale simulations and core conceps. It is not a hardware-specific implementation.


---

## Possible Extensions

* Circuit-level noise models with measurement errors
* Biased-noise decoding strategies
* Alternative decoders (e.g., belief propagation)
* Larger-distance surface code simulations

---

## References

* Gottesman, *Stabilizer Codes and Quantum Error Correction*
* Fowler et al., *Surface Codes: Towards Practical Large-Scale Quantum Computation*
* Stim and PyMatching documentation

---

## License

MIT License
