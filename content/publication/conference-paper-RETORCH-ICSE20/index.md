---
title: 'Efficient test execution in End to End testing : Resource optimization in End to End testing through a smart resource characterization and orchestration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Cristian Augusto
author_notes:
- "Equal contribution"


date: '2020-12-01T00:00:00Z'
doi: '10.1145/3377812.3382177'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *2020 ACM/IEEE 42nd International Conference on Software Engineering: Companion, ICSE-Companion 2020*'
publication_short: In *ICSE20*

abstract: Virtualization and containerization have been two disruptive technologies in the past few years. Both technologies have allowed isolating the applications with fewer resources and have impacted fields such as Software Testing. In the field of testing, the execution of the containerized/virtualized test suite has achieved great savings, but when the complexity increases or the cost of deployment rises, there are open challenges like the efficient execution of End to End (E2E) test suites. This paper proposes a research problem and a feasible solution that looks to improve resource usage in the E2E tests, towards smart resource identification and a proper organization of its execution in order to achieve efficient and effective resource usage. The resources are characterized by a series of attributes that provide information about the resource and its usage during the E2E testing phase. The test cases are grouped and scheduled with the resources (i.e. parallelized in the same machine or executed in a fixed arrangement), achieving an efficient test suite execution and reducing its total cost/time.

# Summary. An optional shortened abstract.
summary: Execute End to End (E2E) test suites in virtualized/containerized environments is challenging due to increasing complexity and deployment costs. It proposes a solution focusing on smart resource identification and organizing test case execution for optimal resource usage. By characterizing resources with attributes and scheduling test cases accordingly, the approach aims to achieve efficient and cost-effective E2E test suite execution.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://hdl.handle.net/10651/58377'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
