# WAO Engineering Document Register

## Purpose

This register defines project codes, document families, numbering rules, revisions, publication status and canonical filenames used across aitoubahou engineering documentation.

## Project Codes

- ATS — AtlasSAT-16U
- HCD — Hybrid Composite Damping
- UAS — Hexacopter UAS
- UGV — Unmanned Ground Vehicle

## General Document Families

- TN — Technical Note
- ES — Engineering Study

## Revision System

Use `Draft`, `Rev A`, `Rev B` and `Rev C`. A revision identifies a controlled public issue; it does not imply qualification, validation or configuration-control maturity beyond the document itself.

## AtlasSAT-16U Preliminary Register

| Document code | Title | Project | Revision | Status | Date | Public / Private | Canonical filename | Website URL | Repository URL | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| WAO-ATS-1A | Mission Overview | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-1A_Mission-Overview_Draft.pdf` | [TODO] | [TODO] | Verify mission assumptions before release. |
| WAO-ATS-1B | Requirements | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-1B_Requirements_Draft.pdf` | [TODO] | [TODO] | Identify source and verification method for each requirement. |
| WAO-ATS-2A | Orbital Analysis — Document 2A summary | AtlasSAT-16U | RevD3.4 | Engineering release published; website mirror staged in draft PR #3 | 2026-10-27 | Public engineering source / staged website mirror | `AtlasSAT_2A_RevD3_4.pdf` | `assets/documents/atlassat/AtlasSAT_2A_RevD3_4.pdf` (staged) | https://github.com/waitoubahou/AtlasSAT-16U-SWM1/releases/tag/v1.0.0 | Accepted Document 2A; exact binary copy; scientific conclusions unchanged. |
| 2A-1 | Orbital Verification, Coverage & Revisit Analysis | AtlasSAT-16U | RevD3.5 | Engineering release published; website mirror staged in draft PR #3 | 2026-10-27 | Public engineering source / staged website mirror | `AtlasSAT_2A-1_RevD3_5.pdf` | `assets/documents/atlassat/AtlasSAT_2A-1_RevD3_5.pdf` (staged) | https://github.com/waitoubahou/AtlasSAT-16U-SWM1/releases/tag/v1.0.0 | Accepted Document 2A-1; exact binary copy; scientific conclusions unchanged. |
| 2A-2 | Analytical Derivations & Independent Verification | AtlasSAT-16U | v0.2.1 | Engineering release published; website mirror staged in draft PR #3 | 2026-10-27 | Public engineering source / staged website mirror | `AtlasSAT_2A-2_v0.2.1.pdf` | `assets/documents/atlassat/AtlasSAT_2A-2_v0.2.1.pdf` (staged) | https://github.com/waitoubahou/AtlasSAT-16U-SWM1/releases/tag/v1.0.0 | Accepted Document 2A-2; exact binary copy; scientific conclusions unchanged. |
| WAO-ATS-3A | Structural Assembly & Drawings | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-3A_Structural-Assembly-and-Drawings_Draft.pdf` | [TODO] | [TODO] | Confirm publication-safe drawings. |
| WAO-ATS-3B | Static Structural Analysis | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-3B_Static-Structural-Analysis_Draft.pdf` | [TODO] | [TODO] | State load cases, factors and MoS basis separately. |
| WAO-ATS-3C | Modal Analysis | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-3C_Modal-Analysis_Draft.pdf` | [TODO] | [TODO] | Do not release unverified frequency values. |
| WAO-ATS-3D | Thermal Analysis | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-3D_Thermal-Analysis_Draft.pdf` | [TODO] | [TODO] | Verify optical properties and cases. |
| WAO-ATS-4A | System Model | AtlasSAT-16U | Draft | Planned | [DATE] | Private | `WAO-ATS-4A_System-Model_Draft.pdf` | [TODO] | [TODO] | Confirm public artefacts and repository structure. |

## Technical Notes

| Document code | Title | Project | Revision | Status | Date | Public / Private | Canonical filename | Website URL | Repository URL | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| WAO-TN-001 | Preliminary Modal Verification of a 16U Spacecraft Primary Structure | AtlasSAT-16U | Rev A | Provisional | [DATE] | HTML public / PDF pending | `WAO-TN-001_Preliminary-Modal-Verification_Rev-A.pdf` | `technical-notes/wao-tn-001/` | [TODO] | Title and revision require confirmation. |
| WAO-TN-002 | Early-Stage Spacecraft FEA: Boundary Conditions and Deployer-Interface Assumptions | AtlasSAT-16U | Rev A | Provisional | [DATE] | HTML public / PDF pending | `WAO-TN-002_FEA-Boundary-Conditions_Rev-A.pdf` | `technical-notes/wao-tn-002/` | [TODO] | Title and revision require confirmation. |
| WAO-TN-003 | Hybrid Composite Damping — Experimental Methodology and Data Interpretation | Hybrid Composite Damping | Rev A | Provisional | [DATE] | HTML public / PDF pending | `WAO-TN-003_Hybrid-Composite-Damping-Methodology_Rev-A.pdf` | `technical-notes/wao-tn-003/` | [TODO] | Title and revision require confirmation. |

## Engineering Studies

| Document code | Title | Project | Revision | Status | Date | Public / Private | Canonical filename | Website URL | Repository URL | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| WAO-ES-001 | Structural Material Trade Study for Small Spacecraft Primary Structures | General / AtlasSAT-16U | Draft | Planned | [DATE] | Public placeholder | `WAO-ES-001_Structural-Material-Trade-Study_Draft.pdf` | `engineering-studies/wao-es-001/` | [TODO] | No research or results released. |

## Adding a Record

1. Reserve the next applicable code in this register.
2. Add the title, project, revision, status, date, publication state and canonical filename.
3. Add website and repository URLs only when they resolve publicly.
4. Verify every numerical claim, unit, figure and reference before changing status to public.
5. Update the associated HTML register and revision history at the same time.
