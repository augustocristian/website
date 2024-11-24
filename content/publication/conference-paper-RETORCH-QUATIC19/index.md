---
title: 'RETORCH: Resource-Aware End-to-End Test Orchestration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
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

date: '2019-09-11T00:00:00Z'
doi: '10.1007/978-3-030-29238-6_22'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-08-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the 12th International Conference on the Quality of Information and Communications Technology, Ciudad Real, Spain*' 
publication_short: 'In *QUATIC19* (C2)'

abstract: Continuous integration practices introduce incremental changes in the code to both improve the quality and add new functionality. These changes can introduce faults that can be timely detected through continuous testing by automating the test cases and re-executing them at each code change. However, re-executing all test cases at each change may not be always feasible, especially for those test cases that make heavy use of resources thoroughly like End-to-End test cases that need a complex test infrastructure. This paper is focused on optimizing the usage of the resources employed during End-to-End testing (e.g., storage, memory, web servers or tables of a database, among others) through a resource-aware test orchestration technique in the context of continuous integration in the cloud. In order to optimize both the cost/usage of resources and the execution time, the approach proposes to (i) identify the resources required by the End-to-End test cases, (ii) group together those tests that need the same resources, (iii) deploy the tests in both dependency isolated and elastic environments, and (iv) schedule their parallel execution in several machines.

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

url_pdf: 'http://hdl.handle.net/10651/53593'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://digibuo.uniovi.es/dspace/bitstream/handle/10651/53593/2019_09_QUATIC19_RETORCH_Presentation.pdf?sequence=6&isAllowed=y'
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
  - testeamos

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---


