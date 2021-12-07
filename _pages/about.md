---
permalink: /
title: "Ghost Knockoffs: an enhanced GWAS approach"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Recent advances in genome sequencing and imputation technologies provide an exciting opportunity to study the contribution of genetic variants to disease phenotypes, but our ability to explain heritability and to translate genetic risk into mechanistic insight remains limited at this point. In our recent [paper](https://google.com), we propose a multiple knockoffs inference to enhance the discovery of genome-wide association studies (GWAS), by improving its statistical power for locus discovery and its resolution at each locus to prioritize the putative causal variants. 

Our Software nicknamed **"GhostKnockoff"** is free to use and publicly available. The [GitHub](https://sosaar@github.com) has all pertinent code and dependencies. 

About
======
We develop a method to perform knockoff-based inference without generating any individual-level knockoffs. The method requires only summary statistics (Z-score) from conventional GWAS and retains useful features of knockoff-based inference. The method additionally allows meta-analysis of studies with arbitrary sample overlapping. It is also robust to genetic variants that do not show up in all studies, and therefore applicable to the integration of genetic association studies genotyped using SNP-array, whole exome-sequencing and whole genome sequencing. 

![Alt text](esgwas_workflow.png?raw=true "Title")

The UK Biobank analysis demonstrates superior performance of the proposed method compared to conventional GWAS in both statistical power (2.05-fold [95% CI, 1.5 to 2.6] more discoveries) and localization of putative causal variants at each locus (46% [95% CI, 34% to 58%] less proxy variants due to linkage disequilibrium). The AD meta-analysis identified 55 risk loci, with ~70% of the proximal genes at these loci showing suggestive signal in downstream single-cell transcriptomic analyses.

Terms
======
When using GhostKnockoff inference in your work, please cite our [flagship paper](https://nature.com)

Authors
======
Zihuai He, Linxi Liu, Michael E. Belloy, Yann Le Guen, Aaron Sossin, Xiaoxia Liu, Xinran Qi, Shiyang Ma, Tony Wyss-Coray, Hua Tang, Chiara Sabatti, Emmanuel Candès, Michael D. Greicius, Iuliana Ionita-Laza


Communication
=====
Don't hesitate to reach out to our research group using the following emails: zihuai@stanford.edu, sosaar@stanford.edu
