---
title: "Sharing Jupyter Notebooks using Binder"
teaching: 0
exercises: 0
questions:
- "How can we share Jupyter Notebook so they are interactive, can be run, and modified?"
- What does it mean for code to "depend" on software?"
- How can we explicitly define the dependencies for our code?"
objectives:
- Create a shareable interactive binder for your online Jupyter notebooks."
- Create a requirements file listing dependencies for the notebooks in your repository."
keypoints:
- "Binder provides an environment that runs and interactively serves your Jupyter notebooks."
- "Use `environment.yml` or `Dockerfile` to specify dependencies beyond the Jupyter notebook execution environment itself."
---


> ## Important notice
> This lesson has been taken from [https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/)
> and is distributed under the <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution license</a>.
> The following is a human-readable summary of (and not a substitute for) the <a href="https://creativecommons.org/licenses/by/4.0/legalcode">full legal text of the CC BY 4.0 license</a>.
{: .callout}


# Reproducible computing environments with Binder

## A short intro on Binder

Authors: Chris Holdgraf, M Pacer

[Slideshow](https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/slides/02-intro_to_binder.slides.html#/)

## Your jupyter dashboards in mybinder

### Preparing your github repository for Binder

Example with:

- environment.yml
- Dockerfile

### Publish your dashboards in mybinder

- Create a shareable Binder link
- Update your github repository to display shareable Binder link for each of your dashboards

We make two exercises: one with environment.yml (adding conda packages) and one with a Dockerfile (where we add for instance input files).

# Thebe?
