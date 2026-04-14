---
title: 'A simulation-based procedure to estimate base rates from Covid-19 antibody
  test results I: Deterministic test reliabilities'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Reinoud Joosten
- Abhishta Abhishta

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-14T21:20:15.878965Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- report

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: ''

abstract: 'We design a procedure (the complete Python code may be obtained at https://github.com/abhishta91/antibody_montecarlo)
  using Monte Carlo (MC) simulation to establish the point estimators described below
  and confidence intervals for the base rate of occurence of an attribute (e.g., antibodies
  against Covid-19) in an aggregate population (e.g., medical care workers) based
  on a test. The requirements for the procedure are the testtextquoterights sample
  size (N) and total number of positives (X), and the data on testtextquoterights
  reliability. The modus generates the largest frequency of observations in the MC
  simulation with precisely the number of test positives (maximum- likelihood estimator).
  The median is the upper bound of the set of priors accounting for half of the total
  relevant observations in the MC simulation with numbers of positives identical to
  the testtextquoterights number of positives. Our rather preliminary findings are:
  • The median and the confidence intervals suffice universally. • The estimator X/N
  may be outside of the two-sided 95% confidence interval. • Conditions such that
  the modus, the median and another promising estimator which takes the reliability
  of the test into account, are quite close. • Conditions such that the modus and
  the latter estimator must be regarded as logically inconsistent. • Conditions inducing
  rankings among various estimators relevant for issues concerning over- or underestimation.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- base rates
- Monte Carlo simulation
- Covid-19
- tests

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
