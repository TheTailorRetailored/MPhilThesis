# In the mood for food

This repository contains the LaTeX source for my 2019 Master of Philosophy thesis in Applied Mathematics at the University of Adelaide:

> **In the mood for food: Markov-modulated models for animal foraging**<br>
> Lachlan Bridges, School of Mathematical Sciences

The thesis studies intermittent animal-search strategies using Markov-modulated random walks. It derives an expression for search efficiency, develops numerical approximations, connects several existing foraging strategies within the same framework, and examines a simplified two-dimensional model.

- [Read the University of Adelaide repository copy](https://digital.library.adelaide.edu.au/server/api/core/bitstreams/5308c175-74e6-408e-b714-a00c2053fed8/content)
- [Read the latest build from this repository](https://thetailorretailored.github.io/MPhilThesis/thesis.pdf)

## Building

The document uses `latexmk`, `pdflatex` and Biber:

```bash
latexmk thesis.tex
```

GitHub Actions rebuilds the thesis after each push to `main` and publishes the PDF through GitHub Pages.

## Citation

```bibtex
@mastersthesis{bridges2019mood,
  author = {Bridges, Lachlan},
  title = {In the mood for food: Markov-modulated models for animal foraging},
  school = {The University of Adelaide},
  year = {2019},
  type = {Master of Philosophy thesis}
}
```
