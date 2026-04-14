---
title: Measuring Malware Detection Capability for Security Decision Making

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- \Muhammad Yasir Muzayan\ Haq
- Abhishta Abhishta
- Sander Zeijlemaker
- Annette Chau
- Michael Siegel
- \Lambert J.M.\ Nieuwenhuis

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-14T21:20:16.007168Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: ''

abstract: Organizations face an urgent need to bolster their cybersecurity defenses
  against the rising threat of ransomware. Implementing advanced antivirus and antimalware
  tools is crucial for proactive identification and mitigation of malicious software.
  However, adversaries constantly refine malware to evade detection increasing the
  complexity of the threat. Hence, developing an effective strategy is nontrivial.
  To address this challenge, this study conducts various analyses on scan results
  of publicly shared malware samples. Utilizing metadata from 635K samples sourced
  from MalwareBazaar and scan results from VirusTotal, we assign family labels using
  AVClass. Additionally, we examine a 90-day longitudinal dataset alongside the main
  dataset. Our findings demonstrate that while over 60% of scanner engines detect
  67% of samples, certain malware families consistently exhibit lower detection rates.
  Detection capability improves over time, particularly within the initial 30 days,
  but remains inadequate for specific families. Furthermore, we observe that some
  scanner engines demonstrate nearly flawless detection capability across all malware
  families, while the majority struggle with efficiently detecting certain types.
  Moreover, we performed Monte Carlo simulations and revealed that employing multiple
  scanner engines substantially enhances detection capability, with 3 to 7 scanners
  being optimal. Finally, simulation analysis in a case study highlights the significant
  impact of hard-to-detect malware on risk and performance, underscoring the importance
  of effective malware strategies.

# Summary. An optional shortened abstract.
summary: ''

tags:
- malware detection
- defense strategy
- decision-making
- security investment
- VirusTotal

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
links:
- name: URL
  url: https://wtmc.info/index.html
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
