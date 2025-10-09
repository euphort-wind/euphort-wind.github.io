---
title: 'Towards systematic trade-off management for MLOps: quality model, architectural tactics, design patterns'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin


date: '2025-10-01'
doi: '2077/89744'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: In the *Licentiate Theses of the University of Gothenburg*
publication_short: ‎ *Licentiate Thesis*

abstract: Machine-learning-enabled systems are booming within modern software-intensive domains, driving innovation in areas such as healthcare, finance, and autonomous systems. To produce high-quality and competitive solutions, the development and operation of ML-enabled systems (MLOps) require careful consideration of quality trade-offs across the entire production cycle. These trade-offs often differ from well-studied ones relevant to traditional software due to the inherently probabilistic and data-dependent nature of machine learning. Such differences particularly challenge startups and SMEs, who must operate in a non-standardized domain and seek frameworks that capture best practices for producing ML-enabled software. In this thesis, we propose a framework for embedding systematic trade-off management into the MLOps lifecycle. Firstly, based on the results of a systematic literature review combined with an evaluation in industrial settings, we built a common quality model unique to ML-enabled systems. Second, through a systematic literature review and multiple-case study with four companies in the AI domain, we derived architectural and non-architectural tactics employed to achieve identified quality attributes. Third, we extracted existing design patterns from the component models of ML-enabled software identified through a multi-vocal literature review, and, using semi-structured expert interviews, evaluated their impact on quality attributes. In combination, these three studies lead to the insight that applying tactics or patterns to improve one quality attribute usually has side effects on other attributes, resulting in quality trade-offs. Our findings reveal that trade-off management is crucial for ML software production, as it significantly influences decision-making at all dimensions of the MLOps lifecycle (data, model, operations, and development). Based on these insights, as a fourth and final contribution, we propose a vision of an extension to the overall MLOps paradigm by embedding explicit steps for trade-off management at all phases of the workflow.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://gupea.ub.gu.se/bitstream/handle/2077/89744/V.%20Indykov%20final%20final%20thesis.pdf'

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