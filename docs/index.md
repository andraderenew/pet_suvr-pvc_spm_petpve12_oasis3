# PET: SUVR + Partial-Volume Correction (PETPVE12) on OASIS-3

**Goal:** Compute regional SUVRs and show the impact of partial-volume correction (PVC) on a tiny OASIS-3 PET subset.

---

## Snapshot
- **Dataset:** OASIS-3 (PET + MRI) — tiny subset
- **Local subset:** <N scans> · **Disk:** download minimally (a few scans)
- **Tools:** SPM12 (coreg/normalize), PETPVE12 (PVC)
- **Status:** <planned / in progress / complete>
- **Last updated:** <YYYY-MM-DD>

---

## Data
- **Source & DUA:** Link to OASIS-3; note access steps.  
- **What I downloaded:** tracer, reference region choice.  
- **Layout:** PET/T1 per subject.

---

## Pipeline (high-level)
1) Coregister PET→T1; normalize  
2) Compute SUVR (define reference region)  
3) PVC with PETPVE12; recompute regional values  
4) Compare SUVR vs SUVR+PVC

---

## Results (to be filled)
- Figure: SUVR maps (with vs without PVC)  
- Table: regional SUVR changes

---

## Reproducibility
- Versions in `env/TOOL_VERSIONS.md`.  
- Steps: “Coreg/normalize → SUVR → PVC → regional table → figures.”  
- Limitations: tiny subset, tracer-specific effects.

---

**Author:** Rene Andrade Rey · 🧪 ORCID: https://orcid.org/0000-0001-5627-579X · 🌐 Scholar: https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ
