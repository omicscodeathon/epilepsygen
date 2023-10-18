# Integrative Transcriptomic Analysis for the Identification of Novel Epilepsy Candidate Genes

## Background
Epilepsy is a chronic neurological disorder characterized by recurrent seizures, that affects millions of individuals worldwide. Despite significant advancements in our understanding of epilepsy pathophysiology, the underlying genetic factors contributing to its development and progression remain incompletely elucidated. Genetic studies have revealed a complex interplay of various genes and molecular pathways, emphasizing the need for comprehensive and integrative approaches to identify novel candidate genes that contribute to epileptogenesis.
The advent of high-throughput genomics technologies has revolutionized our ability to explore the intricate genetic landscape of epilepsy. Integrating diverse genomic datasets, such as gene expression profiles, genetic variants, and epigenetic modifications, can provide a holistic view of the molecular mechanisms underlying this disorder. In this study, we present a comprehensive analysis utilizing integrative genomic and bioinformatics methodologies to identify novel candidate genes associated with epilepsy.

## General Objective
Identify novel candidate genes associated with epilepsy using integrative transcriptomic data analysis.

## Specific Objectives
- Identify differentially expressed genes (DEGs) between patients with epilepsy and healthy controls.
- Perform functional enrichment analysis to identify genes that are involved in related biological pathways.

## Workflow
![image](https://github.com/omicscodeathon/epilepsygen/blob/main/figures/Methods.jpeg?raw=true)
## Results
### Gene set enrichment analysis
![image](https://github.com/omicscodeathon/epilepsygen/blob/main/figures/GO_plot.jpg)

### Protein-Protein interaction network
![image](https://github.com/omicscodeathon/epilepsygen/blob/main/figures/Protein%20protein%20interation.png)

### Potential candidates genes
| Genes | Log2FC | FDR | Expression | Gene description|
|-------|--------|-----|------------|-----------------|
|QKI    | 3.284  | 0.063222 | Up regulated | QKI, KH domain containing RNA binding |
|PARD3 | 3.166 | 0.020429 | Up regulated | Par-3 family cell polarity regulator |
|PIKFYVE | 2.592 | 0.091118 | Up regulated | Phosphoinositide kinase, FYVE-type zinc finger containing|
|PALS1 | 2.467 | 0.095185 | Up regulated | Protein associated with LIN7 1|
|ITGB4 | 1.803 | 1.36E-13 |  Up regulated | Integrin subunit beta 4|
|EGR2 | 1.594 | 0.001439 | Up regulated | Early growth response 2|
|MAG | 1.320 | 0.001133 | Up regulated | Myelin associated glycoprotein|
|MYRF | 1.235 | 0.004840 | Up regulated | Myelin regulatory factor|
|POU3F1 | 1.232 | 0.001828 | Up regulated | POU class 3 homeobox 1|
|GAL3ST1 | 1.102 | 9.16E-04 | Up regulated | Galactose-3-O-sulfotransferase 1|
|MPZ | 1.099 | 0.037204 | Up regulated | Myelin protein zero|
|MBP | 1.099 | 0.029077 | Up regulated | Myelin basic protein|
|MAL | 1.030 | 0.001031 | Up regulated | Mal, T cell differentiation protein|
|ITGAX | 1.008 | 1.340E-05 | Up regulated | Integrin subunit alpha X|
|SLC17A6 | -1.932 | 2.033E-04 | Down Regulated | Solute carrier family 17 member 6|
|RGS4 | -1.408 | 6.510E-07 | Down Regulated | Regulator of G Protein Signalling 4|
|VIP | -1.236 | 7.820E-05 | Down Regulated | Vasoactive Intestinal Peptide|
|SLC9A2 | -1.094 | 1.820E-05 | Down Regulated |Solute carrier family 9 member A2|


## Team
1. [Modibo K. Goita](https://github.com/mkgoita) - Team-lead

1. [Nicholas Donkor](https://github.com/Nick-Donkor) - Co-lead
2. Diana Karan - Writer (Manuscript)
3. Lassana Coulibaly - Member
4. Pius Kwesi Sam - Member
5. Awe Olaitan - African Society for Bioinformatics and Computational Biology, South Africa
