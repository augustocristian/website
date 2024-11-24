---
title: 'Optimizing End-to-End test execution : Unleashing the Resource Dispatcher - WiP'

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

date: '2024-08-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: [ 'paper-conference' ]

# Publication name and optional abbreviated publication name.
publication: 'In *50th Euromicro Conference Series on Software Engineering and Advanced Applications (SEAA) 2024, Paris, France *'
publication_short: 'In *SEAA24* (C7)'

abstract: 'Continuous integration practices have transformed software development, but ex-ecuting test suites of modern software developments addresses new challenges due to its complexity and its huge number of test cases. Certain test levels, like End-to-end testing, are even more challenging due to long execution times and re-source-intensive requirements, moreover when we have many End-to-end test suites. Those E2E test suites are executed sequentially and in parallel over the same infrastructure and can be executed several times (e.g., due to some tester consecutive contributions, or version changes performed by automation engines). In previous works, we presented a framework that optimizes E2E test execution by characterizing Resources and grouping/scheduling test cases, based on their compatible usage. However, the approach only optimizes a single test suite exe-cution and neglects other executions or test suites that can share Resources and lead to savings in terms of time and number of Resource redeployments. In this work, we present a new Resource allocation strategy, materialized through a Re-source Dispatcher entity. The Resource Dispatcher centralizes the Resource man-agement and allocates the test Resources to the different test suites executed in the continuous integration system, according to their compatible usage. Our approach seeks efficient Resource sharing among test cases, test suites, and suite execu-tions, reducing the need for Resource redeployments and improving the execution time. We have conducted a proof of concept, based on real-world continuous in-tegration data, that shows savings in both Resource redeployments and execution time.'
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

url_pdf: 'https://hdl.handle.net/10651/74729'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://digibuo.uniovi.es/dspace/bitstream/handle/10651/74729/2024_08_SSEA_Presentation_RUO.pdf?sequence=4&isAllowed=y'
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
  - equavel

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---


