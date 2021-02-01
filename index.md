---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---
This lesson aims to teach the fundamentals of microbial amplicon analysis. Although many genes can be amplified, in practice the most common are 16S rDNA (for bacteria) and ITS (Internal Transcribed Spacer) DNA for fungi, so that is what this lesson focuses on. We use public datasets to demonstrate the major components of the analysis pipeline, including dealing with sequencing data, turning sequence data into a table of counts, and running common analyses on that table, not to mention performing data cleaning at each step.

If you are interested in metagenomics (which uses random reads instead of specific amplicons), check out [this other lesson](https://carpentries-incubator.github.io/metagenomics/) under development.

<!-- this is an html comment -->

{% comment %} This is a comment in Liquid {% endcomment %}

> ## Prerequisites
>
> This lesson uses command-line tools within the UNIX shell. Basic familiarity with the shell is expected but not required.
{: .prereq}

{% include links.md %}
