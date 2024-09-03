---
title: Research
nav:
  order: 1
  tooltip: Research Overview
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research
Our lab aims to understand how cellular behavior emerges from the dynamics and structural organization of biomolecules. A key characteristic of many subcellular structures is their ability to maintain structural integrity while responding rapidly to external stimuli. For instance, a cell’s nucleus can retain a stable genomic structure while simultaneously reorganizing chromosome configuration in response to external signals. Our goal is to uncover the mechanisms behind this phenomenon through the concept of metastability—a state characterized by multiple stable configurations that allow for rapid transitions between them. To achieve this, we use a combination of microfabricated cell mechanics devices and advanced optical microscopy techniques, such as lattice light sheet microscopy and single-molecule imaging. We also explore the role of machine learning in facilitating our research. 

{% include section.html %}

## Current Projects

{% capture text %}
The cytoskeleton network consists of cross-linked biopolymers and protein motors that exert non-thermal forces. It plays a crucial role in various cellular processes, including migration, mitosis, and immune responses. Notably, the actomyosin network exhibits striking similarities to soft glassy materials, such as power-law rheology, non-Gaussian fluctuations, and step-like displacement events (cytoquakes), indicating that it is in a marginally stable state. By combining micropost array detectors with single-molecule imaging, we investigate the structural organization, dynamics, and mechanical responses of the cytoskeleton to uncover the biophysical origins of its metastability.
<br>Related works: [Shi et al 2019](https://www.pnas.org/doi/abs/10.1073/pnas.1900963116), [Shi et al 2021](https://academic.oup.com/ib/article/13/10/246/6455026)


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/cytoskeletal metastability.png"
  headline="Revealing the biophysical origins of cytoskeletal metastability"
  text=text
%}

{% capture text %}
One of the most remarkable properties of the cell nucleus is its ability to maintain DNA integrity and reorganize chromosome configurition to express different genes in response to external stimuli. This characteristic invites a comparison with glassy materials, which exhibit both solid and liquid-like properties. Our goal is to employ single-molecule imaging, statistical physics, and machine learning to investigate the cell nucleus as an active glass: a non-thermally driven glassy system.
<br>Related works: [Gaugird and Shi et al 2024](http://dx.doi.org/10.1038/s41467-024-48562-0)


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/Nucleosome Dynamics.gif"
  headline="Studying nuclear chromatin as an active glassy material"
  text=text
%}
