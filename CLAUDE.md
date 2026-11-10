# CLAUDE.md — virexa-tech.com (Virexa AI Technologies)

Corporate site of **Virexa AI Technologies s.r.o.**, the parent company of CasTech (castecheq.com), CasTechLED (castechled.com) and CasTech AI (castechai.com). Owner: Bilal Durmaz. He talks to you in Turkish or English. The site is English only.

## Working rules

- Follow the karpathy-guidelines skill: state assumptions, minimum code, surgical changes, verify before saying "done".
- Never change copy, logo, images or structure on your own initiative. Do only what was asked; mention other issues instead of fixing them.
- Pushing to `main` deploys to production via `.github/workflows/deploy-pages.yml`. For anything bigger than a text fix, work on a branch and open a PR.
- Commit messages: short, English, imperative.

## Stack

- **One self-contained `index.html`** (inline CSS and JS). No framework, no build, no npm. Do not introduce one.
- The workflow publishes tracked files except `*.md`, `.github/`, `tools/`, `scripts/` and Python files, so this file and README stay off the live site. The repo itself is public on GitHub: never commit secrets or drafts.
- `CNAME` (virexa-tech.com) and `.nojekyll`: do not touch.
- Font: **Inter**, self-hosted in `assets/fonts/`. This is the reference font for all brand sites (castecheq, castechled, castechai). No other fonts.
- `index.html` already contains three large base64 PNGs (~680 KB file). Put new images in `assets/` as `.webp` and link them; do not inline more base64.

Preview locally: `python3 -m http.server` in the repo root.

## Content rules

- Three divisions, in this order: **01 CasTech** (casino equipment & hardware → castecheq.com), **02 CasTechLED** (LED screens & digital signage → castechled.com), **03 CasTech AI** (computer vision for casino tables → castechai.com). Keep names, order and links consistent with the division sites.
- Use the **CasTechLED** spelling as on castechled.com. Prefer "LED screen" over "LED display" in new copy.
- Whether "Virexa" stays the umbrella name is still an open decision. Do not rename the company or add alternative brand names.
- CasTech AI is in development. Do not describe it as a launched product here.

## Company details

- Virexa AI Technologies s.r.o., IČO 29716055, Cihlářská 782/10a, Prosek, 190 00 Praha 9. Commercial Register, Municipal Court in Prague, section C, file 451241.
- Sister company: Deniz Trade LLC, Batumi, ID 445613480, Khakhuli Str. No. 3 (since 2021).
- Phones: Prague +420 704 481 975, Batumi +995 555 48 19 75. Email: info@virexa-tech.com. Website inquiries from the brand sites go to sales@virexa-tech.com.
- Background: 22 years of international casino setup and management. Deniz Trade founded in 2021; Virexa and CasTech AI launched in Prague in 2026.
