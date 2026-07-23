# AI Code Complexity Analyzer

> **Interactive Reproducibility Artifact for ACM COMPUTE 2026**

An interactive web application for evaluating the cognitive complexity of AI-generated Python programs using software engineering metrics.

The tool accompanies the research paper:

> **From Generation to Justification: Transformation in Introductory Programming Education**

It enables researchers, educators, and students to compare **Raw AI-generated code** with **Scaffolded AI-generated code** and quantify the cognitive effort required to understand each solution.

---

## Project Overview

Large Language Models (LLMs) generate syntactically correct code within seconds. However, novice programmers often struggle to understand these solutions.

This project provides a reproducible framework for measuring that difficulty using established software metrics.

The analyzer computes:

- Halstead Difficulty
- Halstead Effort
- Cognitive Complexity
- Abstract Syntax Tree (AST) Depth
- Lines of Code (LOC)

These metrics serve as cognitive proxies for evaluating AI-generated code in introductory programming education.

---

## Features

✔ Interactive browser-based analyzer

✔ Compare Raw AI vs Scaffolded AI

✔ Real-time metric computation

✔ Cognitive load visualization

✔ Complexity hotspot detection

✔ Comparative reduction analysis

✔ No server required

✔ Runs entirely in the browser

✔ Reproducible research artifact

---

## Methodology

The methodology follows the experimental design presented in the accompanying ACM COMPUTE paper.

The experiment compares two prompt conditions:

### Raw AI

Unconstrained prompts that allow the LLM to generate any valid Python solution.

Example:

```
Write a Python program to reverse an array.
```

### Scaffolded AI

Pedagogically constrained prompts designed for first-year programming students.

Example:

```
Generate a Python program for a beginner.
Use simple variables.
Avoid comprehensions.
Avoid lambda.
Use explicit loops.
Add comments.
```

The generated programs are evaluated using software metrics that approximate cognitive effort.

---

## Metrics

### Halstead Difficulty

Measures program difficulty using operators and operands.

---

### Halstead Effort

Represents the estimated mental effort required to understand a program.

Primary metric used in this research.

---

### Cognitive Complexity

Measures control-flow complexity, nesting depth, boolean chains, and structural reasoning effort.

---

### AST Depth

Represents the maximum nesting depth of the Abstract Syntax Tree.

---

### Lines of Code

Used as a descriptive control metric.

---

## Workflow

```
Generate Raw AI Code
          │
          ▼
Generate Scaffolded Code
          │
          ▼
Paste into Analyzer
          │
          ▼
Compute Metrics
          │
          ▼
Compare Results
          │
          ▼
Export Results
```

---

## Research Questions

The analyzer supports investigation of the following research questions:

- Does Raw AI require greater human verification?
- Does Generative AI shift programming from code generation to code justification?
- Can instructional scaffolding reduce cognitive complexity?

---

## Repository Structure

```
AI-Code-Complexity-Analyzer/
│
├── index.html
├── README.md
├── LICENSE
├── images/
├── examples/
├── dataset/
├── results/
└── paper/
```

---

## Technologies

- HTML5
- CSS3
- JavaScript
- GitHub Pages

No backend required.

---

## Live Demo

```
https://YOUR_USERNAME.github.io/AI-Code-Complexity-Analyzer/
```

---

## Citation

If you use this software in your research, please cite:

**Krishnaveni, C. V.**

*From Generation to Justification: Transformation in Introductory Programming Education.*

ACM COMPUTE 2026.

---

## License

MIT License

---

## Acknowledgements

This project was developed as a reproducible research artifact supporting empirical studies on Generative AI, Cognitive Load Theory, and Introductory Programming Education.

---

## Contact

**Dr. C. V. Krishnaveni**

Lecturer in Computer Science

SKR & SKR Government College for Women (Autonomous)

Kadapa, Andhra Pradesh, India
