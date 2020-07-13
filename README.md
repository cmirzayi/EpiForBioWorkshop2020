# Epidemiology for Bioinformaticians

# Instructor(s) name(s) and contact information

Chloe Mirzayi, cmirzayi@gmail.com
Levi Waldron, levi.waldron@sph.cuny.edu
CUNY School of Public Health, 55 W 125th St, New York, NY 10027

# Workshop Description

Concepts of causal inference in epidemiology have important ramifications for studies across bioinformatics and other fields of health research. In this workship, we introduce basic concepts of epidemiology, study design, and causal inference for bioinformaticians. Emphasis is placed on addressing bias and confounding as common threats to assessing a causal pathway in a variety of study design types and when using common forms of analyses such as GWAS and survival analysis. Workshop participants will have the opportunity to create their own structural causal models (DAGs) and use this model to determine how to assess an estimated causal effect. Examples using DESeq2, edgeR, and limma will be used to show how multivariable models can be fitted depending on the hypothesized causal relationship.

Presented successfully at BioC2019 to 30 people, updates that material by adding a brief demonstration of ggdag, revised conceptual emphasis based on participant feedback, and applied examples using data from curatedMetagenomicData.

## Pre-requisites

* Basic knowledge of R syntax
* Familiarity with regression

## Workshop Participation

Students will have the opportunity to solve toy problems and execute example code in R.

## _R_ / _Bioconductor_ packages used

* daggity
* ggdag
* DESeq2
* edgeR
* limma
* curatedMetagenomicData

## Time outline


| Activity                     | Time |
|------------------------------|------|
| Counterfactuals              | 10m  |
| Causal Inference	           | 10m  |
| Bias and Confounding	       | 15m  |
| Making DAGs in R             | 10m  |
| Example using cMD            | 15m  |


# Workshop goals and objectives

## Learning goals

* Describe the differences in common experimental and observational study designs
* Apply concepts of study design to common analyses in bioinformatics such as GWAS and survival analysis
* Understand key concepts of epidemiology such as causal inference, confounders, collidors, mediators, counterfactuals, and study designs
* Develop a structural causal diagram/directed acyclic graph (DAG) of causal relationships and assess pathways of interest
* Analyze metagenomic data using principles of causal inference to properly adjust for potential confounders

## Learning objectives

* Assess a study design in terms of causal inference
* Learn about path blocking to prevent confounding
* Create a DAG in R using daggity and ggdag
* Identify situations when multivariate adjustment for variables is inappropriate
* Specify a model based on a DAG and then fit that model to data using DESeq2, edgeR, and limma