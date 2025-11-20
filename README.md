# Insper Machine Learning Group — Static Site

This is a small static website scaffold for the Insper Machine Learning Group.

Files

- `index.html` — main site using Bootstrap CDN
- `assets/styles.css` — small custom stylesheet

- `assets/papers.bib` — BibTeX file with the group's references, rendered automatically on the site

- `assets/people/` — per-researcher folders containing `photo.svg` and `profile.json`. Add a new subfolder for each researcher and include their `profile.json` and `photo.svg`.

    Example structure:

    ```text
    assets/people/
    ├─ index.json         # list of researcher ids (order not required)
    ├─ ana_silva/
    │  ├─ profile.json
    │  └─ photo.svg
    ├─ bruno_costa/
    │  ├─ profile.json
    │  └─ photo.svg
    └─ clara_mendes/
         ├─ profile.json
         └─ photo.svg
    ```

    The site loads `assets/people/index.json` and each `profile.json` to render the People section.

Quick preview

Serve the directory and open <http://localhost:8000>

```bash
cd /home/fjayres/dev/misc/web
python3 -m http.server 8000
```

Notes

- Bootstrap is loaded from CDN (no local build required).
- Replace placeholder images and text with real content as needed.
- To deploy: copy files to any static hosting (GitHub Pages, Netlify, S3, etc.).

Papers

- Add new BibTeX entries to `assets/papers.bib`. The site automatically parses and displays them in the `Research Papers` section sorted by year (newest first).
