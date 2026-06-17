# PyAI Tracker — Python → USA AI Olympiad

A clean, offline-first **spaced-repetition learning tracker** that takes you from Python basics to
USA AI Olympiad (USAAIO) / IOAI level, with a **heavy linear-algebra core** and **runnable Google Colab notebooks**.

Built on the same engine as the Lumen study tracker: **Tracks → Units → checkable Submodules**, progress
bars, a spaced-repetition Review Queue (1 / 3 / 7 / 16 / 35-day intervals), per-unit vocabulary
resurfacing, `localStorage` persistence, light/dark themes, optional browser notifications, and per-submodule
section tags + curated **free** resource links.

## Open it
Just open `index.html` — it's a single self-contained file (no build step). Deploy by serving the repo root
as a static site (GitHub Pages, Vercel, Netlify, …).

## Tracks
1. **Python Foundations** — Python docs · Automate the Boring Stuff · Fluent Python
2. **Data Structures & Algorithms** — CLRS · Competitive Programmer's Handbook · USACO Guide
3. **Scientific Python** — Python Data Science Handbook · NumPy / pandas / Matplotlib
4. **Mathematics for ML (Linear Algebra core)** — 3 linear-algebra unit-sets + calculus, probability,
   optimization · *Mathematics for ML* (Deisenroth) · Strang / MIT 18.06 · 3Blue1Brown
5. **Classical Machine Learning** — Hands-On ML (Géron) · ISLR · CS229
6. **Deep Learning** — d2l.ai · Goodfellow · CS231n · Karpathy Zero-to-Hero
7. **AI Olympiad Track** — USAAIO & IOAI official syllabus & materials

## Notebooks (runnable in Colab)
`nb_python_basics`, `nb_numpy`, `nb_pandas`, `nb_linear_algebra`, `nb_matrix_ops_eigen`, `nb_pca`,
`nb_gradient_descent`, `nb_linear_regression`, `nb_logistic_regression`, `nb_knn`, `nb_kmeans`,
`nb_neural_net_from_scratch`, `nb_pytorch_mlp`, `nb_cnn_pytorch`, `nb_transformer_intro`.

The in-app **▶ Open in Colab** buttons link to:
```
https://colab.research.google.com/github/wilson-stackabacus/python-ai-tracker/blob/main/<notebook>.ipynb
```
So this repo should live at **`wilson-stackabacus/python-ai-tracker`** (branch `main`) for the Colab links to resolve.

## Privacy
All progress is stored in your browser's `localStorage`. No account, no server, no tracking.
