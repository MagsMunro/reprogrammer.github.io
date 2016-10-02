---
layout: publication-layout
title: Inferring Method Effect Summaries for Nested Heap Regions | Mohsen Vakilian
---

# Inferring Method Effect Summaries for Nested Heap Regions

by [Mohsen Vakilian]({{site.url}}/), [Danny Dig]({{site.url_danny_dig}}),
[Robert L. Bocchino, Jr.]({{site.url_robert_l_bocchino_jr}}), [Jeffrey L.
Overbey]({{site.url_jeffrey_l_overbey}}), [Vikram S.
Adve]({{site.url_vikram_s_adve}}), and [Ralph E.
Johnson]({{site.url_ralph_e_johnson}}).

In *Proceedings of the International Conference on Automated Software
Engineering (ASE)*, 2009, pp. 421–432.  

[Paper at ACM](https://dl.acm.org/citation.cfm?id=1747491.1747537), [Paper at
IEEE](http://dx.doi.org/10.1109/ASE.2009.68), [Paper at
Illinois](http://hdl.handle.net/2142/14152), [Talk at
Illinois](http://media.cs.uiuc.edu/DCS/research/upcrc/UPCRC-2009-11-05fbdo.asx),
[Artifacts at Illinois](http://dpj.cs.illinois.edu/DPJ/DPJizer.html).

An extended version of this paper appeared as the master's thesis of [Mohsen
Vakilian]({{site.url}}/). [Thesis at
Illinois](http://hdl.handle.net/2142/17342).

## Abstract

Effect systems are important for reasoning about the side effects of a program.
Although effect systems have been around for decades, they have not been widely
adopted in practice because of the large number of annotations that they
require. A tool that infers effects automatically can make effect systems
practical. We present an effect inference algorithm and an Eclipse plug-in,
DPJizer, which alleviate the burden of writing effect annotations for a language
called Deterministic Parallel Java (DPJ). The key novel feature of the algorithm
is the ability to infer effects on nested heap regions. Besides DPJ, we also
illustrate how the algorithm can be used for a different effect system based on
object ownership. Our experience shows that DPJizer is both useful and
effective: (i) inferring effect annotations automatically saves significant
programming burden; and (ii) inferred effects are more precise than those
written manually, and are fine-grained enough to enable the compiler to prove
determinism of the program.

#### BibTeX

    @inproceedings{VakilianETAL2009DPJizer,
      author = {Mohsen Vakilian and Danny Dig and Bocchino, Jr., Robert L. and Jeffrey L. Overbey and Vikram S. Adve and Ralph E. Johnson},
      booktitle = {Proceedings of the International Conference on Automated Software Engineering (ASE)},
      pages = {421--432},
      title = {Inferring Method Effect Summaries for Nested Heap Regions},
      year = {2009}
    }

