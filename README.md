# 2_quantum_algorithms_toolkit

# Repository Structure: Quantum Algorithms Toolkit

quantum-algorithms-toolkit/
├── README.md                    # Project overview, Lipton-Regan math proofs, and setup
├── src/                         # Source code for core quantum logic
│   └── qalgos/                  # Modular algorithm implementations
│       ├── grover.py            # Grover's Search (Standard & Optimized)
│       ├── amplitude_amplification.py # Foundation for search algorithms
│       ├── qft.py               # Quantum Fourier Transform implementation
│       ├── phase_estimation.py  # QPE (The engine for Fault-Tolerant QC)
│       └── oracles.py           # Custom Mykhailova-style problem oracles
├── tests/                       # Unit tests using PyTest (Kaiser-inspired)
│   └── test_grover.py           # Verification of search correctness
├── docs/                        # Deep-dive documentation (Buchmann-based)
│   ├── grover_explained.md      # Theoretical walkthrough of search logic
│   └── qft_explained.md         # Mathematical derivation of the QFT
└── diagrams/                    # Circuit visualizations (Johnston-style)


Algorithms implemented

Oracle abstraction explanation

Complexity discussion

When these algorithms are useful / not useful
