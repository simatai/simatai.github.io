---
title: Existing datasources on antibiotic resistance research
date: 2017-02-27
layout: post
---

I surveyed existing, publicly available data sources that could be sources for data to be fed into models. 

### Databases specific to antibiotics resistance research

[Pathosystems Resource Integration Center](https://www.patricbrc.org/) collects ''known antibiotic resistance genes from reputed external databases and publications'' and ''incorporates antibiotic susceptibility testing results as additional genome metadata.'' It also contains the genomes of bacteria. Its data was used in [https://arxiv.org/pdf/1607.01224.pdf](https://arxiv.org/pdf/1607.01224.pdf).

[Comprehensive Antibiotic Resistance Database, CARD](https://card.mcmaster.ca/home) is a database of resistance genes, their products and associated phenotypes. It was used e.g. in [10.3389/fmicb.2016.01887](https://doi.org/10.3389/fmicb.2016.01887), but seemed not to perform well on their specific sample when it came to predicting resistance in phenotypes from genome information.

[Resfams](http://www.dantaslab.org/resfams/) was closest to the phenotypic results in [10.3389/fmicb.2016.01887](https://doi.org/10.3389/fmicb.2016.01887) [it should really be noted that eh, the authors of the paper work for the same institution as the guys building Resfams].

[ResFinder](https://cge.cbs.dtu.dk/services/ResFinder/) 

[Antibiotic Resistance Genes Database, ARGD](https://ardb.cbcb.umd.edu/) is no longer maintained (last update 2009), all data can be found in CARD. Flat files are available for download.

### Bacterial genomics

[One Codex](https://www.onecodex.com/) is a data platform for applied microbial genomics, where you can also ''search the world's largest index of bacterial, viral, and fungal genomes''.

### Databases on molecular interactions

[MOAD](http://bindingmoad.org/)

MOAD was the basis for the work by [Durrant et al.](https://amarolab.ucsd.edu/~jdurrant/) mentioned in their review article [10.1111/cbdd.12423](https://doi.org/10.1111/cbdd.12423). Around 2011 they built ANNs called NNScore1 and NNScore2 to predict binding of some ligand to a drug target in bacteria. Their approach has since been used in multiple further studies. MOAD is a subset of the [Protein Data Bank (PDB)](http://www.rcsb.org/pdb/home/home.do) and deals specifically with ligand-protein binding.

[PDBbind-CN](http://www.pdbbind.org.cn/)

PDBbind-CN is another database on protein binding mentioned in [10.1111/cbdd.12423](https://doi.org/10.1111/cbdd.12423). It contains binding affinity data for all types of biomolecular complexes.

### Molecular structure and small molecules

[PubChem](https://pubchem.ncbi.nlm.nih.gov/search/) also records bioactivity of compounds.

[Chembl](https://www.ebi.ac.uk/chembl/)






