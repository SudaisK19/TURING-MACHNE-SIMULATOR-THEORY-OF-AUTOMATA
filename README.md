# Turing Machine Simulator

This repository contains a **Turing Machine Simulator** developed as part of the Theory of Automata course. The simulator is implemented in C++ and models a single-tape Turing Machine, providing insights into the operations and computational capabilities of Turing Machines.

---

## Project Overview

Turing Machines are foundational models in theoretical computer science, defining the limits of what can be computed. This project implements a simulator that:
- Instantiates and parses Turing Machine definitions.
- Builds transition tables.
- Simulates Turing Machine operations on a single tape.
- Displays tape states during computation.

---

## Key Features

### Functions in the Simulator:
1. **`displayTape()`**:
   - Displays the current state of the tape during computation.
   
2. **`parseFile()`**:
   - Parses input files containing Turing Machine definitions.
   - Extracts states, transitions, and tape symbols.

3. **`makeTransitionTables()`**:
   - Constructs transition tables based on the parsed input.
   - Maps states to transitions for efficient simulation.

4. **`turingSimulator()`**:
   - Simulates the Turing Machine's computation on the tape.
   - Manages head movements, state transitions, and tape modifications.

5. **`main()`**:
   - Integrates all components.
   - Initializes the Turing Machine and starts the simulation.

---

## Course Details

- **Course**: Theory of Automata
- **Institution**: National University of Computer & Emerging Sciences

---

## Contributors

- **Muhammad Sudais (22K-4364)**
- **Amna Mubashir (22K-4342)**
- **Sumaiya Waheed (22K-4201)**

---

## Future Enhancements

- Extend support for multi-tape Turing Machines.
- Add a graphical interface for visualizing tape operations.
- Improve the input format to support complex Turing Machine definitions.

---

Explore the repository to understand the implementation and simulate Turing Machine computations!
