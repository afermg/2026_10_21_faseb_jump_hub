# JUMP Hub — FASEB presentation source

**Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools**
Alán F. Muñoz — Carpenter-Shen Lab, Purdue University; Carpenter-Singh Lab, Broad Institute
FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

**27 PDF pages: 24 main + 3 additional.** Scheduled narration remains 23 minutes in a 25-minute slot. PDF page numbers are one higher than visible counters.

Use **slides.tex with XeLaTeX**, moloch and Fira Sans. Unowned main.tex is preserved but is not the compilation root.

## Current slide order

| PDF page | Content |
|---|---|
| 1 | Title |
| 2 | What is Cell Painting? |
| 3 | Cell Painting turns images into measurements |
| 4 | Morphological profiling: How to turn images into profiles |
| 5 | Different representations let us compare cells |
| 6 | JUMP: Joint Undertaking for Morphological Profiling |
| 7 | We make JUMP accessible via the JUMP Hub |
| 8 | Tutorials, how-tos and resources |
| 9 | Was my gene or compound tested? |
| 10 | Which perturbations produce related phenotypes? |
| 11 | How does cell morphology change? |
| 12 | Use JUMP as a screen for your phenotype of interest |
| 13 | What do the perturbed cells look like? |
| 14 | Modern tools make image analysis more accessible |
| 15 | Identify and explore cell subpopulations |
| 16 | How do cells in another region compare? |
| 17 | Positive controls contextualize perturbations in both learned and engineered representations |
| 18 | Not just JUMP: Extract morphological profiles from your own images |
| 19 | Applications of JUMP and our tools across biological questions |
| 20 | MisLocus: a single-cell image benchmark |
| 21 | Take-home messages |
| 22 | Thank you |
| 23 | References |
| 24 | JUMP Hub and slides |
| 25 | JUMP-lite: a compact benchmark |
| 26 | Nahual: swap models within one workflow |
| 27 | JUMP-lite: comparing image representations |

## Open-comment revision

Addressed the 12 still-open threads containing new Anne feedback, prioritizing five clear, complete-sentence take-home messages. Resolved review threads and author-only threads were not reworked. No comments were posted, resolved or deleted.

- Original slides 16/17 are combined on PDF14: all six tools, the Cellpose cells/nuclei label, and the example prompt remain together.
- Original word/cell-vector slides are combined on PDF5. Start with control-versus-perturbed comparison; no analogy arithmetic. Blue/non-senescent and orange/senescent label illustrative states, not different cell types.
- The workflow uses consistent structure colors. Its original Mac-edited SVG/PDF and the original word/cell-vector artwork remain unchanged in canonical source, local delivery and Git history. The generated deck now consumes two PNG derivatives instead of those three standalone artwork PDFs.
- The redundant methods/biology transition is absorbed into the Hub introduction. The homepage is cropped and enlarged; no-code guides precede notebooks, and availability wording describes existing experiments.
- Five take-homes cover public JUMP scale, Hub exploration, profiling new images, computational/AI workflows, and biological validation.

Latest direct author edits are preserved, including cell-and-organelle wording, the expanded controls and Applications titles, the Taipale image credit, and Anne in the Carpenter-Shen acknowledgement. The author's ~5x CellProfiler wording is retained, not independently benchmarked in this editorial pass.

## Scientific and delivery boundaries

Control comparison17 still uses the same 5,750 wells: 567 PLK1,10 GJA8 and5,173 negatives. PLK1 is the annotated positive control; GJA8 is a selected phenotype example, not another annotated control. Measured nuclear features and all six fixed UMAPs are unchanged. SubCell remains clipped-input despite its shorter display label; ViT-random is last. No count panel or explanatory footer is restored. Selection is exploratory; removing the count plot does not establish count-independent morphology.

The final published Figure5 comparison27 is separate from that illustration. It retains all original paper rows/values, including CellCount, and the extra-site CellProfiler/count caveat. Workflow25 and Nahual26 remain additional material. No new scientific analysis or additional positive-control validation was performed.

The MisLocus scale and original microscopy panels, JUMP-lite artwork, video and QR payloads are unchanged. Other scientific limits and provenance remain in presenter notes and the canonical source. The workflow/representation drawings are illustrative, not measured data.

The unchanged 23.16-second MP4 is separate from the PDF: play on **PDF15 / visible14**, return to **PDF16**. Its existing public release remains https://doi.org/10.5281/zenodo.23462248 (CC BY4.0).

## Release holds

**Private source repository; no presentation slides.pdf uploaded or pushed.** PDF publication, public repository visibility and a new Mac transfer require separate approval. The Slides QR still targets the absent presentation PDF and is not publicly usable. The three original artwork-PDF names remain the only exceptions in the PDF ignore policy; none are consumed by this revision's generated bundle.

## Verified publication

- Canonical source: `6a369afef960003eda2f646fe9fd041cd486c29d`
- Preserved author head: `3645632e42e94a5a4bc5e13a0e682cdeaf7ea631`
- Overleaf: `ea4f972a893106fc32d384c19caf16861f427c70`
