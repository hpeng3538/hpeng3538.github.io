# Hao Peng — academic homepage

Static academic website prepared for GitHub Pages. The homepage and three seminar pages are based on the HTML files supplied by the owner. The photograph and linked PDFs/ZIP were retrieved from the original MIT website at https://math.mit.edu/~hao_peng/ on 2026-09-11.

## Publish with GitHub Pages

1. Sign in to the GitHub account `hpeng3538`.
2. Create the public repository `hpeng3538.github.io` if it does not already exist.
3. Upload the contents of this folder to the repository root; `index.html` must be at the root, not inside another folder. Upload the individual files, not the website ZIP.
4. In **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/ (root)** and save.
5. Wait for the Pages deployment to succeed. The intended address is https://hpeng3538.github.io/.

No build command, package installation, API key, or custom GitHub Actions workflow is needed. `.nojekyll` marks the files as a plain static site.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Edit

- `index.html`: biography, papers, notes, talks, seminars, teaching, and useful links.
- `styles.css`: shared layout, typography, colors, responsive styles, and print styles.
- `AIPF-seminar.html`, `LLC-seminar.html`, `learning-seminar.html`: seminar pages.
- `park.jpeg`: the current owner-provided portrait, displayed with a 4:5 CSS crop. `manhattan.jpg` is the earlier photograph, retained as an unused asset.
- `Hao_Peng_CV.pdf`: the owner-provided CV, linked beside the email address on the homepage. Replace this file with the same filename to update the CV.
- PDF and ZIP files: the linked research and seminar materials. Keep filenames unchanged when updating links.

The original page's Fathom analytics configuration (`CHXLIJWJ`) is retained. The homepage was updated in September 2026 with the owner’s MIT graduation in June 2026 and Princeton Mathematics Instructor appointment starting in September 2026. Minor spelling corrections, semantic page structure, navigation, and responsive layout were applied.

The interests paragraph marked for hiding in the owner’s browser editor is preserved as an HTML comment in `index.html`.

The contact email is `hao.peng@princeton.edu`. The CV supplied by the owner in September 2026 is included without content changes.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/.
