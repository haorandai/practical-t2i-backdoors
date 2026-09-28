# Practical, Generalizable and Robust Backdoor Attacks on Text-to-Image Diffusion Models

**Project page:** [haorandai.com/practical-t2i-backdoors](https://haorandai.com/practical-t2i-backdoors/) · **Paper:** [arXiv 2508.01605](https://arxiv.org/abs/2508.01605) · **Code:** [haorandai/backdoorT2I](https://github.com/haorandai/backdoorT2I)

A backdoor attack on text-to-image diffusion models that uses natural, readable trigger prompts and CLIP-guided image preparation. It is evaluated on SD 1.4, SDXL and FLUX.1, each fine-tuned separately, and against several existing defenses. This repository holds the source of the project page.

## Citation

```bibtex
@misc{dai2025practical,
  title = {Practical, Generalizable and Robust Backdoor Attacks on Text-to-Image Diffusion Models},
  author = {Haoran Dai and Jiawen Wang and Ruo Yang and Manali Sharma and Zhonghao Liao and Yuan Hong and Binghui Wang},
  year = {2025},
  eprint = {2508.01605},
  archivePrefix = {arXiv},
  primaryClass = {cs.CR},
  url = {https://arxiv.org/abs/2508.01605}
}
```

## Editing the page

The site is static: no build step or package installation.

- Preview with `python3 -m http.server 8000`, then open `http://localhost:8000`.
- `index.html` holds the prose, author list, tables and LaTeX; `styles.css` the layout; `script.js` math rendering and citation copying. Keep the inline citation in sync with `citation.bib`.
- KaTeX is self-hosted in `assets/vendor/katex`. Use `\(...\)` for inline and `\[...\]` for display math, and run `node scripts/check-math.cjs` after editing equations.

GitHub Pages serves the root of `main`.

## Credits

Every result and figure on the page comes from the arXiv preprint (v1), which the authors distribute under CC BY-NC-ND 4.0; figures are reproduced with attribution. Numbers are the ones reported in the paper, not an independent reproduction.
