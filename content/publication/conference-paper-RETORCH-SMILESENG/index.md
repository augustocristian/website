---
title: 'Resource optimization in End-to-End Testing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - augusto
  - moranjesus
  - claudio
  - tuya
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"

date: '2022-07-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: [ 'paper-conference' ]

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings - 2022 International Summer School on Search- and Machine Learning-based Software Engineering*'
publication_short: 'In *SMILESENG22*'

abstract: 'End-to-end (E2E) test suite execution is expensive due to the number of complex resources required. When E2E test suites are executed frequently into a continuous integration system, the total amount of resources required may be prohibitive , moreover when the tests are run in the Cloud with different billing strategies. Traditional techniques to optimize the test suites, such as test suite reduction, minimization, or prioritization, are limited in E2E due to the fact that reordering or selecting a subset of test cases also requires deploying the same expensive system. The current Ph.D. thesis aims to achieve an efficient E2E test execution for large systems in the Cloud. This is done through a smart characterization of the resources required by the test cases, grouping and scheduling them according to their resource usage to avoid unnecessary redeployments and reduce execution time, and finally, executing them into a combination of Cloud infrastructure (i.e., containers, virtual machines, and services) to optimize the costs employed in executing the test suite. Based on the scheduled test cases, we elaborate a cost model for selecting the most cost-effective infrastructure of those available in the Cloud, considering both the cost of the resources required by the test cases and the oversubscription cost (cost incurred in infrastructure contracted and not used during the test suite execution).'
# Summary. An optional shortened abstract.
summary:

tags:
  - Continuous integration
  - Continuous testing
  - End-to-End testing
  - Software testing
  - Test orchestration
  - Testing in the cloud

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hdl.handle.net/10651/75846'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://digibuo.uniovi.es/dspace/bitstream/handle/10651/75846/22_SMILENG22_RETORCH_Presentation_RUO-1.pdf?sequence=2&isAllowed=y'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - testbus

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---


