# Quantum Entanglement and Trotter Error

The github repo recover the results of [Entanglement accelerates quantum simulation](https://www.nature.com/articles/s41567-025-02945-2) by [Qiskit](https://qiskit.github.io/qiskit-aer) and [Cuda-Q](https://nvidia.github.io/cuda-quantum).

[Our notebook](https://github.com/jonahso/Quantum_Entanglement_and_Trotter_Error/blob/main/qimf_zohim.ipynb) has been collected in the application section of [Cuda-Q official documentation](https://nvidia.github.io/cuda-quantum/latest/applications/python/entanglement_acc_hamiltonian_simulation.html).

## Different Hamiltonians by different simulators

- Quantum mixed field Ising Hamiltonian:
[Matrix Exponential](https://github.com/jonahso/quantum-walk-and-entanglement/blob/dc17a037ce04b46b92eb0e7dc89eb6209a23f023/entanglement_trotter_error.ipynb),
[Qiskit-aer-gpu](https://github.com/jonahso/Quantum_Entanglement_and_Trotter_Error/blob/main/QIMF_qiskit.ipynb),
[Cudaq](https://github.com/jonahso/quantum-walk-and-entanglement/blob/772c9cd6d2e3dec6abd41bcc32ff62ce04cc4cc0/trotter_steps.ipynb)

- Power-law decaying Hamiltonian:
[Qiskit-aer-gpu](https://github.com/jonahso/Quantum_Entanglement_and_Trotter_Error/blob/main/Powerlaw_qiskit.ipynb) 
<!-- Power-law saturate faster than nearest-neighbor, but to larger (smaller?) entanglement -->

- Noisy Trotter circuit: [Qiskit-aer](https://github.com/jonahso/Quantum_Entanglement_and_Trotter_Error/blob/main/QIMF_qiskit_noisy.ipynb)

- Hubbard, SYK: More to do ...

The document below records the performances of qiskit CPU, qiskit GPU and cudaq GPU: 
[CPU/GPU compairson](https://docs.google.com/document/d/19h4Z0-DiqDh6jvB_zOMiuUDnqxpCwPj00U1Lpo-U6t8/edit?usp=sharing) 

