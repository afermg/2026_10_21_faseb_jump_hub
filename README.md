# Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools

**Alán F. Muñoz · Carpenter-Shen Lab, Purdue University**

FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

Private source mirror. Compile **slides.tex** with **XeLaTeX**; unowned legacy
`main.tex` is preserved but is not the root. All **20 Overleaf files** are mirrored
unchanged from `361356cb0d96181a05f709e54815a00e8e6ae1cf`; this README and
`.gitignore` are repository-specific additions. The unused JUMP-lite paper PNG
is retained in source history, not the consumed bundle.

## Current deck

**27 pages: 23 main-talk pages and four additional slides.** Narration is planned
for 23 minutes within the 25-minute slot. Stop on the QR page.

- JUMP overview (5): ~58.3 million single-channel TIFF images, alongside the
  existing laboratory and perturbation counts. The public cpg0016 TIFF-count
  table totals 58,267,491; these are neither imaging sites nor cells.
- Applications (18): lysosomal probes, MisLocus, imaging modalities and Squidpy.
- Reality check (19): batch effects, similarity versus mechanism, and the
  experimental-follow-up bottleneck.
- Close: take-homes (20), Thank you (21), References (22), QR (23).
- Additional: JUMP-lite (24), Nahual (25), word2vec (26), cell vectors (27).

JUMP-lite now shows only **8.7 TB → 92 GB (~94× smaller)** for the same image
cohort, using lossy JPEG XL. The original 115 TB JUMP archive would also involve
subset selection. The numerical columns are not an area-proportional chart.

Direct author wording is preserved, including marimo dashboards, individual
tools, plain take-home labels and GSK/NIH MIRA funding scoped to cp_measure and
JUMP-lite. The original Mac-edited workflow remains exact. The detailed Nahual
slide stays hidden. Both vector teaching diagrams use illustrative coordinates,
not measured results; word2vec is an analogy, not the cell-feature algorithm.

## Playback and sources

Play the separate 23.16-second video at **PDF 14 / visible slide 13**, then return
to PDF 15. The two snapshots and text link open the public CC BY 4.0 recording:
<https://doi.org/10.5281/zenodo.23462248>. Video is not embedded in the PDF.

- Image count: <https://github.com/jump-cellpainting/datasets/blob/016e865fa0691244e0860943e41c7d6a88ed2580/stats/cpg0016_source_images_tiff_count.csv>
- Compression comparison: <https://arxiv.org/abs/2608.07632v3>, section 3.1.
- JUMP Hub: <https://broad.io/jump>

## Release holds

Keep this repository **private until explicitly authorized otherwise**.
The presentation **slides.pdf remains absent and ignored**, pending final-slide
approval. PDF upload and public visibility are independent approvals.
The Slides QR reserves
`https://github.com/afermg/2026_10_21_faseb_jump_hub/blob/main/slides.pdf`;
audience access is not yet available. Both 40-mm codes and their payloads remain
unchanged. Review source comments/history before any public release.

Only these three specific vector figure PDFs are permitted source artwork:

- `assets/cell-painting-edited.pdf`
- `assets/vector-interpretability.pdf`
- `assets/word2vec-example.pdf`

These are not presentation-PDF releases. No reuse license is implied for earlier
figures, institutional logos or other third-party material. Scientific qualifications
and full provenance remain in the canonical authoring repository and local notes.
