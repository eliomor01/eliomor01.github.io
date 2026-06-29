# Elio Moreau — Personal Website

This repository contains Elio Moreau's personal website, including a homepage,
research index, blog, downloadable CV, and the project page for:

**“Probing the Geometry of Diffusion Models with the String Method.”**

The site presents the paper, authors, teaser figure, and links to the arXiv version. It is implemented as a lightweight static webpage using HTML, Bulma CSS, and small JavaScript utilities.

---

## Website Overview

Diffusion models define probability distributions over complex data such as images. While these models are highly successful at generation, understanding the **geometry of the learned distribution** remains challenging.

The main site introduces Elio's research interests and links to his CV. The
papers section currently features work introducing a **string-method
perspective** to analyze how samples are connected through a learned
distribution.

The paper studies and compares three regimes:

* **Generative transport**
* **Minimum energy paths**
* **Entropy-aware (tension-regularized) paths**

The results demonstrate that **probabilistic geometry strongly influences the realism and structure of paths in diffusion models.**

---

## Paper

* 📄 Paper PDF: https://arxiv.org/pdf/2602.22122.pdf
* 📚 arXiv page: https://arxiv.org/abs/2602.22122

---

## Authors

* Elio Moreau
* Florentin Coeurdoux
* Grégoire Ferré
* Eric Vanden-Eijnden

Affiliations:

* Capital Fund Management
* Courant Institute of Mathematical Sciences, New York University

---

## Repository Structure

```
.
├── index.html            # Personal homepage
├── papers.html           # Research index
├── blog.html             # Blog index
├── diffusion-strings.html # Diffusion Strings project page
├── static/
│   ├── css/              # Stylesheets (Bulma, custom styles)
│   ├── js/               # JavaScript utilities
│   ├── videos/           # Research videos
│   ├── pdfs/             # Downloadable CV
│   └── images/           # Portrait and figures
```



## Technologies Used

* **HTML5**
* **Bulma CSS framework**
* **KaTeX** for LaTeX rendering
* **FontAwesome / Academicons** for icons
* **jQuery** for lightweight interactivity

---

## Acknowledgements

This webpage template follows common layouts used for **machine learning project pages**, built on top of Bulma and minimal JavaScript components.

---

## License

This repository is intended for **academic and research dissemination**. Please cite the paper if you use or reference this work.
