---
title: Projects
nav:
  order: 1
  tooltip: Projects and Techniques
---

## I want to learn more about...
{% capture col1 %}
[##Equitable Genomics](##equitable-genomics---advancing-research-health-and-capability)
{% endcapture %}
{% capture col2 %}
[##Whole-brain mapping](#MAPmap)
[##High-throughput behavioural phenotyping](#high-throughput-behavioural-phenotyping)
{% endcapture %}
{% include cols.html col1=col1 col2=col2 %}



# {% include icon.html icon="fa-solid fa-flask-vial" %}Projects

{% include search-info.html %}

## Equitable Genomics - Advancing Research, Health, and Capability

{% capture content %}
  {%
  include figure.html
  image="images/pics2show/41584_2025_1228_Fig1_HTML.webp"
  caption="Map of the Pacific region with the known national prevalences of hyperuricaemia and gout."
  width="800px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

The ENHANCE lab is dedicated to understanding the genetic factors that influence health outcomes for Māori and Pasifika peoples. Many diseases, such as gout, are prevalent in these populations and have well-established underlying genetic components. Previous research has identified Māori- and Pacific-specific genetic variants linked to disease risk, and we aim to expand this knowledge by identifying new population-specific genetic variants and conducting functional analyses to uncover their biological effects. Genomic databases largely exclude Māori and Pasifika peoples, threatening to widen health inequities as precision medicine advances. By addressing this gap, our research will not only enhance the genomic representation of these populations in health-related studies but also uncover novel disease mechanisms relevant to all populations. Our findings could improve diagnostics, enable early interventions, and lead to more inclusive and effective treatments for all. Here in Aotearoa, we have a unique opportunity to explore how inherited genetic variation in these populations contributes to disease risk, ensuring Māori and Pasifika communities benefit equally from future medical innovations. As a Māori-led lab, we are also committed to strengthening Māori and Pacific genomics by recruiting and mentoring Māori and Pasifika students in this critical field while fostering strong relationships with the communities we serve. By elevating Māori and Pacific genomics into global research, we aim to create to a future where precision medicine is equitable and effective for all.


## Non-Coding Genetic Elements

Non-coding elements are far more than just “junk” DNA. Genome-wide association studies indicate that >90% of variants associated with complex disease lie within the non-coding genome. Despite their significance in disease, there has been limited research on these elements. In contrast to the protein coding genome, where a variant will have more obvious functional consequences, these elements are a lot more complex and it is harder to decipher their effect on genes. These elements, such as enhancers, promoters, and silencers, are key regulators of gene expression. Promoters are involved in the initiation of transcription. Enhancers bind transcription factors that help drive gene expression whereas silencers act to repress it. Variants in these non-coding elements can greatly alter transcription which may contribute to distinct phenotypes. A classic example of this variation is when there is a change in the _HERC2_ enhancer sequence that causes decreased expression of the _OCA2_ gene, leading to an individual having blue eyes. Our lab investigates the contribution of the non-coding genome to metabolic conditions such as gout, diabetes, and polycystic ovary syndrome. These are all prevalent chronic conditions in which the aetiology is not well understood. Using zebrafish as a model organism, significant non-coding variants associated with these conditions can be investigated to understand their impact on gene expression.

## _JAZF1_ and metabolic disorders

The development of complex diseases such as type two diabetes is multifactorial and involves interplay between both genetic and environmental factors. An approach known as Genome-Wide Association Studies (GWAS) is an important method to identify regions of the genome that associate with disease. Working with genomes from Māori and Pacific peoples has enabled the identification of unique, population-specific genetic elements that associate with metabolic conditions. Out of the many genetic elements identified in this analysis our project focuses on a variant that is found in a regulatory region of _JAZF1_. The _JAZF1_ gene acts in a number of metabolically active tissues (pancreas, brain, liver, muscle) to regulate energy balance. Of note, the _JAZF1_ gene encodes a transcription factor known to act in pancreatic beta-cells, regulating insulin secretion. Its role in other tissues such as the brain and liver is an emerging topic of study. Zebrafish are a powerful model organism to study gene function. Zebrafish express an orthologue of human _JAZF1_ known as _jazf1b_. The ENHANCE lab has taken the (human) _JAZF1_ genetic element coupled to green-fluorescent protein to visualise where the region is actively driving transcription in zebrafish. Preliminary data indicates extra-pancreatic function of _JAZF1_ and suggests a neuronal role including the brain’s control of circadian rhythm. To explore the behavioural, metabolic, and genetic consequences altering _jazf1b_ in zebrafish, we generated a viable _jazf1b_ knock out zebrafish strain. Our data thus far suggests that _jazf1b_ is involved in circadian control supporting a neuronal function. Additionally, an elevated deposition of fat in the liver may drive _JAZF1_-mediated pathology. Our research aims to provide population-focused insights into the genetic role of _JAZF1_ and explore whether environmental stressors (elevated glucose or lipid exposure) worsen these effects.

## Polycystic ovary syndrome

Polycystic ovary syndrome (PCOS) is the predominant cause of infertility worldwide and is extremely common here in Aotearoa, affecting ~5-15% of women of reproductive age. PCOS is characterized by irregular or reduced ovulation, high androgen hormone levels, and presence of multiple cysts on the ovaries. Despite its prevalence worldwide little is known about its underlying biological mechanisms.

Previous large genome-wide association studies (GWAS) of genetic determinants of PCOS have resulted in the identification of numerous loci. In the ENHANCE lab we seek to expand on this genetic information. Using PCOS GWAS data and expression quantitative trait loci (eQTL) data from GTEx we have found probable causal genes with genetic expression differences in the brain and ovaries. We are generating knockout models of these genes in zebrafish and the testing their contribution to the development of PCOS. We aim to identify novel potential therapeutic targets for the treatment of PCOS here in Aotearoa.


{% include section.html %}


# {% include icon.html icon="fa-solid fa-microscope" %}Techniques

### MAPmap

{% capture content %}
  {%
  include figure.html
  image="images/pics2show/MAPmap.png"
  caption="Activity (left) and structural (right) brain mapping"
  width="600px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}


Metabolic syndromes can be caused by neuroendocrine dysfunction, or cause brain pathologies such as Alzheimer's disease. In the zebrafish larvae, we leverage its transparency, smaller brain size and ease of genetic modification to perform high-throughput functional and structural mapping. We use MAPmap, a **m**itogen-**a**ctivated **p**rotein (MAP) kinase-based whole-brain staining and imaging protocol to visualise and compare brain activation and region-specific changes in volume between different experimental groups. The readout allows us to identify brain areas that may be over or under -active, and detect deviations in brain formation or signs of neurodegeneration. These changes can be checked against a comprehensive reference atlas containing spatially resolved gene expression, cell type marker and protein expression data to further refine our understanding of affected brain circuits in disease.


### High-throughput behavioural phenotyping

{% capture content %}
  {%
  include figure.html
  image="images/pics2show/DanioV.png"
  caption="Simultaneous 96-well animal tracking"
  width="400px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}


Behavioural analysis is crucial in understanding how our genetic models affect the physiology and brain function of larval zebrafish. We use a commercially available high-throughout solution (DanioVision, Noldus) that allows the simultaneous tracking of 96 fish across multiple days. In the system, we are able to alter ambient temperature, light intensity/duration in different colours and administer mechanical "taps" as a startle stimulus. We can combine this repertoire of manipulations to detect changes in circadian rhythms, visual/acoustic startle responses and habituation, sensory perception and locomotor functions. Changes in baseline and stimulus-bound movement trajectories offer us a valuable readout on how the brain interacts with the environment, providing insights to potential brain circuit dysfunction. 


{% include float.html clear=false %}
