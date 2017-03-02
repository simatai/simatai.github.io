---
title: "Literature review 1"
date: 2017-02-28
layout: post
---

I surveyed existing literature and applications of Machine Learning on the problem of antibiotics resistance. While two teams focused on predicting resistance characteristics from genome data, one team applied ML to ligand/receptor binding data to aid drug discovery. I also put together information on known biochemical mechanisms of antibiotics and a few references on in-silico experiments in drug discovery or antibiotics resistance.

### Introductory articles on the why, what and social mechanisms

[The Antibiotic Resistance Crisis Part 1: Causes and Threats](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4378521/)



### Machine learning and AI in drug and antibiotics discovery

Santerre, [Stevens](https://www.anl.gov/contributors/rick-stevens) et al. (2016): **[Machine Learning for Antimicrobial Resistance](https://arxiv.org/pdf/1607.01224.pdf)** used genome data from the [PATRIC](https://www.patricbrc.org) database to train a random forest to predict if a given genome leads to a phenotype resistant to antibiotics. PATRIC contains annotated genomes, i.e. there are labels available like ''susceptible to antibiotics'' versus ''non-susceptibe''. They were able to generate a list of top gene regions potentially responsible for AMR (by PATRIC ID), identified from feature importance calculated using RF (the paper shows example for tuberculosis MTB).

[Durrant](https://amarolab.ucsd.edu/~jdurrant/) and Amaro (2015): **[Machine-Learning Techniques Applied to Antibacterial Drug Discovery](https://doi.org/10.1111/cbdd.12423)** reviews work in which not the genome was the predicting variable of resistance but descriptions of small-scale molecular interaction (using data on ligands or receptors from the [MOAD](https://simatai.github.io/2017/02/27/existing-datasources/) database). The resulting models ([QSARs](https://en.wikipedia.org/wiki/Quantitative_structure–activity_relationship)) could accurately predict experimentally measured binding affinities from the receptor-ligand descriptors. Also available from [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4273861/).
 
[Pesesky](http://www.dantaslab.org/people/) et al. (2016): **[Evaluation of Machine Learning and Rules-Based Approaches for Predicting Antimicrobial Resistance Profiles in Gram-negative Bacilli from Whole Genome Sequence Data](https://doi.org/10.3389/fmicb.2016.01887)**
tries to come up with a *genotype-based antibiotic susceptibility prediction (GBASP)* algorithm (i.e. predict resistance from the genome rather than the phenotype) that ''could more rapidly provide all of the information given by current phenotypic AST methods'' (i.e. grow'em kill'em-lab-approach), especially susceptibility information. They used the whole genome as input into their models (one ML, one rules-based, probably a decision tree?). They also [reviewed data quality and congruence across several genomics databases](https://simatai.github.io/2017/02/27/existing-datasources/). To *translate resistance gene identifications into resistance and susceptibility predictions*, they compared a rules-based algorithm to a machine learning approach on the ''resistance profiles of 78 previously characterized genome-sequenced Enterobacteriaceae isolates (Pesesky et al., 2015) to 12 antibiotics.''

Coelho et al. (2013): **[The Use of Machine Learning Methodologies to Analyse Antibiotic and Biocide Susceptibility in Staphylococcus aureus](http://dx.doi.org/10.1371/journal.pone.0055582)** attempted to predict susceptibility of S. aureus to antibiotics from the concentration of other poison needed to kill it. They needed a decision tree and ML to come up with rules of the kind *if poison at Level x stops 'em from growing, antibiotics will work*: ''Whereas most independent variables, including region and year of collection, were not the ones that better discriminate antibiotic susceptibility, the MICs of two common biocides chlorhexidine (CLX) and benzalkonium chloride (BZC) are the best predictors of susceptibility and non-susceptibility to each of the 13 antibiotics''. They built their own data set. While the result looks simple, its **technological/diagnostics application could be significant**: MICs (minimal inhibitory concentration) are quite easy to measure, so you could build a kit to measure MICs to the two biocides and decide on the spot if an antibiotic might work or not.

Yang et al. (2016): **[ARGs-OAP: online analysis pipeline for antibiotic resistance genes detection from metagenomic data using an integrated structured ARG-database](https://doi.org/10.1093/bioinformatics/btw136)** I have no access to this article. The resulting software can be found [here](http://smile.hku.hk/SARGs).

### In silico experiments on drug resistance

**[New insights into bacterial adaptation through in vivo and in silico experimental evolution](https://doi.org/10.1038/nrmicro2750)**

### Mechanisms of antibiotic resistance

[Mechanisms of bacterial persistence during stress and antibiotic exposure](10.1126/science.aaf4268)

On the SOS pathway:

https://doi.org/10.1111/1574-6976.12077

Jun Lin (ed.) et al. [*Mechanisms of antibiotic resistance*](http://www.frontiersin.org/books/Mechanisms_of_antibiotic_resistance/547) (2015)
The book is available for free from Frontiers. At first glance a pretty disappointing collection of seemingly random articles somehow related to the overall topic.

### Technology and resistance diagnostics

[Rapid point of care diagnostic tests for viral and bacterial respiratory tract infections—needs, advances, and future prospects](http://dx.doi.org/10.1016/S1473-3099(14)70827-8)

