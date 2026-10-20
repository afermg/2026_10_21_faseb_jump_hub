# JUMP Hub — FASEB presentation source

**Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools**
Alán F. Muñoz — Carpenter-Shen Lab, Purdue University; Carpenter-Singh Lab, Broad Institute
FASEB: Organelle Cross-Talk in Cellular Homeostasis · 21 October 2026

Use **`slides.tex` with XeLaTeX**, moloch and Fira Sans. Legacy, unowned `main.tex` is preserved but is **not** the compilation root.

- **29 PDF pages:27main-talk +2additional**,23-minute narration in a25-minute slot.
- Overleaf commit: `e8a6a90b59948cd3e1739364091c3345e11430c5`
- Canonical source commit: `e27cb6e045a2c44a72dc3b1a6ef1e9a4ff66568a`
- Direct author changes through `dee36e090c8968d4f68303a4c6d990ddc09b72c4` preserved.

## Current slide order

| PDF page | Content |
|---|---|
| 5–7 | Word2vec → cell vectors → JUMP |
| 10 | Tutorials,how-tos and resources |
| 16–19 | Modern tools → AI → notebook(play18,return19) |
| 20 | **Positive controls contextualize the perturbations** |
| 21 | Extract morphological profiles from your own images |
| 22–23 | Applications → MisLocus |
| 24–27 | Take-homes → Thanks/funding → References → QR closing |
| 28–29 | Additional JUMP-lite → Nahual |

MisLocus23 is labeled **Unpublished data (preprint coming soon)**, with the author-removed personal/lab caption absent and the small adaptation footer retained, with no displayed Hugging Face link. Its scale sentence reports approximately3million cells,1,541reference/variant alleles and282genes,excluding controls; source documentation is retained as internal provenance. The two original LZTR1 image panels are unchanged.

Page20 compares **PLK1 and GJA8** across5,750matched wells:567PLK1,10GJA8 and5,173negative controls. PLK1 is the annotated positive control;GJA8 is a selected phenotype example,not an annotated control. A large measured nuclear-area/eccentricity plot accompanies six fixed UMAPs:CellProfiler+Harmony,MorphEm,DINOv2,OpenPhenom,SubCell and ViT-random last. Cell count and standard SubCell are not displayed. The labeled zoom complements the full-range feature plot;UMAP overlap is retained. Selection is exploratory,not a model ranking or evidence of count-independent morphology.

Reality check and the six separate model slides are not exported. All four visible “Adapted from Muñoz,Cell Circuits(2024)” credits are removed; provenance is retained elsewhere. Exact Mac workflow,word2vec,JUMP-lite artwork,microscopy pixels,video and both40-mm QR payloads are preserved. The cell schematic remains illustrative despite removal of its visible disclaimer; the axis reads **Granularity Mito Channel**.

All six toolbox names remain:Cellpose,Spotiflow,Trackastra,Ultrack,cp_measure,marimo. Use **Fast**,not Fastest; the retained>2×CellProfiler claim is independently unvalidated. Full scientific qualifications,editable figures and analysis evidence are in the canonical repository and local delivery,not this source-only mirror.

## Release holds

**Private repository; no presentation `slides.pdf` tracked or uploaded.** Public PDF release,repository visibility change and new Mac transfer require separate approval. The Slides QR still points to the absent presentation PDF in this private repository and is not publicly usable yet.

Only three artwork PDFs are tracked:`assets/vector-interpretability.pdf`,`assets/cell-painting-edited.pdf`,`assets/word2vec-example.pdf`.

The unchanged23.16-second MP4 is separate from the PDF:<https://doi.org/10.5281/zenodo.23462248>,CC BY4.0.

Latest display edit:the SubCell label no longer includes “(clipped)”,but its underlying clipped-input profiles are unchanged. ViT-random is last. The uv environments/dependencies reference is removed. The updated ML heading,preprint note and cp_measure/JUMP-lite funding credit preserve the latest direct author edits. Controls20/extraction21 share30+45seconds,keeping1380seconds total. No additional positive-control validation results were added in this layout-only revision.
