---
title: Measuring the impact of a successful DDoS attack on the customer behaviour
  of managed DNS service providers

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Abhishta Abhishta
- Roland \Van Rijswijk-Deij\
- \Lambert J.M.\ Nieuwenhuis

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-14T21:20:15.844170Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computer communication review*'
publication_short: ''

doi: 10.1145/3310165.3310175

abstract: Distributed Denial-of-Service (DDoS) attacks continue to pose a serious
  threat to the availability of Internet services. The Domain Name System (DNS) is
  part of the core of the Internet and a crucial factor in the successful delivery
  of Internet services. Because of the importance of DNS, specialist service providers
  have sprung up in the market, that provide managed DNS services. One of their key
  selling points is that they protect DNS for a domain against DDoS attacks. But what
  if such a service becomes the target of a DDoS attack, and that attack succeeds?
  In this paper we analyse two such events, an attack on NS1 in May 2016, and an attack
  on Dyn in October 2016. We do this by analysing the change in the behaviour of the
  service's customers. For our analysis we leverage data from the OpenINTEL active
  DNS measurement system, which covers large parts of the global DNS over time. Our
  results show an almost immediate and statistically significant change in the behaviour
  of domains that use NS1 or Dyn as a DNS service provider. We observe a decline in
  the number of domains that exclusively use NS1 or Dyn as a managed DNS service provider,
  and see a shift toward risk spreading by using multiple providers. While a large
  managed DNS provider may be better equipped to protect against attacks, these two
  case studies show they are not impervious to them. This calls into question the
  wisdom of using a single provider for managed DNS. Our results show that spreading
  risk by using multiple providers is an effective countermeasure, albeit probably
  at a higher cost.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Customer Behaviour
- DDoS Attacks
- Domain Name System
- Dyn
- Economic Impact
- NS1
- 22/3 OA procedure

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
