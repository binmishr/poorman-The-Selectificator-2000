# poorman-The-Selectificator-2000

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.


Introduction
===============

Welcome to my series of blog posts about my data manipulation package, {poorman}. For those of you that don’t know, {poorman} is aiming to be a replication of {dplyr} but using only {base} R, and therefore be completely dependency free. What’s nice about this series is that if you’re not into {poorman} and would prefer just to use {dplyr}, then that’s absolutely OK! By highlighting {poorman} functionality, this series of blog posts simultaneously highlights {dplyr} functionality too! However I also describe how I developed the internals of {poorman}, often highlighting useful {base} R tips and tricks.

v0.2.0 of {poorman} which you can install from CRAN and so today I am going to talk about my progress in expanding the flexibility of the select() function. But I’m not just going to show you what it can do, I am going to show you how. If you’re interested in learning a little bit about non-standard evaluation in R then be sure to read on.
