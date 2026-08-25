# Artifact-to-Finding Promotion - Version 1.1 Release Package

This folder contains the source, distribution, and publication-support files for Version 1.1. The version was published on Zenodo on August 25, 2026 and is linked to the published Version 1.0 record.

## Published Record

- **Version 1.1 DOI:** [10.5281/zenodo.22102862](https://doi.org/10.5281/zenodo.22102862)
- **Version 1.0 DOI:** [10.5281/zenodo.21543521](https://doi.org/10.5281/zenodo.21543521)
- **Publication date:** August 25, 2026

Version 1.0 remains an immutable published record.

## Folder Contents

- `artifact-promotion-working-paper-v1.1.md` is the canonical Markdown text.
- `Watson_Artifact-to-Finding_Promotion_Working_Paper_v1.1.docx` is the editable production source.
- `Watson_Artifact-to-Finding_Promotion_Working_Paper_v1.1.pdf` is the reading and distribution rendition.
- `LICENSE.md` records the licence.
- `ZENODO_METADATA.md` records the publication metadata.

DOCX build command from the repository root:

`python methodologies/artifact-to-finding-promotion/tools/build_artifact_promotion_docx.py`

PDF render command:

`"C:\Program Files\LibreOffice\program\soffice.com" --headless --convert-to pdf --outdir "methodologies\artifact-to-finding-promotion\deposit\v1.1" "methodologies\artifact-to-finding-promotion\deposit\v1.1\Watson_Artifact-to-Finding_Promotion_Working_Paper_v1.1.docx"`

The DOCX inherits the Zemi Method Version 1.1 document system: Cambria typography, page geometry, title and metadata treatment, revision and contents pages, heading hierarchy, running header, and footer pagination. The older ReportLab builder is retained only for reproducing the published Version 1.0 presentation and is not the Version 1.1 publication path.
