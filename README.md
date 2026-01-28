PRL-DAG 
presents a paradigm-shifting framework for causal Directed Acyclic Graph (DAG) discovery that reformulates the combinatorial search problem into a structured reinforcement learning task in permutation space. This repository contains the official implementation of the PRL-DAG algorithm, which introduces three fundamental theoretical contributions:

Theorem 1 (Dependency-Induced Topological Ordering): Reduces DAG search space from adjacency matrix space (O(2^(d²))) to permutation space (O(d!))

Theorem 2 (Variance Reduction Theorem): Establishes that causal structure constraints systematically reduce policy gradient estimation variance

Theorem 3 (Polynomial Sample Complexity): Guarantees convergence with polynomial sample complexity under standard causal identifiability assumptions

🚀 Key Features
Theoretically-Grounded Framework: First provable polynomial sample complexity for causal DAG discovery via reinforcement learning

Efficient Permutation Space Search: Transforms combinatorial graph search into structured sequential decision making

Dynamic Dependency Maintenance: O(1) query complexity for real-time dependency degree updates

End-to-End Causal Reinforcement Learning: Simultaneously learns causal structure while optimizing policies

📋 Installation
Prerequisites
Python ≥ 3.8

Pytorch ≥ 1.9.0

CUDA ≥ 11.1 (for GPU acceleration)
