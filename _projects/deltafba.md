---
layout: page
title: ΔFBA
description: A workflow for the integration of differential transcriptomics data in genome scale metabolic models
img: assets/img/pcbi.png
importance: 2
category: Projects
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/r_dfba_main.png" title="DeltaFBA Workflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr style="height:5px; visibility:hidden;" />

Metabolic alterations are often used as hallmarks of observable phenotypes. In this regard, reconstructed genome-scale metabolic models (GEMs) provide a rich and computable representation of the entire set of biochemical reactions in a cell. They provide a powerful framework for simulating the entire set of biochemical reactions in a cell using a constraint-based modeling strategy called flux balance analysis (FBA). FBA relies on an assumed metabolic objective for generating metabolic fluxes using GEMs. But, the most appropriate metabolic objective is not always obvious for a given condition and is likely context-specific, which often complicate the estimation of metabolic flux alterations between conditions. We developed a computational tool called ΔFBA (deltaFBA) {% cite Ravi2021 %}, that integrates differential gene expression data to evaluate directly metabolic flux differences between two conditions. Notably, ΔFBA does not require specifying the cellular objective. Rather, ΔFBA seeks to maximize the consistency and minimize inconsistency between the predicted flux differences and differential gene expression. 

<hr style="height:5px; visibility:hidden;" />

∆FBA is built in [MATLAB](https://ch.mathworks.com/products/matlab.html) with [COBRA toolbox](https://opencobra.github.io/cobratoolbox/stable/index.html) compliant functions and subroutines. The tool is freely available on the [GitHub page](https://github.com/CABSEL/DeltaFBA) of [CABSEL](https://engineering.buffalo.edu/chemical-biological/people/faculty-directory/core.host.html/content/shared/engineering/chemical-biological/profiles/faculty/gunawan-rudiyanto.detail.html).