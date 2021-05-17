---
layout: post
author: Casper Steinmann
title: The aug‐cc‐pVTZ‐J basis set for the p‐block fourth‐row elements Ga, Ge, As, Se, and Br
splash_path: /assets/img/toc.png
---
A project that started more than 10 years ago is now complete.
I took [Stephan Sauer's](https://sites.google.com/site/spasauer) course on Molecular Electromagnetic Properties which is [online](https://www.youtube.com/playlist?list=PL_Jxd1JMsQnMakaWU-4bOb1v1bSatsfvb) and we had to do a student project as part of the exam.
I passed the course but did not finish the project.
Until now.

![alt text](/assets/img/aug-cc-pvtz-j-toc.png "Table of Contents")

In this recent contribution, we add [optimized basis sets for calculation of particularly spin-spin coupling constants for the p-block fourth row elements Ga, Ge, As, Se and Br](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/10.1002/mrc.5166).

We show in the paper what functions are necessary to obtain converged behavior (a lot of *s*-functions and *f*-functions) for the uncontracted basis set.
This fits well with what was observed for other elements in the fourth row.
We then perform a re-contraction without loosing too much accuracy in the results.
We observe that particularly Br has a somewhat slow convergence with respect to the contraction level compared to the other elements, but overall we see very good accuracy across all elements (less than 0.5 %) when using the contracted basis set over the uncontracted one.

With this addition, the aug-cc-pVTZ-J basis set is available for most fourth row elements.
The basis set will be available soon^(TM) on the [basis set exchange](https://www.basissetexchange.org/).
