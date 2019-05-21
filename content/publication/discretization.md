+++
title = "Benchmarking Time-Series Data Discretization on Inference Methods"

# Date first published.
date = "2018-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yuezhe Li", "Tiffany Jann", "__Paola Vera-Licona__ &dagger;"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Bioinformatics, Jan 18 2019. doi: 10.1093/bioinformatics/btz036. PMID: 30657860"
publication_short = ""

# Abstract and optional shortened version.
abstract = "The rapid development in quantitatively measuring DNA, RNA, and protein has stimulated a great  interest  in the  development  of  reverse-engineering  methods,  that  is,  data-driven  approaches to infer the network structure or a dynamical model of the system. Many reverse engineering methods require  discrete  quantitative  data  as  input,  while  many  experimental  data  are  continuous.  While  data discretization has been considered as a pre-processing step, some studies on the reverse-engineering of intracellular networks have started to reveal the impact that the choice of data discretization has on the performance of reverse-engineering methods. However, more comprehensive studies are still greatly needed to systematically and quantitatively understand the impact that discretization methods have on inference methods. Furthermore, there is an urgent need for systematic comparative methods that can help select between discretization methods. In  this  work,  we  consider  4  different  published  intracellular  networks  with  their  respective time-series datasets.  We consider each publication’s original reverse-engineering method and original datasets,  and  discretized  the  data  with  different  discretization  methods.  Across  the  4  studied  cases, changing the data discretization to a more appropriate one, improved the reverse engineering methods’ performance  by  either  increasing  the  number  of  inferred  true  positives  or  decreasing  the  number  of inferred false positives. We observed no universal best discretization method across different time-series data sets.  Thus,  we propose TEDIE, a two-step evaluation metric for ranking discretization methods for time-series data. The underlying assumption of TEDIE is that an optimal discretization method should preserve the dynamic patterns observed in the original data across all variables. We used the 4 different published data sets and networks to validate TEDIE."

#abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["ReverseEngineering", "TNBC_Math"]

# Links (optional).
url_pdf = "https://www.ncbi.nlm.nih.gov/pubmed/30657860"
url_preprint = "https://www.biorxiv.org/content/early/2018/08/01/378620"
url_code = "https://github.com/VeraLiconaResearchGroup/Benchmarking_TSDiscretizations"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""


+++