# Reinforcement Learning Methods for Training Simulated Autonomous Robots Inside Habitat-Lab

Riley Francis - University of Connecticut, School of Computing

📄 **[Read the full paper (PDF)](main.pdf)**

## Paper Preview

[![Page 1](preview/page-01.png)](main.pdf)


## Building

Requires TeX Live (with `biber` and `biblatex-ieee`) and `latexmk`:

```bash
latexmk -pdf main.tex
```

To refresh the page previews below after rebuilding:

```bash
rm -f preview/*.png && pdftoppm -png -r 110 main.pdf preview/page
```