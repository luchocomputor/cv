# CV

LaTeX source of my CV. The compiled PDF is committed at the repository root, so it can be linked directly.

**[cv.pdf](cv.pdf)** — Louis Almairac, Master MVA (ENS Paris-Saclay) and École des Ponts. Machine learning for time-series and biosignals.

## Build

The class file `resume.cls` sits next to the source, so a plain compilation is enough:

```sh
pdflatex cv.tex
```

Every push that touches `cv.tex` or `resume.cls` triggers a GitHub Actions run that recompiles `cv.pdf` and commits it back.
