---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Symbolic methods in computational cryptography proofs
subtitle: ''
summary: ''
authors:
- Gilles Barthe
- Benjamin Grégoire
- Charlie Jacomme
- Steve Kremer
- Pierre-Yves Strub
tags: []
categories: []
date: '2019-07-01'
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
publishDate: '2022-09-21T14:44:47.986246Z'
publication_types:
- '1'
abstract: 'Code-based game-playing is a popular methodology for proving security of
  cryptographic constructions and side-channel countermeasures. This methodology relies
  on treating cryptographic proofs as an instance of relational program verification
  (between probabilistic programs), and decomposing the latter into a series of elementary
  relational program verification steps. In this paper, we develop principled methods
  for proving such elementary steps for probabilistic programs that operate over finite
  fields and related algebraic structures. We focus on three essential properties:
  program equivalence, information flow, and uniformity. We give characterizations
  of these properties based on deducibility and other notions from symbolic cryptography.
  We use (sometimes improve) tools from symbolic cryptography to obtain decision procedures
  or sound proof methods for program equivalence, information flow, and uniformity.
  Finally, we evaluate our approach using examples drawn from provable security and
  from side-channel analysis-for the latter, we focus on the masking countermeasure
  against differential power analysis. A partial implementation of our approach is
  integrated in EASYCRYPT, a proof assistant for provable security, and in MASKVERIF,
  a fully automated prover for masked implementations.'
publication: "*Proceedings of the 31st IEEE Computer Security Foundations Symposium\
  \ (CSF'19)*"
url_pdf: https://hal.inria.fr/hal-02117794
doi: 10.1109/CSF.2019.00017
links:
- name: URL
  url: https://hal.inria.fr/hal-02117794
---
