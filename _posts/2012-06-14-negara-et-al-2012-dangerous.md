---
layout: publication-layout
title: Is It Dangerous to Use Version Control Histories to Study Source Code Evolution? | Mohsen Vakilian
---

# Is It Dangerous to Use Version Control Histories to Study Source Code Evolution?

by [Stas Negara]({{site.url_stas_negara}}), [Mohsen Vakilian]({{site.url}}/),
[Nicholas Chen]({{site.url_nicholas_chen}}), [Ralph E.
Johnson]({{site.url_ralph_e_johnson}}), and [Danny Dig]({{site.url_danny_dig}}).

In *Proceedings of the European Conference on Object-Oriented Programming
(ECOOP)*, 2012, pp. 79–103.

[Paper at Springer](http://dx.doi.org/10.1007/978-3-642-31057-7_5), [Artifacts
at Illinois](http://codingtracker.web.engr.illinois.edu/).

## Abstract

Researchers use file-based Version Control System (VCS) as the primary source of
code evolution data. VCSs are widely used by developers, thus, researchers get
easy access to historical data of many projects. Although it is convenient,
research based on VCS data is incomplete and imprecise. Moreover, answering
questions that correlate code changes with other activities (e.g., test runs,
refactoring) is impossible.

Our tool, CodingTracker, non-intrusively records fine-grained and diverse data
during code development. CodingTracker collected data from 24 developers: 1,652
hours of development, 23,002 committed files, and 314,085 testcase runs.

This allows us to answer: How much code evolution data is not stored in VCS? How
much do developers intersperse refactorings and edits in the same commit? How
frequently do developers fix failing tests by changing the test itself? How many
changes are committed to VCS without being tested? What is the temporal and
spacial locality of changes?

#### BibTeX

    @inproceedings{NegaraETAL2012Dangerous,
      author = {Stas Negara and Mohsen Vakilian and Nicholas Chen and Ralph E. Johnson and Danny Dig},
      booktitle = {Proceedings of the European Conference on Object-Oriented Programming (ECOOP)},
      pages = {79--103},
      title = {Is It Dangerous to Use Version Control Histories to Study Source Code Evolution?},
      year = {2012}
    }

