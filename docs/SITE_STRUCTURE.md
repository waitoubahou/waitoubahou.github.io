# Site Structure

## Public Navigation

- Engineering Work
- Technical Notes
- About
- CV
- Contact

Engineering Studies remain discoverable from the homepage and Technical Notes but are not a top-level navigation item until the archive contains completed studies.

## Page Families

- `/index.html` — compact archive index and selected work.
- `/engineering-work/` — full project register.
- `/projects/<project-slug>/` — project overviews, methods, evidence, limitations and artefacts.
- `/technical-notes/` — numbered document register.
- `/technical-notes/<document-code>/` — focused technical-document pages.
- `/engineering-studies/` — longer-form study register.
- `/engineering-studies/<document-code>/` — study pages.
- `/about/`, `/cv/`, `/contact/` — supporting profile pages.

## URL Policy

All internal links are relative so the site works locally, at a GitHub Pages project path such as `/website/`, and later at a custom domain. Do not add root-relative internal URLs unless the hosting model changes.

## Content Growth

New projects and documents use independent directory slugs, so the archive can grow without changing the global navigation. Add document records to `DOCUMENT_REGISTER.md` before public release.

## Asset Policy

- Project images: `assets/images/projects/`
- UI assets and future favicon: `assets/images/ui/`
- CV: `assets/documents/cv/`
- Project PDFs: project-specific subdirectories under `assets/documents/`
- Technical-note PDFs: `assets/documents/technical-notes/`
- Engineering-study PDFs: `assets/documents/engineering-studies/`
- Other downloadable files: `assets/files/`

Missing files must be shown as unavailable text, not published as broken links.
