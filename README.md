# JUMP Hub — FASEB presentation source

**Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools**
Alán F. Muñoz — Carpenter-Shen Lab, Purdue University; Carpenter-Singh Lab, Broad Institute
FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

Use **`slides.tex` with XeLaTeX**, moloch and Fira Sans. Legacy, unowned `main.tex` is preserved but is **not** the compilation root.

- **29 PDF pages:26main-talk +3additional**,23-minute narration in a25-minute slot.
- Overleaf commit: `17f5305fb3082b4a288022e530168ace46730ed3`
- Canonical source commit: `7eb09b9f4fae1cd86c64770e2b2af4da0889ec90`
- Direct author changes through `28f4ae2da174fbafbac24520f561cbb7b7691f71` preserved.

## Current slide order

| PDF page | Content |
|---|---|
| 5–7 | Word2vec → clearer cell vectors → JUMP |
| 10 | Tutorials,how-tos and resources beyond this talk |
| 16–18 | Modern tools → AI assistants → interactive notebook |
| 18–19 | Play separate MP4 at18(visible17);return to19 |
| 21–22 | Applications → **MisLocus,in the main talk** |
| 24–26 | Acknowledgements/funding → References → QR closing |
| 27–29 | Additional JUMP-lite → Nahual → combined control figure |

MisLocus22 is labeled **Unpublished data**, retaining Johan Fredin/Carpenter-Shen/Purdue attribution, with no displayed Hugging Face link. Its scale sentence reports approximately3million cells,1,541reference/variant alleles and282genes,excluding controls; source documentation is retained as internal provenance. The two original LZTR1 image panels are unchanged.

Page29 contains **one seven-panel figure**:20PLK1positive-control wells and105negative controls in each panel. MYT1 is excluded from fitting/display. Six deep-learning collections use fixed UMAP; the released Harmony/PCA/arm-corrected CellProfiler representation uses a clearly labeled PCA view. CellProfiler derives from interpretable measurements,but transformed axes are not individual feature values. Same wells do not imply identical preprocessing; axes are independent. Post-hoc positive-control selection is illustrative,not a model-ranking benchmark.

Reality check and the six separate model slides are not exported. All four visible “Adapted from Muñoz,Cell Circuits(2024)” credits are removed; provenance is retained elsewhere. Exact Mac workflow,word2vec,JUMP-lite artwork,microscopy pixels,video and both40-mm QR payloads are preserved. The cell schematic remains illustrative despite removal of its visible disclaimer; the axis reads **Granularity Mito Channel**.

All six toolbox names remain:Cellpose,Spotiflow,Trackastra,Ultrack,cp_measure,marimo. Use **Fast**,not Fastest; the retained>2×CellProfiler claim is independently unvalidated. Full scientific qualifications,editable figures and analysis evidence are in the canonical repository and local delivery,not this source-only mirror.

## Release holds

**Private repository; no presentation `slides.pdf` tracked or uploaded.** Public PDF release,repository visibility change and new Mac transfer require separate approval. The Slides QR still points to the absent presentation PDF in this private repository and is not publicly usable yet.

Only three artwork PDFs are tracked:`assets/vector-interpretability.pdf`,`assets/cell-painting-edited.pdf`,`assets/word2vec-example.pdf`.

The unchanged23.16-second MP4 is separate from the PDF:<https://doi.org/10.5281/zenodo.23462248>,CC BY4.0.
