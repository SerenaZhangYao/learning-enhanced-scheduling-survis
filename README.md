# learning-enhanced-scheduling-survis

Public SurVis companion repository for the COMP4126 Coursework 3 literature review
`Learning-Enhanced Personnel Scheduling for Flexible Multi-Skilled Workforces`.

## Repository contents

- `src/`: the SurVis web app
- `src/data/generated/`: generated SurVis data used by the public site
- `bib/references.bib`: the bibliography used to build the SurVis data
- `update_data.py`: the local script for regenerating the SurVis data

## Local preview

From the repository root:

```powershell
python -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/
```

The root page redirects to `src/index.html`, so the same setup works for local preview and GitHub Pages.

## GitHub Pages

Expected public URL after enabling Pages from the repository root:

```text
https://lmy12367.github.io/learning-enhanced-scheduling-survis/
```
