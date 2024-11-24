---
title: 'Test-Driven Anonymization in Health Data: A Case Study on Assistive Reproduction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- augusto
- Miguel Olivero
- moranjesus
- Leticia Morales
- claudio
- Javier Aroba
- tuya
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: '2020-08-03T00:00:00Z'
doi: '10.1109/AITEST49225.2020.00019'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings - 2020 IEEE International Conference on Artificial Intelligence Testing, AITest 2020*
publication_short: "In *AITEST20* (C5)"

abstract: Artificial intelligence (AI) is a broad field whose prevalence in the health sector has increased during recent years. Clinical data are the basic staple that feeds intelligent healthcare applications, but due to its sensitive character, its sharing and usage by third parties require compliance with both confidentiality agreements and security measures. Data Anonymization emerges as a solution to both increasing the data privacy and reducing the risk against unintentional disclosure of sensitive information through data modifications. Despite the anonymization improves privacy, the diverse modifications also harm the data functional suitability. These data modifications can affect to the applications that employ the anonymized data, especially those that are data-centric as the AI tools. To obtain a trade-off between both qualities (privacy and functional suitability), we use the Test-Driven Anonymization (TDA) approach, which anonymizes incrementally the data to train the AI tools and validate with the real data until maximize its quality. The approach is evaluated in a real-world dataset from the Spanish Institute for the Study of the Biology of Human Reproduction (INEBIR). The anonymized datasets are used to train AI tools and select the dataset that gets the best trade-off between privacy and functional quality requirements. The results show that TDA can be successfully applied to anonymize the clinical data of the INEBIR, allowing third parties to transfer without transgressing the user privacy and develop useful AI Tools with the anonymized data.

# Summary. An optional shortened abstract.
summary:

tags: 
  - Anonymization
  - Software Testing
  - Artificial intelligence
  - Health-Care Data
  - k-Anonymity  

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://hdl.handle.net/10651/56868'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://digibuo.uniovi.es/dspace/bitstream/handle/10651/56868/2020_07_AITEST20_TDA_Presentation.pdf?sequence=9&isAllowed=y'
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
projects:
  - testeamos

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---


