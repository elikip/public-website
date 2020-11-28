---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations"
authors: ["Eliayhu Kiperwasser", "Yoav Goldberg"]
date: 2016-01-01T00:00:00+03:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2016-01-01T00:00:00+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We present a simple and effective scheme for dependency parsing which is based on bidirectional-LSTMs (BiLSTMs). Each sentence token is associated with a BiLSTM vector representing the token in its sentential context, and feature vectors are constructed by concatenating a few BiLSTM vectors. The BiLSTM is trained jointly with the parser objective, resulting in very effective feature extractors for parsing. We demonstrate the effectiveness of the approach by applying it to a greedy
transition based parser as well as to a globally optimized graph-based parser. The resulting parsers have very simple architectures, and match or surpass the state-of-the-art accuracies on English and Chinese."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.transacl.org/ojs/index.php/tacl/article/viewFile/885/198"
url_code: "https://github.com/elikip/bist-parser.git"
url_dataset:
url_poster: "https://www.dropbox.com/s/8wuyfhjj1z3fqs4/BiLSTM.pdf?dl=1"
url_project:
url_slides: "https://www.dropbox.com/s/b1lv35td44q114q/acl16.pdf?dl=1"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
