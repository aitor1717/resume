# resume

Public GitHub Pages site hosting Aitor Bazo's resume (English) and CV (Español) PDFs,
each behind a simple landing page so the link shared externally (LinkedIn Featured,
job applications, portfolio) doesn't end in a literal `.pdf` -- LinkedIn's link
validator rejects those.

- `en/index.html` + `en/bazo_resume.pdf` -- English resume
- `es/index.html` + `es/bazo_cv.pdf` -- CV en español
- `index.html` -- language picker

Source content (editable HTML used to render these PDFs) lives in the private
`recruiterer` repo, not here. To update: re-render the PDF there, copy it into the
matching `en/` or `es/` folder here, commit, push.

Live at: https://aitor1717.github.io/resume/
