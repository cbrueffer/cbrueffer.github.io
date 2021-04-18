---
title: "A crowdsourced set of curated structural variants for the human genome"
authors:
- Lesley M. Chapman
- Noah Spies
- Patrick Pai
- Chun Shen Lim
- Andrew Carroll
- Giuseppe Narzisi
- Christopher M. Watson
- Christos Proukakis
- Wayne E. Clarke
- Naoki Nariai
- Eric Dawson
- Garan Jones
- Daniel Blankenberg
- cbrueffer
- Chunlin Xiao
- Sree Rohit Raj Kolora
- Noah Alexander
- Paul Wolujewicz
- Azza Ahmed
- Graeme Smith
- Saadlee Shehreen
- Aaron M. Wenger
- Marc Salit
- Justin M. Zook

date: 2020-06-19
doi: "10.1371/journal.pcbi.1007933"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*PLoS Computational Biology, 2020. 16(6):e1007933*"
#publication_short: ""

abstract: "A high quality benchmark for small variants encompassing 88 to 90% of the reference genome has been developed for seven Genome in a Bottle (GIAB) reference samples. However a reliable benchmark for large indels and structural variants (SVs) is more challenging. In this study, we manually curated 1235 SVs, which can ultimately be used to evaluate SV callers or train machine learning models. We developed a crowdsourcing app--SVCurator--to help GIAB curators manually review large indels and SVs within the human genome, and report their genotype and size accuracy. SVCurator displays images from short, long, and linked read sequencing data from the GIAB Ashkenazi Jewish Trio son [NIST RM 8391/HG002]. We asked curators to assign labels describing SV type (deletion or insertion), size accuracy, and genotype for 1235 putative insertions and deletions sampled from different size bins between 20 and 892,149 bp. ‘Expert’ curators were 93% concordant with each other, and 37 of the 61 curators had at least 78% concordance with a set of ‘expert’ curators. The curators were least concordant for complex SVs and SVs that had inaccurate breakpoints or size predictions. After filtering events with low concordance among curators, we produced high confidence labels for 935 events. The SVCurator crowdsourced labels were 94.5% concordant with the heuristic-based draft benchmark SV callset from GIAB. We found that curators can successfully evaluate putative SVs when given evidence from multiple sequencing technologies."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Genome in a Bottle
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: "https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1007933&type=printable"
url_preprint: "https://www.biorxiv.org/content/10.1101/581264v3"
url_code: "https://github.com/lesleymaraina/svcurator"
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
projects: []

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
          data-doi="10.1371/journal.pcbi.1007933"
          data-hide-zero-citations="true"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.1371/journal.pcbi.1007933"
          data-condensed="true"
          data-hide-no-mentions="true"
          class="altmetric-embed">
        </div>
    </div>
  </section>
