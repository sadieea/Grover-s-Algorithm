# Grover-s-Algorithm

This repository contains a simulation of Grover's Algorithm implemented on a 2-qubit system. Grover's Algorithm is a quantum search algorithm that provides a quadratic speedup for searching unsorted databases, making it one of the key algorithms in quantum computing.

Project Overview
In this project, we demonstrate Grover's Algorithm with two qubits, which allows for the search of a specific element within a 4-item "database." The simulation uses Qiskit to illustrate the core steps of the algorithm, including:

Oracle Construction: Encodes the target element to be "marked" in the search space.
Amplitude Amplification: Enhances the probability of measuring the correct item by inverting and amplifying the marked state.
Measurement: Confirms the success of the algorithm by measuring the desired state with high probability.
Features
Oracle and Diffuser Design: Implements the Oracle and Diffuser circuits for a 2-qubit system.
Visualization: Displays each step of Grover's Algorithm with circuit diagrams.
Measurement Verification: Demonstrates the effectiveness of the algorithm by increasing the likelihood of finding the target state.
