---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tensor network complexity of multilinear maps
subtitle: ''
summary: ''
authors:
- Per Austrin
- Petteri Kaski
- Kaie Kubjas
tags: []
categories: []
date: '2022-06-20'
lastmod: 2020-08-30T23:28:49+03:00
featured: false
draft: false
url_pdf: 
doi: 

links:
- name: arXiv
  url: "https://arxiv.org/abs/1712.09630"

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
publishDate: '2020-08-30T20:28:49.174432Z'
publication_types:
- 2
abstract: 'We study tensor networks as a model of arithmetic computation for
  evaluating multilinear maps.
  These capture any algorithm based on low-rank tensor decompositions, such as $O(n^{\omega+\epsilon})$ time matrix multiplication, and in addition many other algorithms such as $O(n \log n)$ time discrete Fourier transform and $O^*(2^n)$ time for computing the permanent of a matrix.
  However tensor networks sometimes yield faster algorithms than those
  that follow from low-rank decompositions.  For instance the
  fastest known $O(n^{(\omega +\epsilon)t})$ time algorithms for
  counting $3t$-cliques can be implemented with tensor networks, even
  though the underlying tensor has rank $n^{3t}$ for all $t \ge 2$.
  For counting homomorphisms of a general pattern graph $P$ into a host graph on $n$ vertices we obtain an upper bound of $O(n^{(\omega+\epsilon)\text{bw}(P)/2})$ where $\text{bw}(P)$ is the branchwidth of $P$. This essentially matches the bound for counting cliques, and yields small improvements over previous algorithms for many choices of $P$.

  While powerful, the model still has limitations, and we are able to
  show a number of unconditional lower bounds for various multilinear maps,
  including:  <br/>
  (a) an $\Omega(n^{\text{bw}(P)})$ time lower bound for counting homomorphisms from $P$ to an $n$-vertex graph, matching the upper bound if $\omega = 2$. 
    In particular for $P$ a $v$-clique this yields an $\Omega(n^{\lceil 2v/3 \rceil})$ time lower bound for counting $v$-cliques, and for $P$ a $k$-uniform $v$-hyperclique we obtain an $\Omega(n^v)$ time lower bound for $k \ge 3$, ruling out tensor networks as an approach to obtaining non-trivial algorithms for hyperclique counting and the Max-$3$-CSP problem. <br/> 
 (b) an $\Omega(2^{0.918n})$ time lower bound for the permanent
    of an $n \times n$ matrix.'
publication: 'Accepted to *Theory of Computing*'
---
