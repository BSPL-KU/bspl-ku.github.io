---
title: "[Announcement] Released toolbox: Iterative dual-regression with sparse prior"
date: 2013-12-26 19:42:00
---

Toolbox of iterative dual-regression with sparse prior was released on NITRC (<http://www.nitrc.org/projects/iterdrwsp/>)

Iterative Dual-Regression with Sparse Prior (IDRwSP) is aimed to better estimate an individual's neuronal activation using the results of an independent component analysis (ICA) method applied to a temporally concatenated group of functional magnetic resonance imaging (fMRI) data (i.e., Tc-GICA method). 

In detail, an ordinary DR approach estimates the spatial patterns (SPs) of neuronal activation and corresponding time courses (TCs) specific to each individual's fMRI data with two steps involving least-squares (LS) solutions. The proposed approach employs iterative LS solutions to refine both the individual SPs and TCs with an additional a priori assumption of sparseness in the SPs (i.e., minimally overlapping SPs) based on L(1)-norm minimization.

Toolbox was developed under MATLAB framework (additionally require SPM8).

Please refer the reference paper to know more details ([click here](http://www.sciencedirect.com/science/article/pii/S1053811912008634)), and site it when you want to use in research purpose.

(Kim YH, Kim J, Lee JH., Iterative approach of dual regression with a sparse prior enhances the performance of independent component analysis for group functional magnetic resonance imaging (fMRI) data., Neuroimage. 2012.)

Please enjoy it!

Yong-Hwan Kim 
(whiteneng@gmail.com)

![](newsreleasedtoolboxiterativedual--c376ce02cc17b488/fig_iterDRwSP.png)

