# Phase Kickback with Qiskit

This project explores the concept of phase kickback using Qiskit.

The main goal is to understand how a phase associated with an eigenvalue
of a quantum operation can be transferred to a control qubit through
a controlled operation.

## Topics

- Global phase vs. relative phase
- Phase gates
- Eigenstates and eigenvalues
- Controlled-U operation
- Phase kickback
- Deutsch algorithm
- Quantum interference

## Main Idea

If

U|ψ⟩ = e^{iφ}|ψ⟩,

then applying controlled-U to

(α|0⟩ + β|1⟩)|ψ⟩

produces

α|0⟩|ψ⟩ + βe^{iφ}|1⟩|ψ⟩.

The phase e^{iφ} is therefore encoded into the relative phase
of the control qubit.

## Tools

- Python
- Qiskit
- Qiskit Aer
- NumPy
- Matplotlib
