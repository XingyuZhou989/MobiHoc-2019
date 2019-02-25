---
layout: default
title: Submission Instructions
group: Author Information

---

# {{ page.title }}

Papers should be submitted via [the HotCRP submissing website ( https://mobihoc19.hotcrp.com)](https://mobihoc19.hotcrp.com).

Papers should not exceed 10 pages (US letter size) double column including figures, tables, and references in standard ACM format.
Papers must be submitted electronically in printable PDF form.
Templates for the standard ACM format can be found at [this link](http://www.acm.org/publications/article-templates/proceedings-template.html).
If you are using LaTeX, please refer to the sample file **"sample-sigconf.tex"** after you download the .zip templates file and unzip it. Note that the document class **"\documentclass[sigconf]{acmart}"** should be used. No changes to margins, spacing, or font sizes are allowed from those specified by the style files. Papers violating the formatting guidelines will be returned without review.

All submissions will be reviewed using a **single-blind** review process.
The identity of referees will not be revealed to authors, but author can keep their names on the submitted papers, on figures, bibliography, etc.

#### Dual Submission Policy

*Accepted papers will appear in the conference proceedings published by the ACM. Warning: It is ACM policy not to allow double submissions, where the same paper is submitted to more than one conference/journal concurrently. Any double submissions detected will be immediately rejected from all conferences/journals involved.*
{: class="bs-callout bs-callout-danger" }

 
#### Rebuttal Submission Policy

The authors can write a rebuttal after the first-round review process is complete, and upload the rebuttal to the hotcrp submission site. During the rebuttal phase, you will have access to the current state of your reviews and have the opportunity to submit a response of **<font color= "Red">ONE PAGE</font>**
using the rebuttal template we have provided [link]({% asset mobihoc-rebuttal-template.tex @path %}). You should use a single file to respond to all reviews. Please DO NOT change the setting of the template such as page margins, line space, font family, and font size, etc.

The goal of this rebuttal stage is to give the PC members an opportunity to get answers to specific questions and to give authors the opportunity to correct substantial factual mistakes in the reviews. Author feedback is optional. We ask that you submit comments in the following two cases:

1. Reviews contain explicit questions or requests for clarification.

2. Reviews contain important factual errors, e.g., a reviewer incorrectly concludes that the main theorem is wrong or incorrectly claims that the main result is known.

We strongly suggest that authors do not argue against comments expressing a subjective opinion (e.g. reviewer claims that the novel contribution is modest), as this rarely sways the reviewers. We highlight that in any case the text of your response is limited to one page using the provided template file.

Your response will be seen by all PC members who have access to the discussion of your paper, so please try to be polite and constructive.

You can remove the copyright information on the rebuttal by using the following commands in Latex:  

\settopmatter{printacmref=false} \\
\setcopyright{none} \\
\renewcommand\footnotetextcopyrightpermission[1]{}

### Questions & Answers

Question - Are we allowed to remove the copyright information on the rebuttal?

Answer - You can remove the copyright information on the rebuttal by using the following commands in Latex:  

\settopmatter{printacmref=false} \\
\setcopyright{none} \\
\renewcommand\footnotetextcopyrightpermission[1]{}\\

Question -  in the rebuttal, are we allowed to point to a PDF with a new version of our paper, replying to the reviewer's comments, and with the proposed modifications marked in red?  Or must the review be self-contained, without external links?

Answer - Also, the rebuttal has to be self-contained and cannot point to any external documents or sites. Additionally, since the review was for the draft that was submitted, having a newer version is more like a new submission which would neither be fair (to the others) nor acceptable (for the conference). We hope you understand.
