---
title: 'Toward an efficient End-to-End test suite execution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- augusto
author_notes:
- "Equal contribution"

date: '2023-10-09T00:00:00Z'
doi: '10.1109/ISSREW60843.2023.00038'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings - 2023 IEEE 34th International Symposium on Software Reliability Engineering Workshop, Firenze, Italy*
publication_short: In *ISSREW 2023* (C6)

abstract: End-to-end (E2E) testing is costly because of the complex and expensive resources that are required during the test execution coupled with the long execution times required. This becomes even more challenging when E2E test suites are integrated into a continuous integration (CI/CD) environment, where they are executed with each repository change. Migrating E2E test suite execution to the Cloud is an acknowledged trend to achieve a better cost. However, this also introduces new challenges in addition to those faced on-premises, such as selecting the most suitable services from the wide range offered by Cloud Providers, which is even more difficult considering how the test resources use the Cloud infrastructure. This thesis aims to achieve an efficient execution of the E2E test suites, reducing the number of unnecessary test resource redeployments, and the execution time, and improving the efficiency of selecting the Cloud infrastructure that best aligns with the testing objectives. We present an orchestration approach that aims to enable resource sharing and avoid unnecessary redeployments. This process involves phases like the characterization of the test resources required by the test cases and a grouping of the test cases with compatible resource usage and its scheduling in sequential-parallel to reduce redeployments-time. The orchestration approach has evolved to execute this orchestrated test suite in the Cloud, introducing a model of the E2E test suite execution in the Cloud, which allows us to represent both the test and the Cloud configuration. Using the model, we estimate and compare different Cloud infrastructures in terms of overall cost (billed by the Cloud Provider), but also the cost invested in testing and unused infrastructure (overprovisioning) to select the infrastructure best aligned with the testing objectives.

# Summary. An optional shortened abstract.
summary: 

tags: 
  - Software Reliability
  - Software Testing
  - Cloud Computing
  - End-to-End Testing
  - Resource Optimization

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hdl.handle.net/10651/72390'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://digibuo.uniovi.es/dspace/bitstream/handle/10651/72390/2023_09_ISSRE23_RETORCH_Presentation.pdf?sequence=5&isAllowed=y'
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
  - equavel

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

