---
title: "Practical Security Event Auditing with FreeBSD"
event: "NYCBSDCon 2010"
event_url: "http://www.nycbsdcon.org/2010/presentations.html"

location: "New York City, USA"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2010-11-14T10:00:00Z"
date_end: "2010-11-14T11:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "http://www.nycbsdcon.org/2010/presentations/nycbsdcon-freebsd-audit.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- freebsd

# Enable math on this page?
math: false

abstract: "<p>Security event auditing refers to the reliable and secure logging of security-related system events. It allows for post mortem analysis or live monitoring of system intrusions, as well as intrusion detection. It is also an essential part of the Common Access Protection Profile (CAPP) for Common Criteria (CC), a certification necessary for a system to be used in certain critical environments.</p>

<p>Auditing support has been around for a long time in commercial Unix systems like Solaris. In the BSD world however, it is a relatively unknown and new concept. Starting from version 6.2, FreeBSD provides support for it by means of the audit(4) kernel subsystem.</p>

<p>This talk aims at introducing the FreeBSD audit(4) facility, its supporting tools and benefits, as well as its limitations.</p>"
---
