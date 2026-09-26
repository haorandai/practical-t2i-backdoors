# T2I Backdoors project website

**Practical, Generalizable and Robust Backdoor Attacks on Text-to-Image Diffusion Models**

- Paper record: https://openreview.net/forum?id=9XkxVFcAnd
- Displayed status: Manuscript · Submitted to AAAI 2027
- Public website: https://haorandai.com/practical-t2i-backdoors/
- Website repository: https://github.com/haorandai/practical-t2i-backdoors

## Preview and edit

Run `python3 -m http.server 8000` in this directory, then open `http://localhost:8000`.

Edit `index.html` for prose, author metadata, tables and LaTeX; `styles.css` for layout; and `script.js` for math rendering and citation copying. Keep the inline citation synchronized with `citation.bib`.

KaTeX 0.18.9, fonts and license are self-hosted in `assets/vendor/katex`. Use inline `\(...\)` and display `\[...\]` math. Run `node scripts/check-math.cjs` after equation edits. The site has no build step or package installation.

## Evidence and attribution

Content follows the exact PDF linked from the supplied OpenReview record. Numerical comparisons are manuscript-reported results, not an independent reproduction. Figure crops preserve the original panels and labels. Citation for the public arXiv preprint. The results above follow the linked OpenReview manuscript.

Authors and status were verified against the record on September 26, 2026. No equal-contribution or corresponding-author marks were inferred from author order.

The underlying paper and figures belong to their authors. The OpenReview record specifies CC BY 4.0. Page design adapts the authors' OASIS project page. Geist is loaded from Google Fonts with system fallbacks. No source manuscript, private reviews, research checkpoints, or private repository contents are included.

## Hosting

GitHub Pages serves the root of `main`; `.nojekyll` enables direct static-file serving. Asset paths are relative. This website repository is independent of the research-code repository and the personal homepage. Verify deployment status and the public URL after pushing updates.
