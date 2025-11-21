---
title: "Biopython Project Update 2017"
authors:
- Sourav Singh
- cbrueffer
- Peter Cock
- The Biopython Contributors

date: 2017-07-26
doi: "10.7490/f1000research.1114502.1"

add_badge: true

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*F1000Research 2017, 6(ISCB Comm J):1238 (slides)*"
#publication_short: ""

abstract: "The Biopython Project is a long-running distributed collaborative effort, supported by the Open Bioinformatics Foundation, which develops a freely available Python library for biological computation [1]. We present here details of the Biopython releases since BOSC 2016, namely Biopython 1.68, 1.69 and 1.70. Together these had 82 named contributors including 51 newcomers which reflects our policy of trying to encourage even small contributions.<br />

Biopython 1.68 (August 2016) was a relatively small release, with the main new feature being support for RSSB’s new binary Macromolecular Transmission Format (MMTF) for structural data.<br />

Biopython 1.69 (April 2017) represents the start of our re-licensing plan, to transition away from our liberal but unique Biopython License Agreement to the similar but very widely used 3-Clause BSD License. We are reviewing the code base authorship file-by-file, in order to gradually dual license the entire project. Major new features include: a new parser for the ExPASy Cellosaurus cell line database, catalogue and ontology; support for the UCSC Multiple Alignment Format (MAF), FSA sequencing files, version 4 of the Affymetrix CEL format; updates to the REBASE February 2017 restriction enzyme list; Bio.PDB.PDBList now can download more formats including MMTF; enhanced PyPy support by taking advantage of NumPy and compiling most of the Biopython C code modules.<br />

Biopython 1.70 (July 2017) has internal changes to better support the now standard pip tool for Python package installation. Major new features include: support for Mauve’s eXtended Multi-FastA (XMFA) file format, updates to our BLAST XML and MEME parsers, ExPASy support, and phylogenetic distance matrices. This release is noteworthy for our new logo, contributed by Patrick Kunzmann. This draws on our original double helix logo, and the blue and yellow colors of the current Python logo.<br />

All releases fixed miscellaneous bugs, enhanced the test suite, and continued efforts to follow the PEP8 and PEP257 coding style guidelines which is now checked automatically with GitHub-integrated continuous integration testing using TravisCI. We now also use AppVeyor for continuous integration testing under Windows. Current efforts include improving the unit test coverage, which is easily viewed online at CodeCov.io."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Biopython
- Bioinformatics
- Open Source Software
featured: false

links:
- name: "PDF"
  url: "https://f1000research.com/slides/6-1238#"
  icon: "file-pdf"
#url_pdf: ""
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
          data-doi="10.7490/f1000research.1114502.1"
          data-hide-zero-citations="true"
          data-legend="always">
        </span>
      <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
        <div style="float:right";
          data-link-target="_blank"
          data-badge-details="right"
          data-badge-type="medium-donut"
          data-doi="10.7490/f1000research.1114502.1"
          data-condensed="true"
          data-hide-no-mentions="true"
          class="altmetric-embed">
        </div>
    </div>
  </section>
