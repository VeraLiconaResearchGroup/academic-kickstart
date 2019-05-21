+++
title = "REACT"
date = 2015-07-17
draft = false

# Tags: can be used for filtering tools.
tags = ["network-inference","boolean-networks", "data-discretization"]

# Tool summary to display on homepage.
summary = "REACT: Reverse Engineering Algorithm with Evolutionary Computation Tools"


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

## Introduction
The inference of gene regulatory networks (GRNs) from system-level experimental observations is at the heart of systems biology due to its centrality in gaining insight into the complex regulatory mechanisms in cellular systems. This includes the inference of both the network topology and dynamic mathematical models.
This software contains a novel network inference algorithm within the algebraic framework of Boolean polynomial dynamical system (BPDS). The algorithm considers time series data, including that of perturbation experiments such as knock-out mutants and RNAi experiments. To infer the network topology and dynamic models, it allows for the incorporation of prior biological knowledge while being robust to significant levels of noise in the data used for inference. It uses an evolutionary algorithm for local optimization with an encoding of the mathematical models as BPDS.


## Download and Run
REACT is wrapped in a Docker container based on the [AlgoRun](http://algorun.org) framework. You can easily run REACT from [here](http://react.algorun.org/).

The source code can be downloaded from our GitHub repository in [here](https://github.com/veralicona/REACT).

## Publications
 P Vera-Licona, A Jarrah, LD Garcia-Puente, J McGee, R Laubenbacher. [An algebra-based method for inferring gene regulatory networks](https://veraliconaresearchgroup.github.io/publication/react/). BMC Syst Biol. 2014 Mar 26;8:37. PubMed PMID: 24669835 (chosen as Editor’s Picks), 2014.
