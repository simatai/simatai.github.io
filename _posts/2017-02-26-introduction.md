---
title: "Intro: the what & the why"
date: 2017-02-26
layout: post
---

## Antibiotic resistance is a problem
... which is why this blog will be dedicated to reporting work on **applications of Machine Learning and methods of Artificial Intelligence to the problem of antibiotics resistance**. There was a recent *[Call to Arms on arxiv](https://arxiv.org/pdf/1607.01224.pdf)*, and since I was looking for an interesting and important problem to spend some leisure on, I thought this is it. 

## Research agenda

+ *Understand the work that's out there already*.
  There is quite a bit of work already out there, which [I shall review here](https://simatai.github.io/2017/02/28/literature-review.html).
 
+ *Understand the basics of how antibiotics work*. 
  I'll write several summaries on attack vectors on bacterial infections. One of them obviouly being broad-band antibiotics, of which   plenty are already on the brink of uselessness. I'll try to understand how the biochemistry works and how Machine learning could possibly help to get from genetic information to predicting or constructing new antibiotics. That's quite ambitious, but hey.

+ *Summarize the available data*.
  Most of the work I've seen so far relied on existing databases of gene, protein and ligand/receptor characteristics etc. I put together a [list of publicly accessible databases](https://simatai.github.io/2017/02/27/existing-datasources.html) that we could use data from to feed into prediction & construction algorithms (- one obvious although probably slow construction algorithm would be genetic programming, others would be different heuristics search techniques from AI)
  
+ *Build some models with hopefully interesting output* both potentially about the biochemical side of the problem, visualizing the spread of the problem, visualizing antibiotics usage, and finally do some research how available data can be transformed into insights where to run actual experiments.
  
While no less important, the following issues will be less in the focus of this work:

+ *antibiotics resistance is a social problem* brought about by unfavorable, long-standing patterns in prescriptions, high and rising meat consumption by the Worlds middle and upper class (antibiotics are in widespread use in agriculture). The rise of multi-resistant bacterial strains is a problem of hospital hygiene management.

+ *discovering antibiotics is one thing, getting them to market quite another*. The pharamceutical industry has mostly exited antibiotics research in favor of research on treatments of chronic diseases (those have far higher net present values). That represents a huge market failure, not only because it is quite cynical, but also because it means that the entire professional and efficient chain of production to scale any discovery in the academic sector is not available for new antibiotics.


