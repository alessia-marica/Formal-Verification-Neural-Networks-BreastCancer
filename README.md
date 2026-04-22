# Formal Verification of Neural Networks using SMT Solvers

This repository contains the experimental code developed for my Bachelor Thesis in **Philosophy and Artificial Intelligence** at Sapienza University of Rome.

## Project Overview

The project explores the use of **SMT (Satisfiability Modulo Theories) solvers** for the formal verification of neural networks.

In particular, the work focuses on verifying robustness properties of a **Multilayer Perceptron (MLP)** trained on the **Breast Cancer Wisconsin (Diagnostic) dataset**.

The trained neural network is translated into a set of **logical constraints**, which are then solved using the **Z3 SMT solver** to analyze and verify properties of the model.

## Main Goals

- Train a neural network classifier (MLP) on a medical dataset
- Translate the neural network into logical constraints
- Use SMT solving techniques to formally reason about the model
- Verify robustness properties of the network

## Technologies

- Python
- Z3 SMT Solver
- Neural Networks (MLP)
- Logical constraint encoding

## Research Context

This project explores the intersection between:

- **Artificial Intelligence**
- **Formal Methods**
- **Logic and Verification**

with the goal of investigating how logical reasoning tools can help analyze and verify neural network behavior.

## Author

Alessia Marica  
Bachelor in Philosophy and Artificial Intelligence  
Sapienza University of Rome
