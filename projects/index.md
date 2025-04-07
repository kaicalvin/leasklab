---
title: Projects
nav:
  order: 1
  tooltip: Projects and Techniques
---

# {% include icon.html icon="fa-solid fa-flask-vial" %}Projects

{% include search-info.html %}

## Equitable Genomics - Advancing Research, Health, and Capability

{% capture content %}
  {%
  include figure.html
  image="images/pics2show/41584_2025_1228_Fig1_HTML.webp"
  caption=""
  width="600px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

The ENHANCE lab is dedicated to understanding the genetic factors that influence health outcomes for Māori and Pasifika peoples. Many diseases, such as gout, are prevalent in these populations and have well-established underlying genetic components. Previous research has identified Māori- and Pacific-specific genetic variants linked to disease risk, and we aim to expand this knowledge by identifying new population-specific genetic variants and conducting functional analyses to uncover their biological effects. Genomic databases largely exclude Māori and Pasifika peoples, threatening to widen health inequities as precision medicine advances. By addressing this gap, our research will not only enhance the genomic representation of these populations in health-related studies but also uncover novel disease mechanisms relevant to all populations. Our findings could improve diagnostics, enable early interventions, and lead to more inclusive and effective treatments for all. Here in Aotearoa, we have a unique opportunity to explore how inherited genetic variation in these populations contributes to disease risk, ensuring Māori and Pasifika communities benefit equally from future medical innovations. As a Māori-led lab, we are also committed to strengthening Māori and Pacific genomics by recruiting and mentoring Māori and Pasifika students in this critical field while fostering strong relationships with the communities we serve. By elevating Māori and Pacific genomics into global research, we aim to create to a future where precision medicine is equitable and effective for all.

41584_2025_1228_Fig1_HTML

## Non-Coding Genetic Elements

Non-coding elements are far more than just “junk” DNA. Genome-wide association studies indicate that >90% of variants associated with complex disease lie within the non-coding genome. Despite their significance in disease, there has been limited research on these elements. In contrast to the protein coding genome, where a variant will have more obvious functional consequences, these elements are a lot more complex and it is harder to decipher their effect on genes. These elements, such as enhancers, promoters, and silencers, are key regulators of gene expression. Promoters are involved in the initiation of transcription. Enhancers bind transcription factors that help drive gene expression whereas silencers act to repress it. Variants in these non-coding elements can greatly alter transcription which may contribute to distinct phenotypes. A classic example of this variation is when there is a change in the _HERC2_ enhancer sequence that causes decreased expression of the _OCA2_ gene, leading to an individual having blue eyes. Our lab investigates the contribution of the non-coding genome to metabolic conditions such as gout, diabetes, and polycystic ovary syndrome. These are all prevalent chronic conditions in which the aetiology is not well understood. Using zebrafish as a model organism, significant non-coding variants associated with these conditions can be investigated to understand their impact on gene expression.

## _JAZF1_ and metabolic disorders

The development of complex diseases such as type two diabetes is multifactorial and involves interplay between both genetic and environmental factors. An approach known as Genome-Wide Association Studies (GWAS) is an important method to identify regions of the genome that associate with disease. Working with genomes from Māori and Pacific peoples has enabled the identification of unique, population-specific genetic elements that associate with metabolic conditions. Out of the many genetic elements identified in this analysis our project focuses on a variant that is found in a regulatory region of _JAZF1_. The _JAZF1_ gene acts in a number of metabolically active tissues (pancreas, brain, liver, muscle) to regulate energy balance. Of note, the _JAZF1_ gene encodes a transcription factor known to act in pancreatic beta-cells, regulating insulin secretion. Its role in other tissues such as the brain and liver is an emerging topic of study. Zebrafish are a powerful model organism to study gene function. Zebrafish express an orthologue of human _JAZF1_ known as _jazf1b_. The ENHANCE lab has taken the (human) _JAZF1_ genetic element coupled to green-fluorescent protein to visualise where the region is actively driving transcription in zebrafish. Preliminary data indicates extra-pancreatic function of _JAZF1_ and suggests a neuronal role including the brain’s control of circadian rhythm. To explore the behavioural, metabolic, and genetic consequences altering _jazf1b_ in zebrafish, we generated a viable _jazf1b_ knock out zebrafish strain. Our data thus far suggests that _jazf1b_ is involved in circadian control supporting a neuronal function. Additionally, an elevated deposition of fat in the liver may drive _JAZF1_-mediated pathology. Our research aims to provide population-focused insights into the genetic role of _JAZF1_ and explore whether environmental stressors (elevated glucose or lipid exposure) worsen these effects.

{% include section.html %}


# {% include icon.html icon="fa-solid fa-microscope" %}Techniques

### MAPmap

{% capture content %}
  {%
  include figure.html
  image="images/pics2show/MAPmap.png"
  caption="Activity (left) and structural (right) brain mapping"
  width="300px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}


We use MAPmap, a **m**itogen-**a**ctivated **p**rotein (MAP) kinase-based whole-brain immunostaining technique to gain insights into brain region-specific structural and activity profiles. The staining of total ERK (tERK, the MAP kinase) is used with morphometry algorithms to register image data to a reference atlas; the amount of consistent shrinkage/expansion across fish in certain areas can indicate region-specific neurodevelopmental problems or lesions associated with disease. The phosphorylated form (pERK) is an indirect readout for recent bursts of increased neural activity. The ratio between pERK/tERK can then be used to gauge changes in the coordination of brain excitability across regions, fish, and experimental groups, providing insights into how our manipulations impact brain function. All this information can be referred back to the zbrain reference atlas, where comprehensive gene and protein -specific whole-brain staining information is available and parcellated into defined neuroanatomical designations. By using this resource, we are able to contextualise and formulate new hypotheses based on gene/protein expression and colocolisation patterns to further our understanding of brain function.


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


Gout and circadian rhythm have a complex interplay, demonstrated through multiple aspects of gout flares being dependent on circadian patterns.  Utilizing zebrafish as a model organism, we are interested in creating gene knockouts of gout-associated regions and investigating the effects that these knockouts have on circadian-related phenotypes. We use DanioVision (Noldus) technology to analyze larval zebrafish behavior in large-scale experiments with up to ninety-six larvae per condition. By tracking cumulative movement over multiple days and startle responses to dark flashes and auditory stimuli, we assess how genetic modifications impact behavior. Comparing homozygous and heterozygous gene knockouts to wild-type controls helps us identify circadian rhythm abnormalities in sibling populations, characterizing the impact that removal of these gene regions have in respect to circadian activity.


{% include float.html clear=false %}
