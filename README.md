# Modular-NM — Nanoarchitected Metamaterial Geometry Assets  
*(Release Package — No Manuscript Content)*

This repository contains the **design and manufacturing assets** associated with the *Modular Nanoarchitected Metamaterials (Modular-NM)* project.

It intentionally **does not include** the scientific manuscript, LaTeX sources, drafts, or preprints.  
The paper is distributed **only in published PDF form** through appropriate academic channels.

The purpose of this repository is to provide **authoritative geometric and manufacturing artifacts** corresponding to the published work, enabling verification, controlled reuse, and licensed application of the underlying structural system.

---

## What this repository contains

This release includes **non-textual assets only**, specifically:

- **CAD and manufacturing geometry**
  - STL / OBJ / STEP meshes
  - 3MF manufacturing files where applicable
- **Simulation artifacts**
  - Solver input decks and model files (`.inp`, `.mph`) when available
- **Figures**
  - PNG images used in the published PDF (for reference and verification)
- **Reproducibility manifest**
  - `SHA256SUMS.txt` with cryptographic hashes for every file in this release

These files collectively represent the **functional geometric system** described in the paper, independent of any manuscript layout or formatting.

---

## Repository structure

```
Modular-NM/
├── cad/          # Geometry and manufacturing assets (STL / OBJ / STEP / 3MF)
├── simulations/  # Simulation models and solver inputs (when present)
├── images/       # Figures used in the published PDF
├── SHA256SUMS.txt
├── README.md
└── LICENSE
```

---

## About stub files

Some filenames may appear as **plain-text placeholder files** containing the message:

```
NOT INCLUDED IN THIS RELEASE
```

These stubs are included **deliberately** to preserve **exact filename references** used in the published work and internal documentation.

If you encounter a stub:
- It indicates that the corresponding asset exists in the project but is **not part of this public release**
- Replace the stub only if you possess the authorized artifact
- Do **not** treat stubs as usable geometry or simulation inputs

---

## Reproducibility and integrity

- Every file in this repository is listed in `SHA256SUMS.txt`
- Hashes allow verification that:
  - files have not been altered
  - geometry matches the released reference state
- Any modified or derivative file will necessarily invalidate the hash

This mechanism supports **traceability without exposing manuscript source files**.

---

## Scope and intended use

The assets provided here encode a **functional structural system** based on implicit geometry and topology-preserving design rules.  
They are released for:

- non-commercial research
- academic verification
- evaluation of manufacturing feasibility

They are **not** a general-purpose infill library or an unrestricted design kit.

---

## License and commercial use

This repository is released under the  
**Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)** license.

- ✅ Non-commercial research and academic use permitted with attribution  
- ❌ Commercial manufacturing, resale, deployment, or derivative commercial use **not permitted** under this license  

Commercial licensing, manufacturing agreements, or derivative deployments require a **separate written license** from the author.

### Geometry-as-Product Clarification

The subject of this license includes not only expressive content but also **functional geometric configurations**, including but not limited to lattice topology, curvature–lattice coupling, node reinforcement logic, and scale-invariant geometric relationships embodied in the provided CAD and manufacturing files.

For the avoidance of doubt, the **STL, OBJ, STEP, 3MF, and related geometry files constitute the product itself**, not merely illustrative representations. Any reproduction, modification, rescaling, parameter variation, or derivative geometry that preserves substantially similar structural, topological, or functional characteristics is considered a derivative work under this license.

Minor geometric modifications, rescaling, slicer-based regeneration, or format conversion do **not** exempt derivative works from the commercial licensing requirement.

---

## Patent Notice

Certain structural, geometric, and manufacturing aspects of the nanoarchitected metamaterial systems represented in this repository may be subject to existing or future intellectual property protection, including patents or patent applications, in applicable jurisdictions.

No license to any patent rights—express or implied—is granted by distribution of these files, except as explicitly permitted for non-commercial research and academic evaluation under the accompanying license.  
This notice is provided for defensive clarity and does not constitute a public disclosure or waiver of any rights.

---

For questions regarding commercial licensing or authorized use, contact the author directly.
