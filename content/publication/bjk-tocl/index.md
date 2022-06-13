---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Universal Equivalence and Majority of Probabilistic Programs over Finite Fields
subtitle: ''
summary: ''
authors:
- Gilles Barthe
- Charlie Jacomme
- Steve Kremer
tags:
- probabilistic programs
- finite fields
- decidability and complexity
- Program equivalence
categories: []
date: '2021-11-01'
lastmod: 2021-12-12T12:58:27+01:00
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
publishDate: '2022-06-13T13:02:59.555730Z'
publication_types:
- '2'
abstract: 'We study decidability problems for equivalence of probabilistic programs
  for a core probabilistic programming language over finite fields of fixed characteristic.
  The programming language supports uniform sampling, addition, multiplication, and
  conditionals and thus is sufficiently expressive to encode Boolean and arithmetic
  circuits. We consider two variants of equivalence: The first one considers an interpretation
  over the finite field Fq, while the second one, which we call universal equivalence,
  verifies equivalence over all extensions Fqk of Fq. The universal variant typically
  arises in provable cryptography when one wishes to prove equivalence for any length
  of bitstrings, i.e., elements of F2k for any k. While the first problem is obviously
  decidable, we establish its exact complexity, which lies in the counting hierarchy.
  To show decidability and a doubly exponential upper bound of the universal variant,
  we rely on results from algorithmic number theory and the possibility to compare
  local zeta functions associated to given polynomials. We then devise a general way
  to draw links between the universal probabilistic problems and widely studied problems
  on linear recurrence sequences. Finally, we study several variants of the equivalence
  problem, including a problem we call majority, motivated by differential privacy.
  We also define and provide some insights about program indistinguishability, proving
  that it is decidable for programs always returning 0 or 1.'
publication: '*ACM Trans. Comput. Logic*'
doi: 10.1145/3487063
links:
- name: URL
  url: https://doi.org/10.1145/3487063
---
