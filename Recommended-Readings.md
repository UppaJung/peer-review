# Recommended Readings

<span id="replicability"></span>
#### [The NeurIPS 2021 Consistency Experiment](https://blog.neurips.cc/2021/12/08/the-neurips-2021-consistency-experiment/)

The [The NeurIPS 2021 Consistency Experiment](https://blog.neurips.cc/2021/12/08/the-neurips-2021-consistency-experiment/), and its 2014 predecessor, duplicated the review process for a fraction of papers. Per the 2021 report:

> In 2014, 49.5% of the papers accepted by the first committee were rejected by the second (with a fairly wide confidence interval as the experiment included only 116 papers).  This year, this number was 50.6%.

The experimental methodology is noteworthy for removing independent variables that might cause differences between the replica review processes. Again, in their words:

> During the assignment phase of the review process, we chose 10% of papers uniformly at random—we’ll refer to these as the “duplicated papers.”  We assigned two Area Chairs (ACs) and twice the normal number of reviewers to these papers.  With the help and guidance of the team at OpenReview, we then created a copy of each of these papers and split the ACs and reviewers at random between the two copies.  We made sure that the two ACs were assigned to two different Senior Area Chairs (SACs) so that no SAC handled both copies of the same paper.  Any newly invited reviewer for one copy was automatically added as a conflict for the other copy.  We’ll refer to the SAC, AC, and reviewers assigned to the same copy as the copy’s “committee.”  The papers’ committees were not told about the experiment and were not aware the paper had been duplicated.

This methodology assured that papers were reviewed to a single peer review committee's reviewing standards and with reviewers from the same pool of candidates (a reviewer might be reviewing a paper from replica A and a different paper for replica B).

We can expect even lower reliability under less controlled circumstances, such as when authors re-submit their work to a different peer review committee. Re-submissions means work will be evaluated by a committee with traditions and expectations, different pools of reviewers, with new prior work released in the intervening time, and with changes in what research is fashionable over the passage of time.

<span id="Rein-in-the-four-horsemen-of-irreproducibility"></span>
### [Rein in the four horsemen of irreproducibility](https://www.nature.com/articles/d41586-019-01307-2)
Dorothy Bishop's 2019 Nature *World View* opinion, is a great resource for the history of flawed scientific practices (e.g., P-Hacking, HARKing), which I argue are encouraged and amplified by science's reliance on exclusionary peer review.

[[DOI]](https://doi.org/10.1038/d41586-019-01307-2)

<span id="The-natural-selection-of-bad-science"></span>
### [The natural selection of bad science](https://royalsocietypublishing.org/doi/10.1098/rsos.160384)
Paul E. Smaldino and Richard McElreath write:
>An incentive structure that rewards publication quantity will, in the absence of countervailing forces, select for methods that produce the greatest number of publishable results. This, in turn, will lead to the natural selection of poor methods and increasingly high false discovery rates.

>We term this process the natural selection of bad science to indicate that it requires no conscious strategizing nor cheating on the part of researchers. Instead, it arises from the positive selection of methods and habits that lead to publication. 

[[DOI]](https://doi.org/10.1098/rsos.160384)

<span id="HARKing-Hypothesizing-After-the-Results-are-Known"></span>
### [HARKing (Hypothesizing After the Results are Known)](https://journals.sagepub.com/doi/10.1207/s15327957pspr0203_4)
Norbert L. Kerr writes
>HARKing is defined as presenting a post hoc hypothesis (i.e., one based on or informed by one's results) in one's research report as if it were, in fact, an a priori hypotheses.

In other words, a researcher is HARKing when they look for differences in data that might be significant, then tests for statistical significance when they find differences. If there are 20 possible differences that the researcher might look at, we can expect one in 20 to be statistically significant at the 0.05 level by chance. Thus, we can expect them to find something that by chance that looks like it didn't occur by chance.

[[DOI]](https://doi.org/10.1207/s15327957pspr0203_4)
