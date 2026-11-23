# ME 3330: Mechanical Vibrations — Teaching Sample

**[View the Live Interactive Course Site](https://pbharadwaj28.github.io/ME3330_Teaching_Sample/)**

This repository contains a teaching sample for **ME 3330 (Mechanical Vibrations)**, illustrating an instructional approach that integrates rigorous analytical formulation, physical intuition, and computational/experimental validation.

## Contents
* **Course Syllabus (`00_Syllabus.qmd`):** Complete 15-week course structure, learning outcomes, grading framework, and integrated lab sequence referencing Rao (*Mechanical Vibrations*) and Craig & Kurdila (*Fundamentals of Structural Dynamics*).
* **Sample Lecture (`01_notes.qmd`):** Formulating Single-Degree-of-Freedom (SDOF) equations of motion via D'Alembert's Principle, including a worked pivoted-bar example and small-angle linearization.
* **Python Lab (`02_lab.qmd`):** Side-by-side numerical modeling comparing exact nonlinear D'Alembert EOMs against linearized SDOF models using `scipy.integrate.solve_ivp`.
* **Assessment & Rubric (`03_assignment.qmd`):** Formative problem set and grading rubric emphasizing analysis and physical reasoning.

## Building Locally
This site is built with [Quarto](https://quarto.org/) and Python 3 (`numpy`, `scipy`, `matplotlib`, `jupyter`). Install the listed dependencies and in a new terminal run:

```bash
quarto render
quarto preview
```

