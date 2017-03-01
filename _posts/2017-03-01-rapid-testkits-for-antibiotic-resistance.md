---
layout: post
date: 2017-03-01
title: Current developments on rapid test kits for antibiotics resistance detection
---

One pretty obvious approach to the [important problem of testing for AMR strains in clinics](https://longitudeprize.org/challenge/antibiotics)
is to sequence the genome and then tweak and apply known ML algorithms to detect if a given bacterial DNA shows resistance genes (I daresay
obvious because it occured to me pretty soon after reading into the problem).

[These guys](https://doi.org/10.1038/ncomms10063) did it, but it is still taking pretty long. I had been wondering about the timeline from 
sampling from a patient to sequencing to diagnosis, and they provide an excellent overview where the bottlenecks are.

In fact I had thought about combining the awesome [Nanopore sequencer](https://nanoporetech.com/) available for 1000 USD (!) with 
[known ML](https://simatai.github.io/2017/02/28/literature-review/) to produce such a device -- but I guess someone else will be 
faster so it might be something for a [:Make](http://www.makezine.com). I don't know [if my thesis supervisors DNA 
multiplier](http://prl.aps.org/abstract/PRL/v104/i18/e188102) might 
actually work to multiply k-mers from bacterial DNA fast and safely enough to feed into the Nanopore device.

