# fixtock.com (GitHub Pages)

Copy everything in this folder into the root of the GitHub Pages repo. Keep your existing `CNAME` file.

- `index.html`: the home page (all CSS and JS are inline; only the Inter font loads from Google Fonts).
- `assets/screens/`: app screenshots. To add more, export a 720-px-wide WebP and PNG, and reuse a `.phone` block.
- `legal/`: Privacy, Terms and EULA pages plus the PDFs (rebuild them with `legal_ui/build_legal.py`).
- `privacy.html`: redirects the old link to `legal/privacy.html`, so existing store links keep working.
- `.nojekyll`: tells GitHub to serve the files as they are.

Store listing URLs: https://fixtock.com/legal/privacy.html · https://fixtock.com/legal/terms.html · https://fixtock.com/legal/eula.html
