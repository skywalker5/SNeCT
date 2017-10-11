# SNeCT

Overview
---------------

Integrative analysis of multiple perspective of a patient helps in both cancer stratification and clinical predictions. Stratification help the researchers in understanding and exploring the genomic characteristics in relationship with their current phenotypes and thus to recognize opportunities for clinical improvement on stratified groups of patients. In the perspective of personalized medicine, clinical diagnostics and predictions of individual patient is needed and can be done by searching the integrated profile of patient to existing records. In cancer data analysis, an improved stratification and clinical prediction can be achieved by integrative analysis of the multi-platform data such as copy number alteration (CNA), somatic mutation, gene expression, DNA methylation, and microRNA (miRNA) data.

![scheme_img](/img/scheme.png)


Paper
---------------

**SNeCT: Integrative cancer data analysis via large scale network constrained tensor decomposition**  
[Dongjin Choi](https://skywalker5.github.io/), [Sael Lee](http://www3.cs.stonybrook.edu/~sael/)  
[[PDF](/paper/SNeCT.pdf), [Supplementary material](/paper/SNeCT.pdf)]

Code
---------------
See Github repository for [SNeCT_Code](https://github.com/skywalker5/SNeCT_code)


Data
---------------
| Name | Structure | Size | Number of Entries | Download |
| :------------ | :-----------: | :-------------: |------------: |:------------------: |
| PanCan12     | Patient - Gene - Platform | 4,555 &times; 14,351 &times; 5 | 183,211,020 | [DOWN](https://datalab.snu.ac.kr/data/SNeCT/pancan12_tensor.tar.gz) |
| Pathway    | Gene - Gene | 14,351 &times; 14,351 | 665,429 | [DOWN](https://datalab.snu.ac.kr/data/SNeCT/pathway_network.tar.gz) |
