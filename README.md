# PET — SUVR + Partial-Volume Correction (PETPVE12) on OASIS-3
[![License](https://img.shields.io/github/license/andraderenew/pet_suvr-pvc_spm_petpve12_oasis3)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.XXXXXXX-blue)](#cite-this-work)
[![Pages](https://img.shields.io/website?url=https%3A%2F%2Fandraderenew.github.io%2Fpet_suvr-pvc_spm_petpve12_oasis3%2F)](https://andraderenew.github.io/pet_suvr-pvc_spm_petpve12_oasis3/)
![Release](https://img.shields.io/github/v/release/andraderenew/pet_suvr-pvc_spm_petpve12_oasis3?include_prereleases)
![Last commit](https://img.shields.io/github/last-commit/andraderenew/pet_suvr-pvc_spm_petpve12_oasis3)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5627--579X-A6CE39)](https://orcid.org/0000-0001-5627-579X)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4)](https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ)

**One-line:** Compute regional SUVRs and show the effect of partial-volume correction on a tiny OASIS-3 PET subset.

## Overview
Compute **SUVR** and show the effect of **partial-volume correction (PVC)** with **PETPVE12** on a tiny **OASIS-3** PET subset.

## Data & subset
See `DATA_SOURCES.md`. Suggested: <3 scans> of a single tracer (FDG or AV45) to start.

## Pipeline
SPM coreg/normalize (PET→T1) → SUVR (define reference region) → PETPVE12 (PVC) → compare SUVR vs SUVR+PVC (tables & maps).

## Results (to be filled)
- SUVR maps (with vs without PVC)  
- Regional SUVR change table

## Reproducibility
- Versions: see `env/TOOL_VERSIONS.md`  
- Steps: “Coreg/normalize → SUVR → PVC → regional table → figures.”  
- Limits: tracer-specific effects; tiny subset

## Cite this work
See `CITATION.cff` (add DOI after first Release).
