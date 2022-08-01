---
title: SCAN-B MutationExplorer
summary: "A web-based application for exploring tumor somatic mutations."
tags:
- Cancer
- Breast Cancer
- RNA Sequencing
- Open Source Software
- PhD
date: "2020-02-04T00:00:00Z"

image:
  placement: 1
  #caption: "SCAN-B MutationExplorer"
  focal_point: Smart
  preview_only: false
---

- URL: https://oncogenomics.bmc.lu.se/MutationExplorer
- Source code: https://github.com/cbrueffer/MutationExplorer (2-clause BSD license)

To facilitate research cancer datasets these days get ever larger. Within the [Sweden Cancerome Analysis Network--Breast][scanb] thousands of
breast tumors have already undergone [RNA sequencing], and the number grows daily.  In a [recent research project](../../publication/scanb_mutational_landscape_primary_bc/)
we demonstrated that this data can be used to call somatic mutations, which can e.g. help guide patient treatment or be used as targets for detecting [circulating tumor DNA][ctDNA] in
patient blood samples.

As part of this project we provide the web portal [SCAN-B Mutationexplorer][mutationexplorer] to enable the exploration of mutations from 3,217 primary breast tumor transcriptomes.
The underlying software, MutationExplorer, is freely available on GitHub and can be adapted to other datasets.

[mutationexplorer]: https://oncogenomics.bmc.lu.se/MutationExplorer
[RNA sequencing]: https://en.wikipedia.org/wiki/RNA-Seq
[scanb]: https://www.scan-b.lu.se/
[ctDNA]: https://en.wikipedia.org/wiki/Circulating_tumor_DNA
