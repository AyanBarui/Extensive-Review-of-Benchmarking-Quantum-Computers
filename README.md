# Extensive-Review-of-Benchmarking-Quantum-Computers

Supervisor: Dr. Chetan Waghela, Doctoral Researcher in Quantum Optics in IIT Ropar

• Discussed various aspects of some of such benchmarking schemes to measure power and performance of Quantum Computer.

• Analyzed Low-level benchmarks for charactering few-qubit devices, or a few qubits at a time in a large device like Quantum State Tomography, Randomized Benchmarking.

• Recent methods that have better scalability like Quantum Volume, Cross Entropy Benchmarking.

• Application-oriented benchmarks that test the performance of quantum computers on practically relevant tasks like Algorithms Based Benchmarking.

• Simulated Randomized Benchmarking code using qiskit -

We implemented randomized benchmarking on 2-qubit simultaneous with 1-qubit, establishing a Error per Clifford (EPC) 1.320763e-02. In this particular experiment, we have 3 qubits Q0,Q1,Q2. We are running 2Q RB (on qubits Q0,Q2) and 1Q RB (on qubit Q1) simultaneously, where there are twice as many 1Q Clifford gates. We define a noise model for the simulator. To simulate decay, we add depolarizing error probabilities to the CNOT and U gates. We execute these sequences, but with a noise model extended with T1/T2 thermal relaxation error, and fit the exponentially decaying curve. We count the number of gates per Clifford, and calculate the two-qubit Clifford gate error, using the predicted primitive gate errors from the coherence limit.
