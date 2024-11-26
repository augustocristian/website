---
title: "RETORCH*: A Cost and Resource aware Model for E2E Testing in the Cloud"
authors:
- augusto
- moranjesus
- bertolino
- claudio
- tuya
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2025-03-01T00:00:00Z"
doi: "10.1016/J.JSS.2024.112237"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Systems and Software, Q1* (J3)"
publication_short: "In *JSS*, Q1 (J3)"

abstract: Moving testing to the Cloud overcomes time/resource constraints by leveraging an unlimited and elastic infrastructure, especially for testing levels like End-to-End (E2E) that require a high number of resources and/or execution time. However, it introduces new challenges to those already faced on-premises, like selecting the most suitable Cloud infrastructure and billing scheme. We propose the RETORCH* test execution model that estimates and compares the monetary cost of executing an E2E test suite with different Cloud alternatives, billing schemes, and test configurations. RETORCH* goes beyond the mere cost billed, and selects the solution that best aligns with the test team strategy using the data of on-premises prior executions and the tester's experience. This cost is broken down into the cost incurred to execute the test suite (testing cost) and possible unused infrastructure (overprovisioning cost). Based on these distinct costs, the test team can compare different Cloud and test configurations. RETORCH* has been evaluated using a real-world application's E2E test suite. We analyze how the different decisions taken when the suite is migrated to the Cloud impact the cost, highlighting how RETORCH* can help the tester during Cloud and test configuration to make a more informed decision.
# Summary. An optional shortened abstract.
summary:

tags:
- Continuous integration
- Continuous testing
- End-to-end testing
- Software testing
- Test orchestration
- Testing in the Cloud

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://hdl.handle.net/10651/75794'
url_code: 'https://github.com/giis-uniovi/retorchx-rp'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
 - equavel

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---