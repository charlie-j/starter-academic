---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Symbolic Models for Isolated Execution Environments
subtitle: ''
summary: ''
authors:
- Charlie Jacomme
- Steve Kremer
- Guillaume Scerri
tags: []
categories: []
date: '2018-04-01'
lastmod: 2020-10-22T09:58:26+02:00
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
publishDate: '2020-10-22T07:58:26.495481Z'
publication_types:
- '1'
abstract: Isolated Execution Environments (IEEs), such as ARM TrustZone and Intel
  SGX, offer the possibility to execute sensitive code in isolation from other malicious
  programs, running on the same machine, or a potentially corrupted OS. A key feature
  of IEEs is the ability to produce reports binding cryptographically a message to
  the program that produced it, typically ensuring that this message is the result
  of the given program running on an IEE. We present a symbolic model for specifying
  and verifying applications that make use of such features. For this we introduce
  the S(ell)APIC process calculus, that allows to reason about reports issued at given
  locations. We also provide tool support, extending the SAPIC/TAMARIN toolchain and
  demonstrate the applicability of our framework on several examples implementing
  secure outsourced computation (SOC), a secure licensing protocol and a one-time
  password protocol that all rely on such IEEs.
publication: "*Proceedings of the 2nd IEEE European Symposium on Security and Privacy\
  \ (EuroS&P'17)*"
url_pdf: https://ieeexplore.ieee.org/document/7962001/
doi: 10.1109/EuroSP.2017.16
---
