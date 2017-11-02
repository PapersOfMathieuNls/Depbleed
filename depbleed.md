---
title: "DEPBLEED"
shorttitle: "DEPBLEED"
bibliography: config/library.bib
abstract:  "Abstract Goes Here"
author: 
- name: Mathieu Nayrolles
  affiliation: ECE Department, Concordia University
  location: Montréal, QC, Canada
  email: mathieu.nayrolles@concordia.ca
- name: Julien Kauffmann
  affiliation: Freelan ?
  location: Montréal, QC, Canada
  email: a@b.c
- name: Abdelwahab Hamou-Lhadj
  affiliation: ECE Department, Concordia University
  location: Montréal, QC, Canada
  email: wahab.hamou-lhadj@concordia.ca
csl: config/acm-sig-proceedings.csl
keyword: 
- Bug Prediction
- Risky Software Commits
- Clone Detection
- Software Maintenance
---

# Introduction {#sec:introduction}

# Related Work {#sec:relwork}

# The DEPBLEED TOOL {#sec:depleed}

# Case Study Setup & Results {#sec:exp}

## Project Repository Selection {#sec:rep}

## Building a Database of Dependency Bleedings {#sub:golden}

## Evaluation Measures

Similar to prior work (e.g., [@SunghunKim2008; @Kamei2013]), we used precision, recall, and F$_1$-measure to evaluate our approach. They are computed using TP (true positives), FP (false positives), FN (false negatives), which are defined as follows:

- TP is the number of Dependency Bleedings that were properly classified by DEPBLEED
- FP is the number of healthy dependency that were classified by DEPBLEED as Bleedings
- FN is the number of Dependency Bleedings that were not detected by DEPBLEED
- Precision: TP / (TP + FP)
- Recall: TP / (TP + FN)
- F$_1$-measure: 2.(precision.recall)/(precision+recall)

## Pull Requests

# Discussion

## Limitations

## Threats to Validity

# Conclusion {#sec:conclusion}

# Reproduction Package

\section*{References}
\setlength{\parindent}{0pt}