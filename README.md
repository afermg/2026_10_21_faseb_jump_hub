# Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools

**Alán F. Muñoz · Carpenter-Shen Lab, Purdue University**

FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

Private source mirror. Compile **slides.tex** with **XeLaTeX**; unowned legacy
`main.tex` is preserved but is not the root. All **21 Overleaf files** are mirrored
unchanged from `bab3b8064d6cabaf81d5fee89ef0e73c725e43c4`; this README and
`.gitignore` are repository-specific additions. The original right-hand
JUMP-lite nested-square PNG is included again as consumed artwork.

## Current deck

**27 pages: 22 main-talk pages and five additional slides.** Narration is planned
for 23 minutes within the 25-minute slot. Stop on the QR page.

- JUMP overview (5): ~58.3 million single-channel TIFF images, alongside the
  existing laboratory and perturbation counts. The public cpg0016 TIFF-count
  table totals 58,267,491; these are neither imaging sites nor cells.
- Applications (18): lysosomal probes, MisLocus, imaging modalities and Squidpy.
- Close: take-homes (19), Thank you (20), References (21), QR (22).
- Additional: JUMP-lite (23), reality check (24), Nahual (25), word2vec (26),
  cell vectors (27). The reality-check content remains unchanged.
- The image-count citation is with the other sources on References, not the
  JUMP overview. Its former 30-second reality-check slot now gives the overview
  time to explain the image count and units; the total plan remains 23 minutes.

JUMP-lite now shows the original **nested-square storage graphic**. It includes
both subset selection and compression, with the full 115 TB release as context.
The footer isolates **8.7 TB → 92 GB (~94× smaller)** for the same image cohort,
using lossy JPEG XL. No pixel values or proportions of the artwork were changed.

Direct author wording is preserved, including marimo dashboards, individual
tools, plain take-home labels and GSK/NIH MIRA funding scoped to cp_measure and
JUMP-lite. Thank you (PDF 20) now names both **Carpenter-Singh Lab** and
**Carpenter-Shen Lab**; the presenter explains the move orally. The latest author
application credits, including **Tim Treis, Theis Lab, Helmholtz-Munich**, and
removal of the visible uv row/demo-text link are preserved.
The original Mac-edited workflow remains exact. The detailed Nahual
slide stays hidden. Both vector teaching diagrams use illustrative coordinates,
not measured results; word2vec is an analogy, not the cell-feature algorithm.

## Playback and sources

Play the separate 23.16-second video at **PDF 14 / visible slide 13**, then return
to PDF 15. The two snapshot-image links open the public CC BY 4.0 recording:
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
