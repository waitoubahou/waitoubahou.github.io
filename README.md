# Wassim Ait Oubahou Engineering Archive

A static public front end for Wassim Ait Oubahou's engineering work, technical notes and supporting documents. The V1 site is deliberately restrained, documentation-oriented and honest about unavailable or unverified material.

## Technology

- Semantic HTML5
- One CSS stylesheet: `assets/css/main.css`
- No JavaScript
- Self-hosted IBM Plex Serif, Sans and Mono fonts
- No frontend framework, package manager, tracker or build step

## Local Preview

From this directory, run:

```bash
python -m http.server 8000
```

Open `http://localhost:8000/`. Do not open the HTML files directly from disk when checking relative directory URLs.

## GitHub Pages Deployment

1. Open the `waitoubahou/waitoubahou.github.io` repository.
2. Copy the contents of this directory to the repository root so `index.html` is at the root.
3. Commit and push the files to the default branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the default branch and the `/(root)` folder, then save.
7. Wait for GitHub Pages to publish the site at `https://waitoubahou.github.io/`.
8. Test navigation, nested project pages and the 404 page from the published URL.

All internal URLs are relative.

## Directory Structure

```text
.
├── index.html
├── engineering-work/
├── projects/
│   ├── atlassat-16u/
│   ├── hybrid-composite-damping/
│   ├── hexacopter-uas/
│   └── ugv/
├── technical-notes/
│   ├── wao-tn-001/
│   ├── wao-tn-002/
│   └── wao-tn-003/
├── engineering-studies/
│   └── wao-es-001/
├── about/
├── cv/
├── contact/
├── assets/
│   ├── css/
│   ├── fonts/
│   ├── icons/
│   ├── images/
│   ├── documents/
│   └── files/
├── docs/
├── 404.html
└── README.md
```

## Add a Project

1. Add a directory at `projects/<project-slug>/index.html`.
2. Reuse the established semantic header, project metadata and section structure.
3. Add the project to `engineering-work/index.html`; add it to the homepage only if it is selected work.
4. Put verified imagery in `assets/images/projects/` and public documents in a project-specific `assets/documents/` directory.
5. Use visible TODOs instead of inventing missing requirements, methods or results.

## Add a Technical Note

1. Reserve the next `WAO-TN-###` code in `docs/DOCUMENT_REGISTER.md`.
2. Add `technical-notes/<document-code-lowercase>/index.html`.
3. Add the note to `technical-notes/index.html` and, if recent, the homepage register.
4. Add a PDF only after its revision, claims, references and publication status have been checked.

## Add an Engineering Study

1. Reserve the next `WAO-ES-###` code in `docs/DOCUMENT_REGISTER.md`.
2. Add `engineering-studies/<document-code-lowercase>/index.html`.
3. Change the study status from planned only when substantive content and evidence are ready.

## Update the CV

1. Add `assets/documents/cv/Wassim_Ait_Oubahou_CV.pdf`.
2. Replace the unavailable message in `cv/index.html` with the prepared PDF link shown in its HTML comment.
3. Update the displayed date and document register if the CV is to be revision-controlled.

## Document Numbering

`docs/DOCUMENT_REGISTER.md` is the canonical record of project codes, document codes, revisions, status and filenames. `docs/CONTENT_GUIDE.md` defines publication language and evidence rules.

## Future Custom Domain

For `aitoubahou.com`:

1. Configure the domain's DNS using the current GitHub Pages guidance.
2. Set the custom domain in **Settings → Pages** and enable HTTPS.
3. Add a root-level `CNAME` file containing `aitoubahou.com` if GitHub does not create it automatically.
4. Add canonical URLs, `og:url`, social-preview images and a favicon to each page.
5. Replace the V1 email only when `wassim@aitoubahou.com` is active and monitored.
6. Recheck all internal and document links after migration.

## Pre-Publication Checklist

- Replace all `[DATE]` and required `[TODO]` fields.
- Supply and validate public PDF artefacts before enabling their links.
- Recheck GitHub and LinkedIn URLs if profile handles change.
- Verify AtlasSAT orbit and every other numerical value.
- Confirm Hybrid Composite Damping project status.
- Add publication-safe technical figures with dimensions, alt text and captions.
- Add canonical and social-preview metadata once final imagery is available.
