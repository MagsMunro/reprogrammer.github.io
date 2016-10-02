---
layout: publication-layout
title: "Keshmesh: Bringing Advanced Static Analysis to Concurrency Bug Pattern Detectors | Mohsen Vakilian"
---

# Keshmesh: Bringing Advanced Static Analysis to Concurrency Bug Pattern Detectors

by [Mohsen Vakilian]({{site.url}}/), [Stas Negara]({{site.url_stas_negara}}),
[Samira Tasharofi]({{site.url_samira_tasharofi}}), and [Ralph E.
Johnson]({{site.url_ralph_e_johnson}}).

Technical Report, University of Illinois, 2013, pp. 1–11.

[Paper at Illinois](http://hdl.handle.net/2142/44837).

## Abstract

Bug patterns are coding idioms that may make the code less maintainable or turn
into bugs in future. The state-of-the-art tools for detecting concurrency bug
patterns (CBPs) perform simple, intraprocedural analyses. While this simplicity
makes the analysis fast, it does not provide protection against CBPs that
involve aliasing or multiple methods. This paper shows that it is now practical
to employ advanced static analysis for detecting CBPs. We propose an extensible
framework, Keshmesh, which combines the strengths of WALA, a static analysis
framework, and FindBugs, a popular bug pattern detection tool. Keshmesh detects
five CBPs using interprocedural analyses and fixes two of them. Keshmesh found
40 previously unknown CBP instances and only 12 false positives in six
open-source projects. Programmers fixed 11 of the 20 issues we reported. These
results show that Keshmesh is applicable to large projects, finds CBPs that
programmers want to fix, and reports few false positives.

#### BibTeX

    @techreport{VakilianETAL2013Keshmesh,
      author = {Mohsen Vakilian and Stas Negara and Samira Tasharofi and Ralph E. Johnson},
      institution = {University of Illinois},
      pages = {1--11},
      title = {Koeshmesh: A Tool for Detecting and Fixing Java Concurrency Bug Patterns},
      url = {http://hdl.handle.net/2142/44837},
      year = {2013}
    }

