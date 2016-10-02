---
layout: publication-layout
title: Automated Decomposition of Build Targets | Mohsen Vakilian
---

# Automated Decomposition of Build Targets

by [Mohsen Vakilian]({{site.url}}/), Raluca Sauciuc, [J. David
Morgenthaler]({{site.url_j_david_morgenthaler}}), and [Vahab
Mirrokni]({{site.url_vahab_mirrokni}}).

In *Proceedings of the International Conference on Software Engineering (ICSE)*,
2015, pp. 123–133.

[Paper at Google](http://research.google.com/pubs/archive/42249.pdf), [Paper at
IEEE](http://dx.doi.org/10.1109/ICSE.2015.34), [Paper at
ACM](http://dl.acm.org/citation.cfm?id=2818772), [Extended Version at
Illinois](http://hdl.handle.net/2142/47551).

## Abstract

A (build) target specifies the information that is needed to automatically
build a software artifact. This paper focuses on underutilized targets—an
important dependency problem that we identified at Google. An underutilized
target is one with files not needed by some of its dependents. Underutilized
targets result in less modular code, overly large artifacts, slow builds, and
unnecessary build and test triggers. To mitigate these problems, programmers
decompose underutilized targets into smaller targets. However, manually
decomposing a target is tedious and error-prone. Although we prove that finding
the best target decomposition is NP-hard, we introduce a greedy algorithm that
proposes a decomposition through iterative unification of the strongly
connected components of the target. Our tool found that 19,994 of 40,000 Java
library targets at Google can be decomposed to at least two targets. The
results show that our tool is (1) efficient because it analyzes a target in two
minutes on average and (2) effective because for each of 1,010 targets, it
would save at least 50% of the total execution time of the tests triggered by
the target.

#### BibTeX

    @inproceedings{VakilianETAL2015TargetDecomposition,
      author = {Mohsen Vakilian and Raluca Sauciuc and J. David Morgenthaler and Vahab Mirrokni},
      booktitle = {Proceedings of the International Conference on Software Engineering (ICSE)},
      pages = {123--133},
      title = {Automated Decomposition of Build Targets},
      url = {http://research.google.com/pubs/archive/42249.pdf},
      year = {2015}
    }

