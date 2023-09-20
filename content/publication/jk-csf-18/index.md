---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An extensive formal analysis of multi-factor authentication protocols
subtitle: ''
summary: ''
authors:
- Charlie Jacomme
- Steve Kremer
tags: []
categories: []
date: '2018-07-01'
lastmod: 2020-10-22T09:58:27+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-09-20T12:10:01.491006Z'
publication_types:
- '1'
abstract: "Passwords are still the most widespread means for authenticating users,\
  \ even though they have been shown to create huge security problems. This motivated\
  \ the use of additional authentication mechanisms used in so-called multi-factor\
  \ authentication protocols. In this paper we define a detailed threat model for\
  \ this kind of protocols: while in classical protocol analysis attackers control\
  \ the communication network, we take into account that many communications are performed\
  \ over TLS channels, that computers may be infected by different kinds of malwares,\
  \ that attackers could perform phishing, and that humans may omit some actions.\
  \  We formalize this model in the applied pi calculus and perform an extensive analysis\
  \ and comparison of several widely used protocols - variants of Google 2-step and\
  \ FIDO's U2F. The analysis is completely automated, generating systematically all\
  \ combinations of threat scenarios for each of the protocols and using the ProVerif\
  \ tool for automated protocol analysis. Our analysis highlights weaknesses and strengths\
  \ of the different protocols, and allows us to suggest several small modifications\
  \ of the existing protocols which are easy to implement, yet improve their security\
  \ in several threat scenarios."
publication: "*Proceedings of the 31st IEEE Computer Security Foundations Symposium\
  \ (CSF'18)*"
url_pdf: https://ieeexplore.ieee.org/document/8429292/
doi: 10.1109/CSF.2018.00008
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/8429292/
---
