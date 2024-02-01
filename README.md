# HW 2 -- Sugary beverages

## Preliminaries

In addition to writing the client report and _doing_ the analysis, we will also
practice good `git`/GitHub collaboration behaviours. So, submissions will be
submitted via pull requests and peer-evaluation will be done using PR Reviews.

One member of your group must fork this repo. Other members should fork that
version (not mine). You are also welcome to collaborate in a single repo, as
you choose.

> Read _all_ these instructions carefully before you do anything. 

If you mess stuff up, I can help you fix it. But the cost of my assistance is a
proportional deduction on your mark. So you are better off trying to figure out
how to fix it yourself.

## Version 1 (first deadline), 10 points

In the first portion of your case report, your goal is to **propose**
methodology to examine / solve the client's questions of interest.

There are two mandatory files:

1. `./report/main.Rmd`/`./report/main.qmd` - The Rmarkdown/Quarto file that 
generates your report.
1. `./report/main.pdf` - The compiled pdf produced.

* You must store those (and only those) in the `./report` directory.
* You may not store _any_ files in the root or your team's repo (`./`)
* Any additional files must be in sub-directories that are nicely laid out. 
I suggest you use sub-directories carefully, especially for long scripts
(put these in, e.g. `code/01-exploration.R` rather than inside `main.Rmd`).
* Call your branch for this portion `v1.0.0`. You will submit by opening a PR
against the `main` branch.
* DO NOT DO ANY WORK ON THE `main` BRANCH. 

### Expectations

Write a client report summarizing your comments and proposal for the case. This
portion is at most 3 pages (excluding any carefully chosen tables or figure), or
approximately 1000-1500 words. Consult the included <`RUBRIC.md`> as a general 
guide (similar to HW 1).

1. You must submit your Part 1 via a Pull Request against `main` (from the 
`part1` branch). That means that you do your individual work directly there, or,
MUCH better, via pull requests into `v1.0.0` from your forks or other branches.
1. You must send the `.pdf` to Estella  by the Part 1 deadline. This will allow 
you to incorporate the changes for Part 2.

Though not required, I suggest you begin your analysis (on a different branch).
For Part 2, you must complete it (see below). 

Grade: total 10 pts

- clarity, conciseness, paragraph organization: 2 pts
- grammatical mistakes: 2 pts
- statistical depth, quality of the analysis: 3 pts
- description of the analysis (general audience): 3 pts

## Version 2 (second deadline), 10 points

The goal of this part is two fold (1) incorporate the suggestions from Me, the
peer-reviews, and Estella into your 3 page Summary, (2) complete the analysis
and add a Statistical Appendix.

The Appendix may be at most 7 pages. Choose judiciously. Size figures reasonably.

An additional, final page, should be used to list the names of group members, 
with a concise description of the contributions each group member makes to the
assignment.

### Expectations

* Call your branch for this portion `v2.0.0`. You will submit by opening a PR
against the `main` branch.

1. The structure of your initial 3 page client report should remain the same
(and still be less than 3 pages).
1. You should adjust the client report in light of the, now complete,
statistical analysis.
1. **(NEW)** You should add a *Statistical Appendix* detailing your analysis.
The target audience is statisticians (you and your classmates). Describe your
analysis carefully using statistical language and undertaking any EDA,
diagnostics, model checks, that are necessary. Carefully describe issues with
data cleaning. If you do something Bayesian, describe how you know your MCMC
converged. Etc. The page limit for this component is 5 pages. Think of this
as a roadmap carefully describing what you did and why. If you needed to
return to this project in the future, this part tells you, more precisely,
what you did.

Grade: total 10 pts

- statistical depth, quality of the analysis: 4 pts
- description of the analysis, graphical and numerical summaries (statistical
  audience):  3 pts
- incorporation of previous feedback: 3 pts

