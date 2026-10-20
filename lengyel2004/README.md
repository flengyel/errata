# Corrections to *More existence theorems for recursion categories*

[Read the correction paper](lengyel2004_repairs_v10.pdf) · [LaTeX source](lengyel2004_repairs_v10.tex)

Version 10, 20 October 2026, 30 pages.

This paper gives corrections to Florian Lengyel, *More existence theorems for
recursion categories*, Annals of Pure and Applied Logic **125** (2004), 1–41.
[Original article DOI](https://doi.org/10.1016/S0168-0072(03)00060-5).

The correction paper includes definitions, corrected statements, proofs, and
counterexamples. It treats the existence theorems, the coalgebra application,
finite generation, and range representation. The main existence proofs retain
their original iteration hypotheses. The general connected-image and
product-union results state their additional stability assumptions.

## Build

Install a TeX distribution with `latexmk`, pdfLaTeX, AMS packages, TikZ-CD,
hyperref, geometry, and needspace. From this directory, run:

```sh
make
```

The rebuilt PDF is written to `build/lengyel2004_repairs_v10.pdf`.
The versioned PDF in this directory is the published copy.

To verify the supplied source and PDF:

```sh
make check
```

The checksums identify the supplied files. Rebuilding may change PDF metadata.

## Version provenance

The version 10 source and PDF are identical to those in
[`flengyel/Categorical_Rice_Shapiro` at commit `85d0da1`](https://github.com/flengyel/Categorical_Rice_Shapiro/tree/85d0da186730abdff6d3f4c4b51fa37e73283471/research/notes/lengyel2004_repair).
## License

The correction paper and its LaTeX source are licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](../LICENSE).
