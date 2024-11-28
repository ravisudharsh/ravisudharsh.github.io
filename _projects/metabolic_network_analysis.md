---
layout: page
title: Metabolic Network Analysis
description: Projects with applications of metabolic network analysis
img: assets/img/met_net.png
importance: 3
category: Projects
related_publications: true
---

<hr style="height:5px; visibility:hidden;" />

A fundamental aim of life science is to understand the functioning of an organism and draw system-level connections between its genotype and behavior. Among the most significant types of interaction networks, cellular metabolism is a well-established descriptor of the phenotype of an organism. Inspecting and analyzing the metabolic network in its entirety is crucial in attaining a holistic understanding of the underlying biological mechanism. I am interested in developing algorithms designed to highlight metabolic alterations in neurodegenerative diseases and cancers.

<hr style="height:5px; visibility:hidden;" />

<style>
ul {
  list-style-type: square; /* Remove HTML bullets */
  padding-left: 10px;
  margin-left: 10px;
}
li { 
  padding-left: 0px; 
}
</style>
<ul>
<li> Metabolic stress is a primary pathogenic event in transgenic <em>Caenorhabditis elegans</em> expressing pan-neuronal human amyloid beta. </li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/met_net_main_1.jpg" title="Metabolic Flux Difference in C.elegans" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In this work {% cite Teo2019 %} in collaboration with [Prof. Jan Gruber's lab in Yale-NUS, Singapore](https://www.yale-nus.edu.sg/faculty/jan-gruber/), we showcase the metabolic changes associated with this amyloid-beta induced mitochondrial dysfunction. Our metabolic network analysis with the integration of metabolomics, transcriptomics and experimental data reveal alterations in the Tricarboxylic acid (TCA) cycle metabolism following low-level expression of amyloid-beta, a model to study Alzheimer's disease.  

<hr style="height:5px; visibility:hidden;" />

<ul>
<li> Metabolic adaptation of ovarian tumors in patients treated with an IDO1 inhibitor constrains antitumor immune responses. </li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/met_net_main_2.jpg" title="Metabolic Flux Difference in IDO1 inhibited cancer patients" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Here {% cite Odunsi2022 %}, we leveraged on experimental data on human clinical trials of chemotherapy in ovarian cancer patients collected by [Prof. Kunle Odunsi](https://www.cancerresearch.org/scientific-advisory-council/kunle-odunsi) lab at [Roswell Park Comprehensive Cancer Center, Buffalo, USA](https://www.roswellpark.org/). Through our integrative metabolic network analysis, we assisted in uncovering the underlying mechanisms associated with failure of indoleamine 2,3-dioxygenase 1 (IDO1) blockade in clinical trials. 