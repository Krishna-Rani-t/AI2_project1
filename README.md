# AI2 Project 1 — Bayes Net Inference (CS/AI Assignment)

This repository contains the code and supporting files for **AI2 Project 1**, which implements **Bayesian network inference and reasoning** as part of an introductory AI/ML course assignment.

The project includes Python code for representing Bayesian networks, performing exact and approximate inference, and applying probabilistic reasoning to example problems.

---

## 📘 Project Overview

Bayesian networks are probabilistic graphical models that represent variables and their conditional dependencies via a directed acyclic graph (DAG). They are widely used for **uncertainty modeling**, **prediction**, and **decision making** under uncertainty.

In this project you will find implementations for:

* Constructing and representing Bayesian network structures
* Performing probabilistic inference (exact or approximate)
* Parsing test cases and running inference over them
* Integration with grading/autograder tools for automated evaluation

This codebase is adapted from the **Berkeley AI (CS188) Bayes Net Inference Project** structure.

---

## 📁 Repository Structure

```
AI2_project1/
├── autograder.py
├── bayesAgents.py
├── bayesNet.py
├── bayesNets2TestClasses.py
├── factorOperations.py
├── game.py
├── ghostAgents.py
├── grading.py
├── graphicsDisplay.py
├── graphicsUtils.py
├── hunters.py
├── inference.py
├── keyboardAgents.py
├── layout.py
├── pacmanAgents.py
├── projectParams.py
├── submission_autograder.py
├── testClasses.py
├── testParser.py
├── textDisplay.py
├── util.py
├── VERSION
└── README.md
```

---

## 🧠 What’s Included

### Core Components

* **bayesNet.py**
  Defines the classes and structures for representing Bayesian networks.

* **inference.py**
  Contains inference algorithms (e.g., exact and approximate inference) for querying the network.

* **factorOperations.py**
  Implements operations on factors needed for probabilistic calculations (e.g., join, marginalize, normalize).

---

## 🧪 Testing & Autograder

* **autograder.py / submission_autograder.py**
  Scripts to automatically run tests and verify correctness of your implementations.

* **testClasses.py / testParser.py / bayesNets2TestClasses.py**
  Test harness and test case definitions for validating functionality.

---

## ▶️ How to Run

1. Make sure you have **Python 3** installed.

2. To run the autograder and test your solutions:

   ```bash
   python3 autograder.py
   ```

   Or to run specific tests:

   ```bash
   python3 testParser.py
   ```

3. You can also import the modules in your own Python scripts and experiment with Bayesian networks:

   ```python
   from bayesNet import BayesNet
   from inference import inferenceFunction
   ```

*(Replace `inferenceFunction` with the relevant inference method you want to use.)*

---

## 🛠 Dependencies

This project uses **standard Python libraries only** — no external packages are required. It is intended to work with the default Python installation.

---

## 📝 Notes

* This repository is structured for coursework and learning, not as a production library.
* Files like `game.py`, `layout.py`, and `pacmanAgents.py` are included to support any examples or test interactions with graphical/state environments.

---

## 📄 License

The original project structure and code are adapted from educational materials. Please respect any original licensing terms if r
