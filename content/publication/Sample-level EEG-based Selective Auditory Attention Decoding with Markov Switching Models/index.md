---
title: 'Sample-level EEG-based Selective Auditory Attention Decoding with Markov Switching Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Simon Geirnaert
  - Tinne Tuytelaars
  - Alexander Bertrand

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-02-13T00:00:00Z'
doi: 'https://arxiv.org/abs/2602.13447'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 'ArXiv'
publication_short: 'ArXiv'

abstract: Selective auditory attention decoding aims to identify the speaker of interest from listeners' neural signals, such as electroencephalography (EEG), in the presence of multiple concurrent speakers. Most existing methods operate at the window level, facing a trade-off between temporal resolution and decoding accuracy. Recent work has shown that hidden Markov model (HMM)-based post-processing can smooth window-level decoder outputs to improve this trade-off. Instead of using a separate smoothing step, we propose to integrate the decoding and smoothing components into a single probabilistic framework using a Markov switching model (MSM). It directly models the relationship between the EEG and speech envelopes under each attention state while incorporating the temporal dynamics of attention. This formulation enables sample-level attention decoding, with model parameters and attention states jointly estimated via the expectation-maximization algorithm. Experimental results demonstrate that this integrated MSM formulation achieves comparable decoding accuracy to HMM post-processing while providing faster attention switch detection. The code for the proposed method is available at https://github.com/YYao-42/MSM.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/YYao-42/MSM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example

---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
