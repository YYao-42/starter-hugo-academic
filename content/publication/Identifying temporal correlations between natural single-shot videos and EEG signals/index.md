---
title: 'Identifying Temporal Correlations Between Natural Single-shot Videos and EEG Signals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Axel Stebner
  - Tinne Tuytelaars
  - Simon Geirnaert
  - Alexander Bertrand

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-02-07T00:00:00Z'
doi: '10.1088/1741-2552/ad2333'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Neural Engineering
publication_short: In JNE

abstract: Electroencephalography (EEG) is a widely used technology for recording brain activity in brain-computer interface (BCI) research, where understanding the encoding-decoding relationship between stimuli and neural responses is a fundamental challenge. Recently, there is a growing interest in encoding-decoding natural stimuli in a single-trial setting, as opposed to traditional BCI literature where multi-trial presentations of synthetic stimuli are commonplace. While EEG responses to natural speech have been extensively studied, such stimulus-following EEG responses to natural video footage remain underexplored. We collect a new EEG dataset with subjects passively viewing a film clip and extract a few video features that have been found to be temporally correlated with EEG signals. However, our analysis reveals that these correlations are mainly driven by shot cuts in the video. To avoid the confounds related to shot cuts, we construct another EEG dataset with natural single-shot videos as stimuli and propose a new set of object-based features. We demonstrate that previous video features lack robustness in capturing the coupling with EEG signals in the absence of shot cuts, and that the proposed object-based features exhibit significantly higher correlations. Furthermore, we show that the correlations obtained with these proposed features are not dominantly driven by eye movements. Additionally, we quantitatively verify the superiority of the proposed features in a match-mismatch task. Finally, we evaluate to what extent these proposed features explain the variance in coherent stimulus responses across subjects. This work provides valuable insights into feature design for video-EEG analysis and paves the way for applications such as visual attention decoding.

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
url_code: 'https://github.com/YYao-42/Identifying-Temporal-Correlations-Between-Natural-Single-shot-Videos-and-EEG-Signals'
url_dataset: 'https://zenodo.org/records/10512414'
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
