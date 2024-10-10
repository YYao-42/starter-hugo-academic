---
title: 'Identifying Temporal Correlations Between Natural Single-shot Videos and EEG Signals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Simon Geirnaert
  - admin
  - Tom Francart
  - Alexander Bertrand

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-18T00:00:00Z'
doi: '10.1109/JBHI.2024.3462991'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Journal of Biomedical and Health Informatics
publication_short: In JBHI

abstract: Various new brain-computer interface technologies or neuroscience applications require decoding stimulus-following neural responses to natural stimuli such as speech and video from, e.g., electroencephalography (EEG) signals. In this context, generalized canonical correlation analysis (GCCA) is often used as a group analysis technique, which allows the extraction of correlated signal components from the neural activity of multiple subjects attending to the same stimulus. GCCA can be used to improve the signal-to-noise ratio of the stimulus-following neural responses relative to all other irrelevant (non-)neural activity, or to quantify the correlated neural activity across multiple subjects in a group-wise coherence metric. However, the traditional GCCA technique is stimulus-unaware, no information about the stimulus is used to estimate the correlated components from the neural data of several subjects. Therefore, the GCCA technique might fail to extract relevant correlated signal components in practical situations where the amount of information is limited, for example, because of a limited amount of training data or group size. This motivates a new stimulus-informed GCCA (SI-GCCA) framework that allows taking the stimulus into account to extract the correlated components. We show that SI-GCCA outperforms GCCA in various practical settings, for both auditory and visual stimuli. Moreover, we showcase how SI-GCCA can be used to steer the estimation of the components towards the stimulus. As such, SI-GCCA substantially improves upon GCCA for various purposes, ranging from preprocessing to quantifying attention.

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
url_code: 'https://github.com/AlexanderBertrandLab/si-gcca'
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
