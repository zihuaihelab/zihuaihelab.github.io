---
permalink: /
title: "GWAS Enhancement with Multiple Knockoffs Inference: "Ghost Knockoffs""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Recent advances in genome sequencing and imputation technologies provide an exciting opportunity to study the contribution of genetic variants to disease phenotypes, but our ability to explain heritability and to translate genetic risk into mechanistic insight remains limited at this point. In our recent paper that can be found here https://google.com, we propose a multiple knockoffs inference to enhance the discovery of genome-wide association studies (GWAS), by improving its statistical power for locus discovery and its resolution at each locus to prioritize the putative causal variants. 

Our Software nicknamed "GhostKnockoff" is free to use and publicly available. The GitHub can be found at this link: https://google.com and further information about its context, use, and communication with authors is on this page. 

About
======
We develop a method to perform knockoff-based inference without generating any individual-level knockoffs. The method requires only summary statistics (Z-score) from conventional GWAS and retains useful features of knockoff-based inference. The method additionally allows meta-analysis of studies with arbitrary sample overlapping. It is also robust to genetic variants that do not show up in all studies, and therefore applicable to the integration of genetic association studies genotyped using SNP-array, whole exome-sequencing and whole genome sequencing. 

Getting started
======
1. First clone the repository 
2. 
3. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
4. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
5. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
6. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
7. Check status by going to the repository settings, in the "GitHub pages" section

Tips
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Cite Us
======
Please cite us referencing this paper: https://nature.com

For more info
------
Don't hesitate to reach out to our research group using the following emails: zihuai@stanford.edu, etc. 
