---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Development and validation of multimorbidity index predicting mortality among Chinese older adults"
event: The Gerontological Society of America (GSA) 2021 Annual Scientific Meeting
event_url: https://community.geosociety.org/gsa2021/home

location: Online

summary: Poster Presentation in The Gerontological Society of America (GSA) 2021 Annual Scientific Meeting.
abstract: 'This study aimed to construct a multimorbidity index among Chinese older adults. Participants aged 65-84 years (n=11,757) from the Chinese Longitudinal Healthy Longevity Survey (CLHLS). Fourteen self-reported chronic conditions were assessed at baseline. Outcome was all-cause mortality within five-year follow-up. We used restrictive association rules mining to identify the patterns of multiple chronic conditions associated with mortality. The weights of conditions and disease combinations were assigned using logistic regression adjusted by age and sex in training set. Multimorbidity index (MI) with individual diseases and multimorbidity index incorporating disease combinations (MIDC) were developed. We compared the performance of MI and MIDC with condition count and XGBoost algorithm in the validation set. There were no significant differences of c-statistics between condition count (0.687) and MI (0.692) or MIDC (0.689). The c-statistic of XGBoost algorithm (0.675) was the lowest among all models. The Integrated Discrimination Improvement (IDI) and categorical Net Reclassification Index (NRI) for MI (IDI: 0.01, P < 0.001; NRI: 0.01, P = 0.127), MIDC (IDI: 0.004, p = 0.002; NRI: 0.02, P = 0.033), and XGBoost model (IDI: 0.02, P < 0.001; NRI: 0.03, P = 0.004) were significantly positive compared with condition count. However, no significant differences for IDI and NRI were observed between MI and MIDC. Among Chinese older adults, weighted multimorbidity index with individual disease can better predict five-year mortality risk over condition count. There was little improvement in the predictive performance of the index after considering the joint effects of disease combinations.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2021-11-10T11:00:00-04:00'
date_end: '2021-11-13T19:30:00-04:00'
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2022-06-12T21:43:20+08:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf: "content/event/gsa-2021"
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["multimorbidity-measures"]
---
