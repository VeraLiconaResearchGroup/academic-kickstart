+++
title = "OCSANA_V2"
date = 2018-01-17
draft = false

# Tags: can be used for filtering tools.
tags = ["structure-based-control"]

# Tool summary to display on homepage.
summary = "OCSANA: Optimal Combination of Interventions from Network Analysis"


# Optional image to display on homepage.
image_preview = "bigstock-DNA-molecules-with-binary-code-83578793.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""


# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

Introduction
Targeted therapies interfering specifically one protein activity, are promising strategies in the treatment of diseases like cancer. However, accumulated empirical experience has shown that targeting multiple proteins in signaling networks involved in the disease, is often necessary. Thus one important problem in biomedical research is the design and prioritization of optimal combinations of interventions to repress a pathological behavior, while minimizing side-effects.

OCSANA (Optimal Combinations of Interventions from Network Analysis) is a software designed to identify and prioritize optimal and minimal, combinations of interventions to disrupt the paths between source nodes and target nodes. When specified by the user, OCSANA seeks to additionally minimize the side-effects that a combination of interventions can cause on specified off-target nodes. With the crucial ability to cope with very large networks, OCSANA includes exact and selective enumeration approaches for the combinatorial interventions’ problem.