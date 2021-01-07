+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Power and sample size computations for the simultaneous assessment of the consistency of treatment effects"

# Project summary to display on homepage.
summary = "In this study, we address the problem of calculating the power and sample size in the simultaneous assessment of the consistency of treatment effects. The method is based on a general formulation of inconsistency as a treatment-by-subset interaction, while the interaction term is defined as the ratio of the treatment effects. This approach allows the interpretation of inconsistency as a relative change in the treatment effects. In addition, conclusions are given based on an appropriately defined consistency margin. The methodology is applicable to trials with continuous and binary endpoints. Two power definitions arising in multiple testing, namely the all-pair (complete) power and any-pair (minimal) power, are considered. The focus of this study is the assessment of consistency in multi-regional clinical trials, but the proposed methodology is in general applicable to the assessment of any treatment-by-subset interactions, including the detection of qualitative interactions. Several examples from clinical trials are provided to illustrate the application of the proposed procedure. An R add-on package poco was developed for the analysis, which provides the functionality presented in this study."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "PowerMeto.tiff"

# Tags: can be used for filtering projects.
# Example: `tags = ["treatment-by-subset interaction", "multi-regional clinical trials", "heterogeneity"]`
tags = ["treatment-by-subset interaction", "multi-regional clinical trials", "heterogeneity"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
In this study power and sample size calculations for the analysis of treatment-by-subgroup interactions are proposed. Therefore, the interaction effect is either defined via product-type interaction  contrasts or as ratio of treatment differences. The latter formulation allows besides the detection of interactions also the assessment of the consistency/heterogeneity of the subgroup-specific treatment effect by the definition of an inconsistency margin.

You can find the pdf of a detailed article [here](pdf/PowerConsistency_SIM.pdf). Furthermore, the slides from a corresponding talk are given [here](JournalClub_Power.pdf).
