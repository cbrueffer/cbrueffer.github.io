---
title: "TopHat-Recondition: A post-processor for TopHat unmapped reads"
authors:
- cbrueffer
- Lao H. Saal

date: 2016-05-04
doi: "10.1186/s12859-016-1058-x"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Bioinformatics, 2016. 17(1):199*"
#publication_short: ""

abstract: "TopHat is a popular spliced junction mapper for RNA sequencing data, and writes files in the BAM format – the binary version of the Sequence Alignment/Map (SAM) format. BAM is the standard exchange format for aligned sequencing reads, thus correct format implementation is paramount for software interoperability and correct analysis. However, TopHat writes its unmapped reads in a way that is not compatible with other software that implements the SAM/BAM format. We have developed TopHat-Recondition, a post-processor for TopHat unmapped reads that restores read information in the proper format. TopHat-Recondition thus enables downstream software to process the plethora of BAM files written by TopHat. TopHat-Recondition can repair unmapped read files written by TopHat and is freely available under a 2-clause BSD license on GitHub: https://github.com/cbrueffer/tophat-recondition."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- RNA Sequencing
- Open Source Software
- PhD
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://bmcbioinformatics.biomedcentral.com/track/pdf/10.1186/s12859-016-1058-x"
url_preprint: "https://biorxiv.org/content/early/2015/12/02/033530"
#url_preprint: ""
#url_code: ""
#url_dataset: ""
#url_project: ""
#url_slides: ""
#url_video: ""
#url_poster: ""
#url_source: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [phd]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<html>
  <style>
    section {
        background: white;
        color: black;
        border-radius: 1em;
        padding: 1em;
        left: 50% }
    #inner {
        display: inline-block;
        display: flex;
        align-items: center;
        justify-content: center }
  </style>
  <section>
    <div id="inner">
      <script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>
        <span style="float:left";
          class="__dimensions_badge_embed__"
          data-doi="10.1186/s12859-016-1058-x"
          data-hide-zero-citations="true"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div  style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.1186/s12859-016-1058-x"
          data-condensed="true"
          data-hide-no-mentions="true"
          class="altmetric-embed">
        </div>
    </div>
  </section>

