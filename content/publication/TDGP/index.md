---
title: "Two-dimensional Bayesian inversion of magnetotelluric data using trans-dimensional Gaussian processes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anandaroop Ray
- Kerry Key

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-03-25T00:00:00Z"
doi: "https://doi.org/10.1093/gji/ggab110"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Geophysical Journal International*
publication_short: In *GJI*

abstract: Bayesian inversion of electromagnetic data produces crucial uncertainty information on inferred subsurface resistivity. Due to their high computational cost, however, Bayesian inverse methods have largely been restricted to computationally expedient 1-D resistivity models. In this study, we successfully demonstrate, for the first time, a fully 2-D, trans-dimensional Bayesian inversion of magnetotelluric (MT) data. We render this problem tractable from a computational standpoint by using a stochastic interpolation algorithm known as a Gaussian process (GP) to achieve a parsimonious parametrization of the model vis-a-vis the dense parameter grids used in numerical forward modelling codes. The GP links a trans-dimensional, parallel tempered Markov chain Monte Carlo sampler, which explores the parsimonious model space, to MARE2DEM, an adaptive finite element forward solver. MARE2DEM computes the model response using a dense parameter mesh with resistivity assigned via the GP model. We demonstrate the new trans-dimensional GP sampler by inverting both synthetic and field MT data for 2-D models of electrical resistivity, with the field data example converging within 10 d on 148 cores, a non-negligible but tractable computational cost. For a field data inversion, our algorithm achieves a parameter reduction of over 32× compared to the fixed parameter grid used for the MARE2DEM regularized inversion. Resistivity probability distributions computed from the ensemble of models produced by the inversion yield credible intervals and interquartile plots that quantitatively show the non-linear 2-D uncertainty in model structure. This uncertainty could then be propagated to other physical properties that impact resistivity including bulk composition, porosity and pore-fluid content.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

