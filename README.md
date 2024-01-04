# TU Delft - Thesis Stable Variable Impedance Learning

This repository contains the LaTeX source for my literature study on `Stability guarantees in variable impedance control for rigid robotics manipulators in contact with (semi)-rigid environments`.

## Prerequisites

- [TexLive](https://www.tug.org/texlive/) or any LaTeX distribution
- [Arial font](https://www.cufonfonts.com/font/arial-3) (Linux only)
- [Roboto Slab font](https://fonts.google.com/specimen/Roboto+Slab) (Linux only)

## Compile Instructions

1. Clone [the repository](https://github.com/rickstaa/thesis-stable-variable-impedance-learning):

   ```bash
   git clone git@github.com:rickstaa/thesis-stable-variable-impedance-learning.git
   ```

2. Install [TexLive](https://www.tug.org/texlive/) (or any other LaTeX distribution):

   ```bash
   sudo apt-get install texlive-full
   ```

3. Install required fonts (Linux only):

   ```bash
   sudo apt install ttf-mscorefonts-installer fonts-roboto-slab
   ```

4. Compile the document:

   ```bash
   xelatex report.tex
   ```

> [!TIP]
> Use [Visual Studio Code](https://code.visualstudio.com/) with the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension for an optimal editing experience.
