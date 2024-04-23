---
title: "RETORCH: an approach for resource-aware orchestration of end-to-end test cases"
authors:
- Cristian Augusto
- Jesús Morán
- Antonia Bertolino
- Claudio de la Riva
- Javier Tuya
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2020-03-02T00:00:00Z"
doi: "10.1007/s11219-020-09505-2"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Software Quality Journal, Q2*(1)"
publication_short: ""

abstract: Continuous integration practice mandates to continuously introduce incremental changes into code, but doing so may introduce new faults too. These faults could be detected automatically through regression testing, but this practice becomes prohibitive as the cost of executing the tests grows. This problem is preponderant in end-to-end testing where the whole system is requested for test execution. However, some of these test cases could be executed with fewer resources (e.g., memory, web services, computation, Cloud instances, among others), by deploying only the subsystems needed by each test. This paper is focused on the optimization of the resources employed in end-to-end testing by means of a resource-aware test orchestration technique in the context of continuous integration practices in the Cloud. The RETORCH approach proposes a novel way to identify the resources required by end-to-end test cases and to use this information to group together those tests requiring equivalent resources. Besides, the approach proposes to deploy the grouped tests in isolated and elastic environments, so that their execution can be scheduled in parallel on several machines. RETORCH is exemplified with a real-world application, and its performance evaluation shows promising savings in terms of resource usage and time.

# Summary. An optional shortened abstract.
summary: RETORCH proposes a novel way to identify the resources required by end-to-end test cases and to use this information to group together those tests requiring equivalent resources. Besides, the approach proposes to deploy the grouped tests in isolated and elastic environments, so that their execution can be scheduled in parallel on several machines.

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
url_pdf: 'http://hdl.handle.net/10651/53593'
url_code: 'https://github.com/giis-uniovi/retorch'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example

title: "FlakyLoc: Flakiness Localization for Reliable Test Suites in Web Applications"
authors:
- Jesús Morán
- Cristian Augusto
- Antonia Bertolino
- Claudio de la Riva
- Javier Tuya
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: "10.13052/jwe1540-9589.1927"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Web Engineering, Q3*(2)"
publication_short: ""

abstract: Web application testing is a great challenge due to the management of complex asynchronous communications, the concurrency between the clients-servers, and the heterogeneity of resources employed. It is difficult to ensure that a test case is re-running in the same conditions because it can be executed in undesirable ways according to several environmental factors that are not easy to fine-grain control such as network bottlenecks, memory issues or screen resolution. These environmental factors can cause flakiness, which occurs when the same test case sometimes obtains one test outcome and other times another outcome in the same application due to the execution of environmental factors. The tester usually stops relying on flaky test cases because their outcome varies during the re-executions. To fix and reduce the flakiness it is very important to locate and understand which environmental factors cause the flakiness. This paper is focused on the localization of the root cause of flakiness in web applications based on the characterization of the different environmental factors that are not controlled during testing. The root cause of flakiness is located by means of spectrum-based localization techniques that analyse the test execution under different combinations of the environmental factors that can trigger the flakiness. This technique is evaluated with an educational web platform called FullTeaching. As a result, our technique was able to locate automatically the root cause of flakiness and provide enough information to both understand it and fix it.

# Summary. An optional shortened abstract.
summary: 
The paper addresses the challenge of flakiness in web application testing, caused by uncontrollable environmental factors. It proposes a spectrum-based localization technique to automatically identify and understand these factors' influence on test outcomes. The approach is evaluated on the FullTeaching platform, successfully pinpointing and providing insights to resolve flakiness issues.

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example

---


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
