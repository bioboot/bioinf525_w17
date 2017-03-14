---
layout: page
title: Module 2
permalink: /module2/
---


# Module 2. Introduction to Statistics in Bioinformatics

Basic statistics as used in bioinformatics, especially standard statistical tests of significance and when they apply. Applications to genetics, experimental and observational medical data, as well as exploration of multiple testing issues that arise in bioinformatics and other experimental settings.  


  
**N.B.**  Please complete this pre-course [**questionnaire**](http://tinyurl.com/bioinf525-questions) if you have not already done so. 




|         |           |                          | 
| :-----: |:---------:| :----------------------- | 
| **2.1** | Lecture  | [**Framework for statistical analysis of biomedical data**](#2.1) | 
|         | Lab | [Descriptive statistics and summarizing data](#2.1) | 
| **2.2** | Lecture | [**Approaches to statistical estimation and testing**](#2.2)  | 
|         | Lab | [Statistical estimation and hypothesis testing](#2.2)  | 
| **2.3** | Lecture | [**Analyses involving associations**](#2.3)   | 
|         | Lab | [Pearson correlation, t-test, and log odds ratios](#2.3) | 
| **2.4** | Lecture | [**Linear regression**](#2.4)                 | 
|         | Lab | [Regression models](#2.4)  | 
| **2.5** | Lecture | [**Graphical methods for multivariate data analysis**](#2.5) | 
|         | Lab | [Clustering and principal component analysis](#2.5)  | 


<br>

---
<a name="2.1"></a>
<br>

#### Lecture (2-1): **Framework for statistical analysis of biomedical data**
- **Time**: 		Feb 7 (Tuesday), 2:30 - 4:00 PM
- **Topics**: 
Probability distributions, quantifying central values and variability, quantifying association, graphical displays of data
- **Material**:  
[Lecture slides (PDF)]({{ site.baseurl }}/class-material/BI525W17Lec2.1.pdf),  
[Pre class screen cast](https://vimeo.com/151178510),  
We will be using R throughout this module to demonstrate data analyses concepts and best practices.  In preparation for our first lab session we are requesting that you all complete the free online interactive learning tutorial [“TryR” (http://tryr.codeschool.com)](http://tryr.codeschool.com).  This will take you through a gentle introduction to R syntax and some of the major R data structures (called vectors, matrices and data.frames).  


<script async class="speakerdeck-embed" data-id="95cf77439df54785a9716718af8d05a0" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

[Hands-on in class exercise](https://github.com/bioboot/web-2016/blob/gh-pages/class-material/R_basics.md).  
<br>

#### Lab (2-1): 	**Descriptive statistics and summarizing data**
- **Time**: 		2:30 – 4:00 PM, Feb 9 (Thursday)
- **Topics**:
Introduction to R, probability distributions, quantifying central values and variability, quantifying association, graphical displays of data.
- **Material**:  
[PDF slides: Introduction to R]({{ site.baseurl }}/class-material/Introduction_to_R_w17.pdf), [Video](https://www.youtube.com/watch?v=BlFUKYwwksk)  
[Lab worksheet]({{ site.baseurl }}/class-material/lab2.1_w17.pdf)  
Dataset [TROPHY.csv]({{ site.baseurl }}/class-material/TROPHY.csv)  
Readings [Feasibility of Treating Prehypertension with an Angiotensin-Receptor Blocker (TROPHY. S. Julius 2006)]({{ site.baseurl }}/class-material/Feasibility of Treating Prehypertension with an Angiotensin-Receptor Blocker TROPHY (S. Julius 2006).pdf), [R Data Types]({{ site.baseurl }}/class-material/Data Types.pdf)  
[Muddy point assessment](https://docs.google.com/forms/d/1cMIZVNnQj5YUmo_Dl3hPqg4bPx3tP0LoKkqj5WpzP6k/viewform)  
- **Homework**:  
[Homework Assignment 1]({{ site.baseurl }}/class-material/525W17_module2_HW1.doc)  

<br>

---
<a name="2.2"></a>
<br>


#### Lecture (2-2): **Approaches to statistical estimation and testing**
- **Time**: 		Feb 14 (Tuesday), 2:30 - 4:00 PM
- **Topics**:
Estimation and standard errors, standard errors for means, correlations, and log odds ratios, formal hypothesis testing, tests involving means, correlations, and log odds ratios, power.
- **Material**:  
[Lecture slides (PDF)]({{ site.baseurl }}/class-material/BI525W17Lec2.2.pdf)  

<br>

#### Lab (2-2): 	**Statistical estimation and hypothesis testing**
- **Time**: 		2:30 – 4:00 PM, Feb 16 (Thursday)
- **Topics**: 
Estimation and standard errors, standard errors for means, correlations, and log odds ratios, formal hypothesis testing, one and two sample tests involving means, power.
- **Material**:  
[Lab worksheet]({{ site.baseurl }}/class-material/lab_2.2_w16.pdf)  
Dataset [TROPHY.csv]({{ site.baseurl }}/class-material/TROPHY.csv)  
[Muddy point assessment](https://docs.google.com/forms/d/1pBpHR8kFX4YKklD1Vzha0UgEYqRs3povnH47HrFk7fM/viewform)  
- **Homework**:  
[Homework Assignment 2]({{ site.baseurl }}/class-material/525W16_module2_HW2.doc)  


<br>

---
<a name="2.3"></a>
<br>

#### Lecture (2-3): **Analyses involving associations**
- **Time**: 		Feb 21 (Tuesday), 2:30 - 4:00 PM
- **Topics**:
Pearson correlation, t-test, odds ratios, discussion of a research article
- **Material**:  
[Lecture slides (PDF)]({{ site.baseurl }}/class-material/BI525W17Lec2.3.pdf)  

<br>

#### Lab (2-3): 	**Pearson correlation, t-test, and log odds ratios**
- **Time**: 		2:30 – 4:00 PM, Feb 23 (Thursday)
- **Topics**:
Tests based on Pearson correlation t-test, and log odds ratios
- **Material**:  
[Lab worksheet]({{ site.baseurl }}/class-material/lab_2.3_w16.pdf)  
[Muddy point assessment](https://docs.google.com/a/umich.edu/forms/d/1P_ldx1K8BJUr2V9ahi4HXymnjvrXXv-hMiopHrkQjIs/viewform)  
- **Homework** (Due 3/14):   
[Homework Assignment 3]({{ site.baseurl }}/class-material/525W17_module2_HW3.doc)  

<br>

---
<a name="2.4"></a>
<br>

#### Lecture (2-4): **Linear regression**
- **Time**: 		Mar 7 (Tuesday), 2:30 - 4:00 PM
- **Topics**:
Single and multiple variable linear regression, Bonferroni correction, power for regression analysis
- **Material**:  
[Lecture slides (PDF)]({{ site.baseurl }}/class-material/BI525W17Lec2.4.pdf)  

<br>

#### Lab (2-4): 	**Regression models**
- **Time**: 		2:30 – 4:00 PM, Mar 9 (Thursday)
- **Topics**:
Fitting regression models for prediction and effect estimation, inference for regression effects, R^2, diagnostics, comparing models
- **Material**:  
[Lab worksheet]({{ site.baseurl }}/class-material/lab_2.4_w16.pdf)  
[Muddy point assessment](https://docs.google.com/forms/d/1tpTEqpT837pSm_8NEty3vUE-7nIMDY3_nx3mGlk5qmg/viewform)  
- **Homework**:  
[Homework Assignment 4]({{ site.baseurl }}/class-material/525W16_module2_HW4.docx)  

<br>

---
<a name="2.5"></a>
<br>

#### Lecture (2-5): **Introduction to graphical methods for multivariate data analysis** 
- **Time**: 		Mar 14 (Tuesday), 2:30 - 4:00 PM
- **Topics**:
Clustering methods, Multidimensional scaling and Principal component analysis
- **Material**:  
[Lecture slides (PDF)]({{ site.baseurl }}/class-material/BI525W17Lec2.5.pdf)  


<br>

#### Lab (2-5): 	**Clustering and principal component analysis**
- **Time**: 		2:30 – 4:00 PM, Mar 16 (Thursday)
- **Topics**:
Multivariate data, Heat maps and dendrograms, clustering methods, principal component analysis 
- **Material**:  
[Muddy point assessment](https://docs.google.com/forms/d/1B2xIMitIxIhYxkvn_kZ4eKDREhZksoGwBX6NtzWIRQE/viewform)

<br>

### Reference material
[RStudio cheatsheet](http://www.rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf): well designed reference card for RStudio features.  
[Try R]() An excellent interactive online R tutorial.  
<!--- files dont exist yet...
[Slides-2.1]()
[Slides-2.2]()
-->

