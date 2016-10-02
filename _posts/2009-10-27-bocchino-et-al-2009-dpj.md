---
layout: publication-layout
title: A Type and Effect System for Deterministic Parallel Java | Mohsen Vakilian
---

# A Type and Effect System for Deterministic Parallel Java

by [Robert L. Bocchino, Jr.]({{site.url_robert_l_bocchino_jr}}), [Vikram S.
Adve]({{site.url_vikram_s_adve}}), [Danny Dig]({{site.url_danny_dig}}), [Sarita
V. Adve]({{site.url_sarita_v_adve}}), Stephen Heumann, [Rakesh
Komuravelli]({{site.url_rakesh_komuravelli}}), [Jeffrey L.
Overbey]({{site.url_jeffrey_l_overbey}}), Patrick Simmons, [Hyojin
Sung]({{site.url_hyojin_sung}}), and [Mohsen Vakilian]({{site.url}}/).

In *Proceedings of the Conference on Object Oriented Programming Systems
Languages and Applications (OOPSLA)*, 2009, pp. 97–116.

[Paper at ACM](http://dl.acm.org/authorize?148828), [Artifacts at
Illinois](http://dpj.cs.illinois.edu).

## Abstract

Today's shared-memory parallel programming models are complex and error-prone.
While many parallel programs are intended to be deterministic, unanticipated
thread interleavings can lead to subtle bugs and nondeterministic semantics. In
this paper, we demonstrate that a practical type and effect system can simplify
parallel programming by guaranteeing deterministic semantics with modular,
compile-time type checking even in a rich, concurrent object-oriented language
such as Java. We describe an object-oriented type and effect system that
provides several new capabilities over previous systems for expressing
deterministic parallel algorithms. We also describe a language called
Deterministic Parallel Java (DPJ) that incorporates the new type system
features, and we show that a core subset of DPJ is sound. We describe an
experimental validation showing that DPJ can express a wide range of realistic
parallel programs; that the new type system features are useful for such
programs; and that the parallel programs exhibit good performance gains (coming
close to or beating equivalent, nondeterministic multithreaded programs where
those are available).

#### BibTeX

    @inproceedings{BocchinoETAL2009DPJ,
      author = {Bocchino, Jr., Robert L. and Vikram S. Adve and Danny Dig and Sarita V. Adve and Stephen Heumann and Rakesh Komuravelli and Jeffrey L. Overbey and Patrick Simmons and Hyojin Sung and Mohsen Vakilian},
      booktitle = {Proceedings of the Conference on Object Oriented Programming Systems Languages and Applications (OOPSLA)},
      pages = {97--116},
      title = {A Type and Effect System for Deterministic Parallel Java},
      year = {2009},
    }

