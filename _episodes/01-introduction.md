---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "What is reproducible research?"
- "How to make your research more reproducible?"
objectives:
- "Explain what we mean by reproducible research"
- "Understand the value of reproducible research practices"
keypoints:
- "Reproducible research"
---

This lesson is greatly inspired from [Reproducible Research using Jupyter Notebooks](https://reproducible-science-curriculum.github.io/workshop-RR-Jupyter/) and released under the [CC Zero public domain waiver](https://creativecommons.org/publicdomain/zero/1.0/).

# What is reproducible research?

What we mean by "Reproducible Research"  is the ability of repeating the same research "experiment" in any place with any person. Here the word "experiment" is more general than data acquisition or running a simulation and should be seen as the whole set of steps for achieving your research results.

To make your research reproducible you need:

- to document the steps of your research project, and make them easy to understand
- to publish these steps and materials along with data used for your research project


# Why is it important to be reproducible?

> ## Is there a reproducibility crisis in Science?
>
> - Go to [socrative](https://socrative.com/)
> - Select tab "STUDENT LOGIN"
> - Use the Room Name given by the intructor (check the etherpad too)
> - Discuss with your neighbors
> - Answer to the question "*Is there a reproducibility crisis in Science?*"
>
> > ## Solution
> > - Analyze and discuss the results you got in your classroom.
> > - Watch the short video entitled "[Is there a reproducibility crisis in science?](https://www.youtube.com/watch?v=j7K3s_vi_1Y)" published by Nature.
> > <iframe width="560" height="315" src="https://www.youtube.com/watch?v=j7K3s_vi_1Y" frameborder="0" allowfullscreen></iframe>
> > - Did you get similar results?  
> {: .solution}
{: .challenge}

Being able to reproduce results is becoming increasingly important to:

- confirm that results are indeed correct
- allow scientists (including students and PhDs working in your team) to develop from previous work to create new scientific breakthroughs faster
- use the same scientific workflow with the same or different datasets and confirm/contradict existing results.  


## What kind of problems can you face if your research is not reproducible?

#### Science retracts paper without agreement of lead author.

- Journal retracted a study of how canvassers can sway people's opinions about gay marriage.
- [Editor-in-Chief](http://news.sciencemag.org/policy/2015/05/science-retracts-gay-marriage-paper-without-lead-author-s-consent): Original survey data:
    * not made available for independent reproduction of results
    * Survey incentives misrepresented
    * Sponsorship statement false
- Two grad students attempted to reproduce the study and could not.
- Concluded the data must have been fabricated. [538 story](http://fivethirtyeight.com/features/how-two-grad-students-uncovered-michael-lacour-fraud-and-a-way-to-change-opinions-on-transgender-rights/).


> ## Key Point
>  Methods we'll discuss today can't prevent fraud, but they can make it easier to discover such issues.
{: .callout}

#### Retracted, but not fraud

- One researcher had seven papers retracted because of irreproducibility [Retraction Watch](http://retractionwatch.com/2014/11/14/univ-no-misconduct-but-poor-research-practice-in-mgt-profs-work-now-subject-to-7-retractions/#more-23666)
- Couldn't find the data [Wiley](http://onlinelibrary.wiley.com/doi/10.1111/j.1468-1331.2011.03524.x/abstract)
- "Extensive" errors force retraction of lymphoma paper [JRO](http://retractionwatch.com/2013/01/14/extensive-errors-force-retraction-of-lymphoma-radiation-paper/)
- Many, many more [Irreproducible examples](https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-08-2014/wiki/Irreproducible-Examples)


#### Seizure study retracted after authors realized data were "Terribly mixed"

- From the authors of Low Dose Lidocaine for Refractory Seizures in Preterm Neonates: "The article has been - retracted at the request of the authors. After carefully re-examining the data presented in the article, they identified that data of two different hospitals got terribly mixed. The published results cannot be reproduced in accordance with scientific and clinical correctness." [IJP](http://retractionwatch.com/2013/02/01/seizure-study-retracted-after-authors-realize-data-got-terribly-mixed/)

#### Bad spreadsheet merge kills depression paper, quick fix resurrects it

- The authors informed the [journal](http://retractionwatch.com/2014/07/01/bad-spreadsheet-merge-kills-depression-paper-quick-fix-resurrects-it/) that the merge of lab results and other survey data used in the paper resulted in an error regarding the identification codes.
- Original conclusion : Lower levels of CSF IL-6 were associated with current depression and with future depression.
- Revised conclusion: Higher levels of CSF IL-6 and IL-8 were associated with current depression.

#### [LIGO](http://www.ligo.org/) (Laser Interferometer Gravitational-Wave Observatory)

- All [data](https://losc.ligo.org/data/) are publically available free of charge.
- Jupyter Notebooks running Python are produced for each [publication](https://www.ligo.caltech.edu/page/detection-companion-papers). These notebooks allow full reproducibility: all analyses and figures can be recreated.
- Produce in-depth [Tutorials](https://losc.ligo.org/tutorials/) using Jupyter Notebooks and Python
    * [Signal processing tutorial](https://losc.ligo.org/s/events/GW150914/GW150914_tutorial.html)
