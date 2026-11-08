MedVES local project page

Open index.html directly in a browser. All figures, styles, scripts, and the
paper PDF are local; no installation is required. The Code link needs Internet.
Keep the Website folder together when moving or sharing the page.

GitHub repository: https://github.com/wxzwxzwxz/MedVES-Demo
Website address after GitHub Pages is enabled:
https://wxzwxzwxz.github.io/MedVES-Demo/

Publish with GitHub Pages
1. Upload index.html, styles.css, script.js, assets/, and .nojekyll to the
   repository root on the main branch. Do not upload the local poster file.
2. Open the repository's Settings > Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Choose main and / (root), then Save.
5. Wait for the Pages deployment to finish, then open the website address.
GitHub Free requires a public repository for Pages. Eligible paid plans can
publish a public Pages site from a private repository.

Subsequent updates from this folder:
git add index.html styles.css script.js assets/medves.bib assets/MedVES.pdf assets/*.webp README.txt .gitignore .nojekyll
git commit -m "Update MedVES project page"
git push origin main

The Code button currently links to this website's source repository. To link
the algorithm implementation instead, change its URL in index.html.

Sources
- Abstract, results, and case descriptions: checked against MedVES_camera_ready.pdf
- Figures: framework_tts.pdf, cases_1.pdf, cases_2.pdf, cases_3.pdf
- Paper: MedVES_camera_ready.pdf
- Layout reference: https://github.com/wxzwxzwxz/CL-NeRF

Editorial note
The supplied PDF displays Anonymous Author(s) and placeholder publication
metadata. The existing page's author order, affiliations, venue, and BibTeX
are retained; they cannot be verified from this anonymized PDF. Amirhossein
Kiani has no affiliation assigned on the existing page. DOI and ISBN
placeholders are intentionally omitted from the citation.

The HTML, CSS, and JavaScript were independently written for this local page.
