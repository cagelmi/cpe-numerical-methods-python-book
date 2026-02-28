# Numerical Methods in Chemical Process Engineering Using Python
### Tools for Modeling, Simulation, and Optimization

[![Publisher: Springer](https://img.shields.io/badge/Publisher-Springer-blue)](https://www.springer.com/)
[![Python Version](https://img.shields.io/badge/python-3.10.13-blue.svg)](https://www.python.org/downloads/release/python-31013/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the official Python source code and case studies for the book [Numerical Methods in Chemical Process Engineering Using Python: Tools for Modeling, Simulation, and Optimization]([https://www.linkedin.com/in/claudiogelmi/](https://link.springer.com/book/9783032229571), published by **Springer Nature** (forthcoming, May 2026).

## Authors
* **Héctor Jorquera, Ph.D.** –[Academic Profile](https://www.ing.uc.cl/academicos-e-investigadores/hector-ivan-joaquin-jorquera-gonzalez/)
Héctor Jorquera is Professor in the Department of Chemical and Bioprocess Engineering, Pontificia Universidad Católica de Chile. He holds BSc and MSc degrees in Chemical Engineering from Universidad de Chile and a PhD from the University of Minnesota. Professor Jorquera has been teaching numerical methods to engineering students since 1992. He has been a visiting professor in ENSBANA (Dijon, France), Imperial College (London, UK), University of Iowa (CGRER) and Harvard University (ACMG). He has published more than 60 papers in scientific journals. He is the author of the textbook Introduction to Air Pollution Engineering (in Spanish).
  
* **Claudio A. Gelmi, Ph.D.** –[LinkedIn Profile](https://www.linkedin.com/in/claudiogelmi/)
Claudio A. Gelmi earned a B.Sc. in Industrial and Chemical Engineering and an M.Sc. in Chemical Engineering from Pontificia Universidad Católica de Chile (UC), and a Ph.D. in Chemical Engineering from the University of Delaware (Newark, USA). He served as an Assistant Professor in UC’s Department of Chemical and Bioprocess Engineering and held leadership roles as Associate Dean for Engineering Education in the School of Engineering and Director of the Center for Teaching Development within the Academic Vice-Rector’s Office. He has authored more than 20 research articles and two textbooks, among other publications. He has led data-driven initiatives as an independent consultant and has taught artificial intelligence in executive education programs at UC. He currently serves as Director of the Artificial Intelligence Center at Universidad San Sebastián (Chile).
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
2. **Navigate to the Case Studies folder:** Each subfolder includes Jupyter notebooks, and any required datasets for the book’s case-study examples.

---

## Attribution
If you use these codes, methods, or examples in your own projects, research, or publications, please cite the book:

> **Jorquera, H., & Gelmi, C. A. (2026). *Numerical Methods in Chemical Process Engineering Using Python: Tools for Modeling, Simulation, and Optimization.* New York, NY: Springer.**

---

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details. This means you are free to use, modify, and distribute the code, provided that the original copyright and license notice are included.
