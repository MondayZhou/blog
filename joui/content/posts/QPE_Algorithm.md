+++
title = 'QPE Algorithm'
date = 2022-07-08T15:56:28-04:00
draft = false
decription = 'QPE Algorithm Intro And Optimization'
tags = ['Quantum Computing']
+++

* [Introduction](#inreoduction)
 * [Quantum Computing Concept Development](#quantum-computing-concept-development)
 * [Quantum Algorithm Overview](#quantum-algorithm-overview)


## Introduction
Quantum computers are known to perform certain computational tasks much faster than classical computers. The famous example illustrating this is the problem of factorization of large prime numbers.  Today’s most practical encryption protocols rely on the computational hardness of this problem.  Quantum computer’s ability to break these cryptosystems by running the Shor’s algorithm is one of the main forces driving today’s race among many research groups and big industrial companies to build the quantum computer.  Quantum computers are believed to be useful in other areas as well such as quantum chemistry and machine learning.

### Quantum Computing Concept Development

Quantum computing uses the quantum characteristics of bits, which means, uses the superposition of quantum states and the entanglement characteristics of quantum states to encode data, and operates on quantum states according to the principles of quantum dynamics to realize a calculation that performs operations on data expressed by quantum states plan. The theoretical model of using quantum computing principles was first proposed by Manin's team in 1980. They pointed out that calculations can be realized with two-level quantum systems, that is and proposed a purely theoretical model scheme based on quantum mechanics principles to realize calculations. The theoretical scheme points out that the quantum state in the multi-dimensional Hilbert space can be used to represent data, and the evolution of the quantum state over time can be used to realize the operation of the gate and construct the quantum computing gate.  

In 1985, Deutsch proposed a general-purpose quantum computer theory program and proposed the concept of a quantum Turing machine. In 1982, Feynman expounded a question he was thinking about at a conference 1982, namely, how to effectively simulate the physical system in the real world. Feynman believes that a physical system whose internal evolution laws follow the principles of quantum mechanics is difficult to effectively simulate its evolution with classical computer calculation methods. In the report, he proposed that a quantum computer based on the principles of quantum mechanics may simulate the evolution of a multi-body quantum system. Feynman's conception has attracted the attention and research of researchers. One of the potential applications of quantum computing at this stage is to simulate materials. It is generally believed that the initial ideas in this direction are derived from related concepts elaborated by Feynman.  

Quantum computers mainly hope to use the superposition of quantum states and quantum entanglement in quantum mechanics to realize parallel computing. The originality and coherence of the superposition of quantum states are the basis of quantum parallel computing. Due to the principle of superposition of quantum states and the principle of quantum entanglement, a qubit can be $|0 \rangle $ State and $|1 \rangle $ State at the same time, and $N$ bits can be $N^2$ quantum states at the same time and can realize parallel processing. This makes quantum computers promising to solve complex problems that classical computers cannot solve.  

### Quantum Algorithm Overview

The quantum computer does not simply use a quantum Turing machine to realize the classical algorithm of classical computers, which is not an effective quantum algorithm. Quantum algorithm generally refers to the algorithm that is based on the superposition of states in quantum mechanics and the entanglement of quantum states. It has a more obvious acceleration effect than classical algorithms for solving certain types of problems. For some specific problems, classical algorithms are used to solve such problems. As the difficulty of the problem increases, the computational complexity increases exponentially. Many problems become unsolvable in a limited time. If an effective quantum algorithm is used to make the computational complexity of solving a certain problem polynomial, it is called an effective quantum algorithm.  

The Shor large number factorization algorithm is a quantum algorithm proposed by the mathematician Peter Shor in 1994. The Shor large number factorization algorithm is based on the Simon quantum algorithm and uses the quantum Fourier transform to factorize prime numbers with N bits. The classic algorithm decomposes the number of binary digits as L, and the calculation time complexity is the relationship of the exponential power of L. Using the Shor large number factorization algorithm, the calculation time complexity is the quadratic term of L. Therefore, the Shor large number factorization algorithm calculates the acceleration with exponential power. Since the Shor large number factorization algorithm can be used to crack the modern electronic communication encryption system, it has attracted wide attention from researchers once it was proposed. Researchers have invested a lot of interest in how to implement quantum computing.  

The Grover quantum search algorithm solves the problem of finding a certain number among the disordered N numbers. For solving this type of problem, the best classical calculation algorithm needs to find $N/2$ times, and the Grover quantum search algorithm is reduced to $\sqrt{N}$ times, which has a square root acceleration effect.  

