---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Analyzing the Costs (and Benefits) of DNS, DoT, and DoH for the Modern
Web"
authors: ["Austin Hounsel", "Kevin Borgolte", "Paul Schmitt", "Jordan Holland",
"Nick Feamster"]
date: 2019-07-22
doi: "10.1145/3340301.3341129"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Applied Networking Research Workshop"
publication_short: "ANRW '19"

abstract: "We measure the effect of DoH and DoT on name resolution performance and content delivery. We find that although DoH and DoT response times can be higher than for conventional DNS (Do53), DoT performs better than DoH and Do53 in terms of page load times. However, when network conditions degrade, webpages load quickest with Do53, and up to one second faster compared to DoH. Furthermore, in a substantial amount of cases, a webpage may not load at all with DoH, while it loads successfully with DoT and Do53. Our in-depth analysis reveals various opportunities to readily improve DNS performance, for example through opportunistic partial responses and wire format caching."

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

url_pdf: publication/anrw19/paper.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
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
