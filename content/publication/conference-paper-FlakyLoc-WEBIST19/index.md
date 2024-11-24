---
title: 'Debugging flaky tests on web applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
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

date: '2019-09-18T00:00:00Z'
doi: '10.5220/0008559004540461'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-09-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the 15th International Conference on Web Information Systems and Technologies, Viena, Austria*' 
publication_short: 'In *WEBIST19* (C3)'

abstract: Testing web applications is a challenging practice because it involves managing asynchronous requests between clients and servers, the integration of heterogeneous technologies, and concurrent accesses to the resources. Therefore, rerunning the test cases of these applications under the same conditions is difficult as one test case can be executed in many different ways according to several environmental factors like memory, screen size or network. Moreover, some of these test cases could be flaky, i.e., due to environmental factors the test outcome can vary even though the application did not change. Understanding which factors are the root cause of flakiness is very important for web developers to both prevent and fix flakiness. This paper introduces a technique to locate the root causes of flakiness based on a characterization of the different environmental factors that are not controlled during the testing of web applications. The root cause of flakiness is located by a spectrum-based localization technique that analyses the execution of the same flaky test under different environmental factors that can trigger the flakiness. The technique is illustrated on an educational web platform named FullTeaching.

# Summary. An optional shortened abstract.
summary: 

tags: 
  - Software Testing and Debugging
  - Spectrum-based Localization
  - Web Applications
  - Test Flakiness

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://hdl.handle.net/10651/54569'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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


