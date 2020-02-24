---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Comparing the Effects of DNS, DoT, and DoH on Web Performance"
authors: ["Austin Hounsel", "Kevin Borgolte", "Paul Schmitt", "Jordan Holland",
"Nick Feamster"]
date: 2020-04-20
doi: "10.1145/3366423.3380139"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The Web Conference 2020"
publication_short: "WWW '20"

abstract: "Nearly every service on the Internet relies on the Domain Name System (DNS), which translates a human-readable name to an IP address before two endpoints can communicate. Today, DNS traffic is unencrypted, leaving users vulnerable to eavesdropping and tampering. Past work has demonstrated that DNS queries can reveal a user's browsing history and even what smart devices they are using at home. In response to these privacy concerns, two new protocols have been proposed: DNS-over-HTTPS (DoH) and DNS-over-TLS (DoT). Instead of sending DNS queries and responses in the clear, DoH and DoT establish encrypted connections between users and resolvers. By doing so, these protocols provide privacy and security guarantees that traditional DNS (Do53) lacks.
In this paper, we measure the effect of Do53, DoT, and DoH on query response times and page load times from five global vantage points. We find that although DoH and DoT response times are generally higher than Do53, both protocols can perform better than Do53 in terms of page load times. However, as throughput decreases and substantial packet loss and latency are introduced, web pages load fastest with Do53. Additionally, web pages successfully load more often with Do53 and DoT than DoH. Based on these results, we provide several recommendations to improve DNS performance, such as opportunistic partial responses and wire format caching."

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

url_pdf: publication/www20/preprint.pdf
url_code: https://github.com/noise-lab/dns-measurement-suite.git
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
