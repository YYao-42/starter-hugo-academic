---
title: 'Transformer Convolutional Neural Networks for Automated Artifact Detection in Scalp EEG'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Yan Peh
  - admin
  - Justin Dauwels

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-11T00:00:00Z'
doi: '10.1109/EMBC48229.2022.9871916'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 44th Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC)
publication_short: In EMBC

abstract: It is well known that electroencephalograms (EEGs) often contain artifacts due to muscle activity, eye blinks, and various other causes. Detecting such artifacts is an essential first step toward a correct interpretation of EEGs. Although much effort has been devoted to semi-automated and automated artifact detection in EEG, the problem of artifact detection remains challenging. In this paper, we propose a convolutional neural network (CNN) enhanced by transformers using belief matching (BM) loss for automated detection of five types of artifacts --- chewing, electrode pop, eye movement, muscle, and shiver. Specifically, we apply these five detectors at individual EEG channels to distinguish artifacts from background EEG. Next, for each of these five types of artifacts, we combine the output of these channel-wise detectors to detect artifacts in multi-channel EEG segments. These segment-level classifiers can detect specific artifacts with a balanced accuracy (BAC) of 0.947, 0.735, 0.826, 0.857, and 0.655 for chewing, electrode pop, eye movement, muscle, and shiver artifacts, respectively. Finally, we combine the outputs of the five segment-level detectors to perform a combined binary classification (any artifact vs. background). The resulting detector achieves a sensitivity (SEN) of 60.4%, 51.8%, and 35.5%, at a specificity (SPE) of 95%, 97%, and 99%, respectively. This artifact detection module can reject artifact segments while only removing a small fraction of the background EEG, leading to a cleaner EEG for further analysis.

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
