---
title: 'EEG-based Decoding of Selective Visual Attention in Superimposed Videos'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wout De Swaef
  - Simon Geirnaert
  - Alexander Bertrand

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-19T00:00:00Z'
doi: '10.48550/arXiv.2409.12562'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: In arXiv

abstract: Selective attention enables humans to efficiently process visual stimuli by enhancing important locations or objects and filtering out irrelevant information. Locating visual attention is a fundamental problem in neuroscience with potential applications in brain-computer interfaces. Conventional paradigms often use synthetic stimuli or static images, but visual stimuli in real life contain smooth and highly irregular dynamics. In this study, we show that these irregular dynamics in natural videos can be decoded from electroencephalography (EEG) signals to perform selective visual attention decoding. To this end, we propose an experimental paradigm in which participants attend to one of two superimposed videos, each showing a center-aligned person performing a stage act. We then train a stimulus-informed decoder to extract EEG signal components that are correlated with the motion patterns of the attended object, and show that this decoder can be used on unseen data to detect which of both objects is attended. Eye movements are also found to be correlated to the motion patterns in the attended video, despite the spatial overlap between the target and the distractor. We further show that these eye movements do not dominantly drive the EEG-based decoding and that complementary information exists in EEG and gaze data. Moreover, our results indicate that EEG also captures information about unattended objects. To our knowledge, this study is the first to explore EEG-based selective visual attention decoding on natural videos, opening new possibilities for experiment design in related fields.

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
url_code: ''
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
