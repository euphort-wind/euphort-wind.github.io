---
title: 'On the use of GPT-4 in the reverse engineering of class diagrams'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Victor Campanello
  - Shariq Shahbaz
  - admin
  - Daniel Strüber

date: '2025-06-10T00:00:00Z'
doi: 'http://doi.org/10.5381/jot.2025.24.2.a14'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *European Conference on Modelling Foundations and Applications '25* 
publication_short: In *ECMFA 2025* 

abstract: Class diagrams are a standard notation for effectively visualizing the structure of a software system in the context of software design and analysis. In particular, class diagrams are widely used in reverse engineering, the main goal of which is to reconstruct and analyze the design of a system from a given codebase to understand and improve it. Yet, traditional reverse engineering tools that generate class diagrams from code often produce cluttered outputs due to their inability to perform abstraction, that is, leaving out or summarizing nonessential elements in a way human experts would do.In this paper, we explore the use of large language models, specifically GPT-4, in generating class diagrams from code to emulate human abstraction. We used an experimental methodology in which we applied GPT-4 to a dataset of five substantial projects, comprising 4452 code elements and their expert-created abstraction to 338 model elements. Our prompts were informed by an in-depth manual analysis of the dataset, in which we identified stylistic choices that can lead to different generation outcomes and, therefore, are useful to include as hints into the prompt to reflect user preferences. To understand GPT-4’s inherent ability to abstract, we experimented with including hints from the Human Abstraction Framework (HAF), a previous systematization of human abstraction, into the prompts. Our results shed a promising light on the use of GPT-4 for making abstraction decisions at a fine level of granularity (e.g., the inclusion of attribute- and operation-level and type information), where mean F1 scores of 91% and 89% could be achieved, respectively, while more coarse-grained abstraction decisions (especially regarding the representation of relationships) lead to considerably worse F1 scores between 62% and 75%. The inclusion of HAF-based hints into prompts did not significantly affect accuracy, shedding a promising light on GPT-4s’s inherent abstraction ability. Our results emphasize the need for further research on understanding the handling of relationships during manual abstraction.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jot.fm/issues/issue_2025_02/a14.pdf'

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
