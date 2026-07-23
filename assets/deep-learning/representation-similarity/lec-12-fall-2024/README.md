# Similarity-Based Representation Learning slide excerpts

This directory contains six PNG excerpts from the official MIT OpenCourseWare
deck for *6.7960 Deep Learning, Fall 2024, Lecture 12: Similarity-Based
Representation Learning*.

- Source PDF: [MIT OpenCourseWare Lecture 12 deck](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/mit6_7960_f24_lec12.pdf)
- Exported pages: 5, 12, 34, 45, 47, and 49
- Output files: `slides/slide-05.png`, `slides/slide-12.png`,
  `slides/slide-34.png`, `slides/slide-45.png`, `slides/slide-47.png`, and
  `slides/slide-49.png`
- Output dimensions: 1920 x 1080 pixels
- Renderer: Poppler `pdftoppm` at 72 DPI

The images were rendered with:

```sh
for page in 5 12 34 45 47 49; do
  padded_page="$(printf '%02d' "$page")"
  pdftoppm -f "$page" -l "$page" -singlefile -r 72 -png \
    tmp/pdfs/mit6_7960_f24_lec12.pdf \
    "assets/deep-learning/representation-similarity/lec-12-fall-2024/slides/slide-${padded_page}"
done
```

## Attribution and license caveat

Course material copyright Massachusetts Institute of Technology and provided
by MIT OpenCourseWare. Unless otherwise noted, MIT OpenCourseWare materials are
licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/);
see the [MIT OpenCourseWare Terms of Use](https://ocw.mit.edu/terms/).

That license does not cover every third-party element embedded in the slides.
In particular, page 34 marks its photographs as source unknown, all rights
reserved, and excluded from the Creative Commons license. Reuse of any excerpt
must respect the credit lines and rights notices shown on the source slide; the
presence of a rendered PNG here does not grant additional reuse rights.

Page 49 includes the projection-head diagram credited on the slide to Figure 2
of [Chen et al., *A Simple Framework for Contrastive Learning of Visual
Representations*](https://proceedings.mlr.press/v119/chen20j.html). Consult the
original paper and its rights terms before redistributing that excerpt outside
this study-note context.
