---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Universal equivalence and majority on probabilistic programs over finite fields
subtitle: ''
summary: ''
authors:
- Gilles Barthe
- Charlie Jacomme
- Steve Kremer
tags: []
categories: []
date: '2020-07-01'
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
publishDate: '2023-09-20T12:10:02.045528Z'
publication_types:
- '1'
abstract: ' We study equivalence checking of probabilistic programs, a fundamental
  problem which arises in many application areas including cryptography, privacy,
  algorithmic fairness and machine learning.  The programming language we consider
  manipulates polynomials over a finite field of characteristic $q$ and supports sampling
  and conditioning making it sufficiently expressive to encode boolean and arithmetic
  circuits. We consider two variants of the equivalence checking problem: the first
  one considers an interpretation over the finite field $Fq$, while the second one,
  which we call universal equivalence, verifies equivalence over all extensions $Fqk$
  of $Fq$. The universal variant typically arises in provable cryptography when one
  wishes to prove equivalence for any length of bitstrings, i.e., elements of $F_2^k$
  for any $k$.  While the first problem is obviously decidable, we establish its exact
  complexity which lies in the counting hierarchy. To show decidability, and a doubly
  exponential upper bound, of the universal variant we rely on results from algorithmic
  number theory and the possibility to compare local zeta functions associated to
  given polynomials. Finally we study several variants of the equivalence problem,
  including a problem we call majority, motivated by differential privacy.  '
publication: "*Proceedings of the 35th Annual ACM/IEEE Symposium on Logic in Computer\
  \ Science (LICS'20)*"
---
