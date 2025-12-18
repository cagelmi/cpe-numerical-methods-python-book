# Numerical Methods in Chemical Process Engineering Using Python
### Tools for Modeling, Simulation, and Optimization

[![Publisher: Springer](https://img.shields.io/badge/Publisher-Springer_USA-blue)](https://www.springer.com/)
[![Python Version](https://img.shields.io/badge/python-3.10.13-blue.svg)](https://www.python.org/downloads/release/python-31013/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the official Python source code and case studies for the book **"Numerical Methods in Chemical Process Engineering Using Python: Tools for Modeling, Simulation, and Optimization"**, published by **Springer USA** (forthcoming, Late 2026).

## Authors
* **Héctor Jorquera, Ph.D.** –[Academic Profile](https://www.ing.uc.cl/academicos-e-investigadores/hector-ivan-joaquin-jorquera-gonzalez/)
* **Claudio A. Gelmi, Ph.D.** –[LinkedIn Profile](https://www.linkedin.com/in/claudiogelmi/)

---

## About the Book
Numerical modeling and simulation are essential tools for solving modern engineering problems. This book provides a modern approach for science and engineering students, offering the necessary tools to tackle complex modeling, simulation, and optimization challenges.

The text is divided into two comprehensive parts:

### Part I: Foundations and Implementation
Reviews available numerical methods and demonstrates their implementation using Python's built-in functions and libraries. 
* **Key Focus:** Identifying the most suitable algorithms for specific engineering problems.
* **Practical Insights:** Discussion on diagnosing and preventing common numerical difficulties where "universal" algorithms fail.
* **Academic Heritage:** The materials have been refined over 20+ years in the courses *"Applied Mathematics for Process Engineering"* and *"Computational Methods for Transport Phenomena"* at the **School of Engineering of the Pontificia Universidad Católica de Chile**.

### Part II: Case Studies
Offers a curated set of solved problems with complete code and result figures. Highlights include:
* **Areas covered:** Chemical kinetics, reactors, bioreactors, heat transfer, and fluid mechanics.
* **Advanced Topics:** Parameter fitting with nonlinear equations and ODEs, confidence intervals, and bioreactor optimization.
* **Dynamic Perspective:** Beyond steady-state conditions, the book emphasizes dynamic problems and time-dependent simulations.

---

## Python Code
The scripts in this repository correspond to the **"Case Studies"** section of the book.

While programming is an art with multiple valid solutions, we have striven to provide the most direct and efficient implementations for educational purposes.

---

## Requirements

The programs were developed and tested using **Python 3.10.13**. To ensure compatibility and reproducibility, we recommend the following environment:

| Library | Version |
| :--- | :--- |
| `python` | 3.10.13 |
| `numpy` | 1.25.2 |
| `scipy` | 1.11.1 |
| `matplotlib` | 3.7.2 |
| `statsmodels` | 0.14.0 |

### Quick Installation
```bash
pip install numpy==1.25.2 scipy==1.11.1 matplotlib==3.7.2 statsmodels==0.14.0
```

---

## How to Use
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/numerical-methods-chemeng-python.git
   ```
2. **Navigate to the Case Studies folder:** Each folder contains the script and necessary data files for the examples described in the book.
3. **Run a script:**
   ```bash
   python case_study_example.py
   ```

---

## Attribution
If you use these codes, methods, or examples in your own projects, research, or publications, please cite the book:

> **Jorquera, H., & Gelmi, C. A. (2026). *Numerical Methods in Chemical Process Engineering Using Python: Tools for Modeling, Simulation, and Optimization.* Springer USA.**

---

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details. This means you are free to use, modify, and distribute the code, provided that the original copyright and license notice are included.
