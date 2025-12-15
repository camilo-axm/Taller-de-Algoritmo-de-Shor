# 🔐 Shor’s Algorithm Workshop

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A complete interactive workshop on **Shor’s Algorithm**, the quantum algorithm that revolutionized cryptography by demonstrating that integer factorization can be performed in polynomial time using quantum computers.

## 📚 Description

This repository contains an educational Jupyter Notebook that explores Shor’s algorithm from its mathematical foundations to its practical implementation. It is ideal for students of computer science, mathematics, quantum physics, and anyone interested in quantum computing.

### What is Shor’s Algorithm?

Shor’s algorithm, proposed by Peter Shor in 1994, is a quantum algorithm capable of factoring integers in polynomial time. This capability represents a potential threat to RSA encryption systems, which rely on the computational difficulty of factorization.

## ✨ Workshop Content

### 1. **Modular Arithmetic**
- Basic modular operations
- Modular congruences
- Properties and practical examples

### 2. **Modular Exponentiation**
- Computation of modular powers
- Efficient recursive implementation
- Visualization of periodic patterns

### 3. **Period Finding**
- Periodic function `f(x) = a^x mod N`
- Identification of the period `r`
- Number theory theorems

### 4. **Factorization**
- From the period to the factors
- Euclidean algorithm (GCD)
- Result verification

### 5. **Quantum Algorithm**
- Representation using quantum circuits
- Quantum superposition states
- Quantum Fourier Transform

## 🚀 Solved Exercises

The notebook includes complete solutions for:

### ✅ Exercise 1: Congruence Verification
Step-by-step demonstration of:
- `1977 ≡ 1 (mod 247)`
- `16183 ≡ 15442 (mod 247)`

### ✅ Exercise 2: Factorization of N = 247
Full implementation of Shor’s algorithm to factor `N = 247` using `a = 2`:
- **Period found:** r = 36
- **Factors:** 13 and 19
- **Verification:** 13 × 19 = 247 ✓

## 📊 Visualizations

The workshop includes multiple interactive plots that illustrate:
- Periodic patterns in modular functions
- Behavior of different values of `a` and `N`
- Visual representation of the period-finding process

![Shor's Algorithm](images/shoralgorithm.jpg)

## 🛠️ Installation and Usage

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/camilo-axm/Taller-de-Algoritmo-de-Shor.git
cd Taller-de-Algoritmo-de-Shor
