+++
title = "The Minimal Hitting Set Generation Problem: Algorithms and Computation"

# Date first published.
date = "2017-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Andrew Gainer-Dewar", "__Paola Vera-Licona__ &dagger;"]

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
publication = "SIAM Journal on Discrete Mathematics. 2017; 31(1):63–100."
publication_short = "SIAM Journal on Discrete Mathematics. 2017; 31(1):63–100"

# Abstract and optional shortened version.
abstract = "Finding inclusion-minimal hitting sets (MHSs) for a given family of sets is a fundamental combinatorial problem with applications in domains as diverse as Boolean algebra, computational biology, and data mining. Although many algorithms are available in the literature to generate these MHSs, application papers typically consider only a few before selecting one (or introducing a novel algorithm), suggesting the need for a comprehensive survey and performance comparison. We introduce several of these applications, discussing how MHS generation is applied in each domain and which algorithms have been used, providing a unified view of these applications for researchers from diverse areas. We survey twenty-one algorithms for MHS generation from across a variety of domains, considering their history, classification, and useful features. We provide the results of a comprehensive suite of benchmarks of public software implementations of seventeen of these algorithms, including six we implemented ourselves in C++, emphasizing problem instances taken from real applications in the literature. We find that the fastest algorithms in practice are not those with the tightest complexity bounds or those most commonly used in applications, suggesting that, for a given application, benchmarking from across the broad span of available algorithms will enable a better choice. Finally, we provide a public repository of these software implementations as ready-to-use, platform-agnostic Docker containers based on the AlgoRun framework, so interested computational scientists can easily perform similar tests with inputs from their own research areas, either on their own computers or through a convenient Web interface or deploy the algorithms in their own analysis pipelines."

#abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["StructureControl"]

# Links (optional).
url_pdf = "https://epubs.siam.org/doi/10.1137/15M1055024"
url_preprint = "https://arxiv.org/abs/1601.02939"
url_code = "https://github.com/VeraLiconaResearchGroup/MHSGenerationAlgorithms"
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
caption = "My caption"

    
[[url_custom]]
    name = "AlgoRunContainer"
    url = "http://algorun.org/browse?q=mhs&hPP=100&idx=dev_AlgoRun&p=0&is_v=1"
        

+++