# Uncovering biological relationships through morphological profiling: The JUMP-Cell Painting dataset and tools

**Alán F. Muñoz** · Carpenter-Shen Lab, Purdue University

**21 October 2026** · FASEB: Organelle Cross-Talk in Cellular Homeostasis

Slides for the FASEB 2026 talk, following the date-prefixed naming convention of
my other talks and posters. This repository mirrors the current Overleaf source.

## Private editing stage — no PDF release yet

**Keep this repository private until the presenter explicitly instructs otherwise.**
**Do not commit or push a PDF until the presenter explicitly approves the final slides.**
These are separate approval gates; approval for one does not imply the other.

The final PDF's reserved viewer URL is:

https://github.com/afermg/2026_10_21_faseb_jump_hub/blob/main/slides.pdf

The dedicated QR slide already contains a code for that URL. `slides.pdf` is intentionally
absent and ignored by Git while editing. The QR will not provide public audience
access until the approved PDF is uploaded and public visibility is separately
authorized. No automatic PDF publication or visibility change is configured.

## Source and build

- `slides.org`: authoring source mirrored from Overleaf.
- `slides.tex`: **current presentation root**, compiled with XeLaTeX.
- `assets/`: figures, screenshots, logos and two QR images.
- `main.tex`: preserved legacy/unowned Overleaf file, **not** the current root.

Current Overleaf snapshot: `ea8d33b12ec3f17dd42843d635d1fd98278d9e02`.
All 19 Overleaf files are mirrored unchanged; this README and `.gitignore` are
repository-specific additions. The deck contains 23 pages, with a 23-minute
narration plan within the 25-minute slot. The toolbox on page 15 includes marimo
and uv. Page 16 introduces Nahual with DINOv2/DINOv3, OpenPhenom, MorphEm,
Cellpose, StarDist and Trackastra as documented model examples. cp_measure and
JUMP-lite follow. Gratitude is on page 21, references on 22, and the final QR
page is 23. The historical speed-benchmark citation is removed.

The ORF card shows ~12,600 genes without the construct count; the dataset
introduction identifies 12 acquiring laboratories. The video remains a separate
offline companion and is also public on
[Zenodo](https://doi.org/10.5281/zenodo.23462248) under CC BY 4.0. Both snapshot
images on PDF pages 13/14 and the demo text link on page 14 open the recording.
Page 23 contains only JUMP Hub and Slides (PDF), with two 40-mm QR codes and the
visible shortlink `broad.io/jump`. Direct Overleaf edits through `25527fb`,
including the revised wording and collaborator credits, are preserved.
Only the MP4 was uploaded to Zenodo; the PDF and repository-publication gates
above remain unchanged.

Continue editing through the established Org-to-Overleaf pipeline. Direct
Overleaf edits take content priority; preserve and reconcile them before
publishing. Refresh this source mirror after publication. There is no automatic
GitHub synchronization.

Compile `slides.tex` twice with XeLaTeX and the required Beamer/Fira packages for
local previews. Generating a local preview does not authorize a PDF upload.
Before any later public release, review editorial comments and source history
for private operational information. The original authoring and Overleaf
projects must remain private unless separately authorized.

## Credits

Scientific references and tool links appear immediately before the final QR slide.
Illustration/logo credits are no longer displayed there, at the presenter's
request. Their provenance remains in the private authoring repository's
[`docs/provenance.md`](https://github.com/afermg/org-overleaf-sync/blob/main/docs/provenance.md)
and retained Git history. Third-party images, logos and tools retain their
respective rights and licences; no blanket licence is applied here.
