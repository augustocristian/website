---
title: "FlakyLoc: Flakiness Localization for Reliable Test Suites in Web Applications"
authors:
- moranjesus
- augusto
- bertolino
- claudio
- tuya
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2020-03-02T00:00:00Z"
doi: "10.13052/jwe1540-9589.1927"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Web Engineering, Q3* (J1)"
publication_short: ""

abstract: Web application testing is a great challenge due to the management of complex asynchronous communications, the concurrency between the clients-servers, and the heterogeneity of resources employed. It is difficult to ensure that a test case is re-running in the same conditions because it can be executed in undesirable ways according to several environmental factors that are not easy to fine-grain control such as network bottlenecks, memory issues or screen resolution. These environmental factors can cause flakiness, which occurs when the same test case sometimes obtains one test outcome and other times another outcome in the same application due to the execution of environmental factors. The tester usually stops relying on flaky test cases because their outcome varies during the re-executions. To fix and reduce the flakiness it is very important to locate and understand which environmental factors cause the flakiness. This paper is focused on the localization of the root cause of flakiness in web applications based on the characterization of the different environmental factors that are not controlled during testing. The root cause of flakiness is located by means of spectrum-based localization techniques that analyse the test execution under different combinations of the environmental factors that can trigger the flakiness. This technique is evaluated with an educational web platform called FullTeaching. As a result, our technique was able to locate automatically the root cause of flakiness and provide enough information to both understand it and fix it.

# Summary. An optional shortened abstract.
summary: 

tags:
- Software testing and debugging
- Spectrum-based localization
- Test flakiness 
- Web applications

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'http://hdl.handle.net/10651/57031'
url_code: ""
url_dataset: ""
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
 - testeamos

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''

---



