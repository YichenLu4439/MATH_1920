# MATH 1920 — Multivariable Calculus Lecture Notes

A collection of lecture notes for **MATH 1920: Multivariable Calculus for Engineers** at Cornell University.

These notes are written in LaTeX and organized by topic, combining mathematical definitions, theorems, worked examples, and visualizations to provide a structured reference for studying multivariable calculus.

## 📖 Read the Notes

**[View the Complete Lecture Notes (PDF)](merge.pdf)**

## 📚 Contents

Topics covered include:

- Vectors in Two and Three Dimensions
- Vector-Valued Functions and Space Curves
- Partial Derivatives
- Gradients and Directional Derivatives
- Linear Approximations and Tangent Planes
- Optimization and Lagrange Multipliers
- Multiple Integrals
- Vector Calculus

*The notes are updated as the course progresses.*

## 🛠️ Built With

- **LaTeX** — Mathematical typesetting and document organization
- **TikZ & PGFPlots** — Mathematical diagrams, surfaces, and contour plots
- **Gnuplot** — Function plotting and numerical visualization
- **tcolorbox** — Structured definitions, theorems, problems, and solutions
- **Hyperref** — Navigable table of contents and cross-references

## ⚙️ Compilation

The notes are maintained as a multi-file LaTeX project, with `main.tex` serving as the primary document.

To compile locally, install a LaTeX distribution (such as TeX Live) and Gnuplot.

Compile using:

```bash
latexmk -pdf -shell-escape main.tex
```

The `-shell-escape` option is needed for plots that invoke external programs such as Gnuplot.

Generated auxiliary files and compilation caches are excluded from version control through `.gitignore`.

## 📝 About

These notes are independently compiled and maintained for personal study and academic reference. They are not official course materials and are not affiliated with or endorsed by Cornell University.

**Author:** Yichen Lu  
**Institution:** Cornell University  
**Course:** MATH 1920  
**Academic Term:** Fall 2026

## 📄 License

All rights reserved unless otherwise specified.