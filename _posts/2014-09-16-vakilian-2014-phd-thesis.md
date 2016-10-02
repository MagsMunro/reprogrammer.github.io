---
layout: publication-layout
title: Less Is Sometimes More in the Automation of Software Evolution Tasks | Mohsen Vakilian
---

# Less Is Sometimes More in the Automation of Software Evolution Tasks

by [Mohsen Vakilian]({{site.url}}/).  

PhD Thesis, University of Illinois at Urbana-Champaign, 2014, pp. 1–174.  

[Thesis at Illinois](http://hdl.handle.net/2142/50602).

## Abstract

Software rapidly evolves. A refactoring is a code change that preserves the
behavior of the program. There has been much interest in automation to make
refactoring more efficient and reliable. Although modern Integrated Development
Environments (IDEs) provide many automated refactorings, studies suggest that
programmers underuse automated refactorings. Based on our studies of
programmers' refactoring practices, we argue that usability problems are the
common reasons of underusing automated refactorings. We introduce compositional
refactoring, a new paradigm of automating refactorings. In this paradigm, the
tool designer decomposes the large refactorings into a set of smaller, primitive
changes and automates the primitive changes. Then, programmers compose the
primitive changes to make larger changes. We have used the compositional
paradigm to automate two classes of refactorings: the refactorings supported by
modern IDEs and type qualifier inference. Type qualifiers augment a type system
to check more properties of the software. Automated inference of type qualifiers
can reduce the cost of using type qualifiers. The compositional paradigm enabled
us to build the first universal type qualifier inference system. The system
takes an existing type qualifier checker as an input and uses it to assist
programmers in inserting type qualifiers. Our studies show that compositional
refactoring is natural to programmers, gives programmers more control, and makes
the automation more predictable and usable than the existing wizard-based and
batch paradigms. The compositional paradigm achieves higher usability by
automating less. Although this phenomenon may seem counterintuitive, it is not
uncommon in automation design. The promising results of the compositional
paradigm suggest that other software development automation technologies may
also achieve a wider adoption by reducing the level of automation.

#### BibTeX

    @phdthesis{Vakilian2014PhDThesis,
      author = {Mohsen Vakilian},
      institution = {University of Illinois at Urbana-Champaign},
      pages = {1--174},
      title = {Less Is Sometimes More in the Automation of Software Evolution Tasks},
      url = {http://hdl.handle.net/2142/50602},
      year = {2014}
    }

