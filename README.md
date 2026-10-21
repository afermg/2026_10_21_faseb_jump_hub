# JUMP Hub — FASEB 2026

**Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools**

Alán F. Muñoz — Carpenter-Shen Lab, Purdue University; Carpenter-Singh Lab, Broad Institute

FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

## Published slides

The representation slide6 now labels blue A/B **Control** and orange C/D **Perturbation**. Only those two legend labels changed;coordinates,colors,drawings and axes are unchanged. The original artwork remains preserved in source/history.

The JUMP overview on PDF7 includes **1.8 billion cells**,rounded from the documented1,810,840,525cells across the pinned compound,ORF and CRISPR inputs. [Cell-count source](https://github.com/broadinstitute/jump-profiling-recipe/tree/d2512d978ca17aafead0e99de66386337e6312e4/inputs/cell_counts).

- [View the slides](./slides.pdf) — the unchanged Slides QR destination.
- [Download the PDF](https://raw.githubusercontent.com/afermg/2026_10_21_faseb_jump_hub/main/slides.pdf).
- [JUMP Hub](https://broadinstitute.github.io/jump_hub/).
- [Demo recording](https://doi.org/10.5281/zenodo.23462248), CC BY 4.0.

The **public PDF has25pages and ends at the QR slide**. The three additional slides are excluded from this PDF,at the presenter's request. References is PDF24 with39distinct clickable URLs;the UMAP reference entry was explicitly removed. UMAP plots and methodological qualifications are unchanged.

Word2vec and biological representations remain separate on5/6. Tools15;demo and AI prompt16;return17;acknowledgements23;References24;QR25. Broad is above Carpenter-Singh/Cimini;Purdue is above Carpenter-Shen. Main narration remains1380seconds.

## Full source and reproducibility

The **full Overleaf deck remains28pages**,including additional slides26–28. The source files in this repository also retain that full deck. Compile `slides.tex` with XeLaTeX,moloch and Fira Sans,then select pages1–25 for the public PDF. `main.tex` is a preserved empty starter,not the presentation root. All25retained pages were checked for identical rendering,text and links against the full build. Prior public versions remain in Git history;this is a PDF-length change,not a history-removal operation.

Illustrative word/cell coordinates are invented,not measured data. PLK1 is the annotated positive control;GJA8 is an exploratory phenotype example. The full deck's published-paper comparison remains a separate analysis with its extra-site caveat. Original source/figure attribution and scientific qualifications are preserved. Third-party material retains its original terms;no blanket license is newly granted.

## Validated PDF

- Public pages:25,ending at QR.
- Public PDF SHA256:`e52dbde3dbed1302e7de3e3f3854a09dc29780c0315ded4ba799a17f60cf09d4`.
- Full-deck PDF SHA256:`e9461c0c4ae5de01167b3c39e80ffe28f564663805ff65beaff196a8205afd6d`.
- Repository remains public;future PDF updates are manual,not automatic.
