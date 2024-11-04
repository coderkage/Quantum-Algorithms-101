# Quantum Computing Exercises with Solutions

This repository contains solutions to a series of quantum computing exercises implemented using Qiskit. Each exercise is designed to explore different aspects of quantum mechanics, such as quantum gates, superposition, entanglement, controlled operations, and oracles for well-known quantum algorithms. Below, you'll find an explanation of each exercise, including the purpose and expected outcome.

---

## Exercise 1: Apply Basic Quantum Gates
1. **Goal**: Learn how to apply individual quantum gates to a single qubit.
2. **Solution**:
   - Create a circuit with 1 qubit.
   - Sequentially apply X, H, and Z gates to the qubit.
   - Measure the final state and visualize the state vector.
3. **Explanation**: The X gate flips the qubit from |0⟩ to |1⟩. The Hadamard (H) gate then creates a superposition, and the Z gate applies a phase shift. This setup allows for observing how sequential gate applications transform a qubit's state.

---

## Exercise 2: Superposition with Hadamard Gate
1. **Goal**: Understand how the Hadamard gate creates superposition.
2. **Solution**:
   - Apply a Hadamard gate to a single qubit.
   - Measure and visualize the result.
3. **Explanation**: The Hadamard gate creates an equal probability of measuring |0⟩ or |1⟩ by transforming |0⟩ into a superposition state. This exercise illustrates how quantum mechanics can represent multiple states simultaneously.

---

## Exercise 3: Bell State (Quantum Entanglement)
1. **Goal**: Create entanglement between two qubits.
2. **Solution**:
   - Apply a Hadamard gate to the first qubit.
   - Use a CNOT gate to entangle it with the second qubit.
3. **Explanation**: The result is a Bell state, where the qubits are correlated: measuring one qubit reveals the state of the other. This exercise demonstrates the concept of entanglement, which is foundational to quantum computing.

---

## Exercise 4: Multi-Qubit Superposition
1. **Goal**: Generate a superposition across multiple qubits.
2. **Solution**:
   - Apply Hadamard gates to all three qubits in a 3-qubit circuit.
3. **Explanation**: Each qubit is placed in a superposition, resulting in all possible 3-bit combinations with equal probability. This demonstrates quantum parallelism, as the circuit represents multiple outcomes at once.

---

## Exercise 5: Controlled Operations (CNOT and Toffoli Gates)
1. **Goal**: Understand multi-controlled operations with CNOT and Toffoli gates.
2. **Solution**:
   - Apply a Toffoli gate with the first two qubits controlling the third qubit.
3. **Explanation**: The Toffoli gate flips the third qubit if both control qubits are in state |1⟩. This logic gate can be used for conditional operations and is a fundamental component of many quantum algorithms.

---

## Exercise 6: Custom Circuit with Quantum Gates
1. **Goal**: Combine different gates to explore complex state manipulation.
2. **Solution**:
   - Apply a Hadamard gate to the first qubit, a CNOT between the qubits, and a Z gate to the second.
3. **Explanation**: This setup combines entanglement and phase shifting, illustrating how individual gates contribute to the overall circuit behavior.

---

## Exercise 7: Bell State Circuit for ψ = √(1/2)(|00⟩ + |11⟩)
1. **Goal**: Create a specific Bell state.
2. **Solution**: Implement the standard Bell state circuit and measure the result.
3. **Explanation**: This results in an entangled state with equal probability for |00⟩ and |11⟩, reinforcing the concept of entanglement.

---

## Exercise 8: Implement a Toffoli Gate (CCX Gate)
1. **Goal**: Implement a controlled-controlled-X (Toffoli) gate.
2. **Solution**: Apply the Toffoli gate in a 3-qubit circuit.
3. **Explanation**: The Toffoli gate flips the target qubit if both control qubits are |1⟩. This gate is essential in quantum computing for controlled operations.

---

## Exercise 9: Implement a Fredkin Gate (CSWAP Gate)
1. **Goal**: Understand controlled swap operations.
2. **Solution**: Apply a Fredkin (CSWAP) gate with qubit 0 as the control.
3. **Explanation**: The Fredkin gate swaps qubits if the control qubit is |1⟩, a unique feature useful for certain quantum operations.

---

## Exercise 10: Explore Phase-Shift Gates
1. **Goal**: Observe how phase-shift gates affect a qubit.
2. **Solution**: Apply S, T, and Rz gates with specified angles.
3. **Explanation**: Phase gates add rotations, which alter the qubit's state by adjusting its relative phase, a vital operation for more complex circuits.

---

## Exercise 11: Complex Circuit with Phase-Shift, Toffoli, and Fredkin Gates
1. **Goal**: Build a circuit that combines different quantum operations.
2. **Solution**: Apply phase-shift, Toffoli, and Fredkin gates in sequence.
3. **Explanation**: This circuit shows the effect of multiple quantum gates, including phase shifts and conditional operations.

---

## Exercise 12: Multi-Controlled Circuit
1. **Goal**: Apply controlled operations based on superposition.
2. **Solution**: Use Hadamard, Toffoli, and Phase (S) gates.
3. **Explanation**: This setup demonstrates the combination of superposition with conditional logic, resulting in more nuanced state transformations.

---

## Exercise 13: Oracle for Deutsch’s Algorithm
1. **Goal**: Implement an oracle to test if a function is balanced.
2. **Solution**: Construct the oracle and measure the outcome.
3. **Explanation**: Deutsch’s Algorithm distinguishes between constant and balanced functions. This exercise highlights how quantum circuits can solve specific problems more efficiently than classical algorithms.

---

## Exercise 14: Oracle for Deutsch-Jozsa Algorithm
1. **Goal**: Implement an oracle to test a function's balance.
2. **Solution**: Use an oracle to differentiate constant and balanced functions with 3 input qubits.
3. **Explanation**: The Deutsch-Jozsa Algorithm shows exponential speedup for determining balance in functions.

---

## Exercise 15: Oracle for Simon’s Algorithm
1. **Goal**: Discover a hidden periodicity using Simon’s Algorithm.
2. **Solution**: Construct the oracle with hidden periodicity `s`.
3. **Explanation**: This exercise demonstrates Simon's Algorithm, where the oracle reveals periodic patterns in the data, useful in cryptography.

---

## Exercise 16: Oracle for a Specific State
1. **Goal**: Mark a specific state in Grover’s algorithm.
2. **Solution**: Build an oracle for state |101⟩ and apply Grover’s algorithm.
3. **Explanation**: Grover's Algorithm provides quadratic speedup in search tasks, demonstrated here for a 3-qubit search.

---

## Exercise 17: Oracle for Grover’s Algorithm (Any Target State)
1. **Goal**: Create an oracle for any given target state.
2. **Solution**: Build a customizable oracle function.
3. **Explanation**: This generalized approach allows Grover's Algorithm to search for any target state within a set.

---

## Exercise 18: Oracle with Multiple Solutions
1. **Goal**: Mark multiple target states in Grover’s algorithm.
2. **Solution**: Design an oracle for two states, |101⟩ and |110⟩.
3. **Explanation**: This demonstrates Grover's algorithm with multiple solutions, showing that it can handle complex search spaces.

---

Each exercise in this repository offers hands-on practice with essential quantum computing concepts, laying the groundwork for more advanced quantum algorithms and applications.

