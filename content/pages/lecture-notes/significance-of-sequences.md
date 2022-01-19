---
content_type: page
parent_title: Lecture Notes
parent_uid: 9e7f1aa8-38db-6648-8063-791ee60d518e
title: Significance of Alignments
uid: 11af0f00-dc54-78ce-d85a-e3567d5d0eb2
---

1.  [Sequence alignment](http://www.ncbi.nlm.nih.gov/BLAST/tutorial/Altschul-1.html)
    *   Inputs:
        *   _Explicit_—Two sequences {a1, a2, ...., am} and {b1, b2, ...., bn} (e.g. query and database)
        *   _Implicit_—A scoring procedure, e.g. pairwise scores s(ai,bj) and gap costs
    *   Alignment algorithm: global, local, gapped, gapless (dynamic programming, applet)
    *   Output: matching (sub)sequences with an overall score S . ([example](http://en.wikipedia.org/wiki/File:Zinc-finger-dot-plot.png))
    *   Significance: What is the probability of getting a score S by chance?
2.  Statistics of gapless local alignments:
    *   Random walks of scores as a function of matching length
    *   [Extreme Value Distributions](http://mathworld.wolfram.com/ExtremeValueDistribution.html), the [Gumbel distribution](http://www.itl.nist.gov/div898/handbook/eda/section3/eda366g.htm)
    *   Tails of distribution in a [gapless alignment](http://online.itp.ucsb.edu/online/infobio01/altschul/)
    *   The Karlin-Dembo formula
3.  Gapped alignments and Statistical Physics
    *   Transfer Matrix method for [Directed Paths in Random Media (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)PDF)](https://arxiv.org/pdf/cond-mat/9411022.pdf)
    *   Dynamic Programming method for Sequence Alignment ([Example](http://www.sbc.su.se/%7Eper/molbioinfo2001/dynprog/dynamic.html))

*   [Tutorial by Ralf Bundschuh](http://online.itp.ucsb.edu/online/infobio01/bundschuh/) on Sequence Alignment (and [associated paper](http://pre.aps.org/abstract/PRE/v65/i3/e031911))

([Detailed Lecture Notes (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)PDF)]({{< baseurl >}}/resources/mit8_592js11_lec8))