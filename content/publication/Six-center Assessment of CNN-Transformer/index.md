---
title: 'Six-center Assessment of CNN-Transformer with Belief Matching Loss for Patient-independent Seizure Detection in EEG'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Yan Peh
  - Prasanth Thangavel
  - admin
  - John Thomas
  - Yee-Leng Tan
  - Justin Dauwels

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-11-22T00:00:00Z'
doi: '10.1142/S0129065723500120'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: International Journal of Neural Systems
publication_short: In IJNS

abstract: Neurologists typically identify epileptic seizures from electroencephalograms (EEGs) by visual inspec-tion. This process is often time-consuming, especially for EEG recordings that last hours or days.To expedite the process, a reliable, automated, and patient-independent seizure detector is essential.However, developing a patient-independent seizure detector is challenging as seizures exhibit diversecharacteristics across patients and recording devices. In this study, we propose a patient-independentseizure detector to automatically detect seizures in both scalp EEG and intracranial EEG (iEEG). First,we deploy a convolutional neural network with transformers and belief matching loss to detect seizuresin single-channel EEG segments. Next, we extract regional features from the channel-level outputs todetect seizures in multi-channel EEG segments. At last, we apply postprocessing filters to the segment-level outputs to determine seizures’ start and end points in multi-channel EEGs. Finally, we introducethe minimum overlap evaluation scoring as an evaluation metric that accounts for minimum overlapbetween the detection and seizure, improving upon existing assessment metrics. We trained the seizuredetector on the Temple University Hospital Seizure (TUH-SZ) dataset and evaluated it on five indepen-dent EEG datasets. We evaluate the systems with the following metrics --- sensitivity (SEN), precision(PRE), and average and median false positive rate per hour (aFPR/h and mFPR/h). Across four adultscalp EEG and iEEG datasets, we obtained SEN of 0.617-1.00, PRE of 0.534-1.00, aFPR/h of 0.425-2.002, and mFPR/h of 0-1.003. The proposed seizure detector can detect seizures in adult EEGs andtakes less than 15s for a 30 minutes EEG. Hence, this system could aid clinicians in reliably identifyingseizures expeditiously, allocating more time for devising proper treatment.

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
