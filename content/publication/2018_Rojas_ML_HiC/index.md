---
title: "Machine learning approaches for comparative genome structure analysis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Minh N. Tran
- Linh Huynh
- Fereydoun Hormozdiari

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2018-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent, 9 = Poster
publication_types: ["9"]

# Publication name and optional abbreviated publication name.
publication: American Society of Human Genetics
publication_short: ASHG

abstract: The development of high-throughput chromosome conformation capture techniques (Hi-C) has provided a wealth of data on the three-dimensional architecture of genomes. We can use this data to analyze the topological structure of genome and understand genomic interactions. However, the accurate approach to find conserved or specific genomic interactions in two or more Hi-C contact matrices is an open question. We introduce a convolutional autoencoder an unsupervised machine learning technique to produce a similarity function to compare areas between pairs of Hi-C matrices. Our model is trained on sub-blocks of the Hi-C matrix that are treated as high-dimensional vectors and that are transformed into lower dimensional vectors. We show that our autoencoder outperforms statistical methods such as principal components analysis (PCA) and root-mean-square error (RMSE) for finding genomic interactions which are specifi c to one of the matrices. This method is useful and accurate in finding genomic interactions specifi c to one genome which potentially result in changes in gene expression by comparing Hi-C matrices from two or more tissues or species.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example


# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}
#
# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

---


