# From Smooth Manifolds to de Rham Cohomology: Intuition and Significance

Talk manuscript and Beamer presentation slides on smooth manifolds and de Rham cohomology.

## Talk Overview

- **Format**: 45-minute talk + 15-minute Q&A.
- **Target Audience**: Undergraduates, PhD students (modelling PDE, algebraic geometry), and faculty/researchers (optimization PDE, algebra).
- **Core Philosophy**: Focus on intuitive motivation, structural connections, and geometric insight rather than exhaustive technical rigor. Provide inspiration and bridge diverse backgrounds.

## Repository Structure

```text
.
├── README.md
├── .gitignore
├── references.bib    # Shared BibTeX bibliography for manuscript and slides
├── manuscript/       # LaTeX / Markdown manuscript drafts and talk notes
│   └── main.tex      # Manuscript document root
├── slides/           # Beamer presentation source files
│   └── slides.tex    # Presentation deck root
└── figures/          # TikZ, diagrams, and illustrative assets
```

## Compilation

Build the manuscript:
```bash
latexmk -pdf -cd manuscript/main.tex
```

Build the slides:
```bash
latexmk -pdf -cd slides/slides.tex
```
