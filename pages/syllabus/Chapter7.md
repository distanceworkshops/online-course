---
layout: page
sidebar: right
subheadline: An alternative analysis workflow
title: Chapter 7 Analysis using R
permalink: /syllabus/Chapter7/
header:
  image_fullwidth: ray-hennessy-cardinal-unsplash.jpg
---

Previous chapters have described analysis of distance sampling data using the Distance software.  Much of the code that underlies the graphical interface of the Distance software is written in the programming language __R__.  Some people use the [R software](https://www.r-project.org/about.html) for data management and exploratory data analysis.  Use of __R__ has been made easier with the advent of a development environment [_R-Studio_](https://www.rstudio.com/products/RStudio/).  Both pieces of software are free of charge and can be easily downloaded and installed.  Please install both of those pieces of software before beginning these exercises.  In addition, software for analysing distance sampling data in __R__ resides in a package called [_Distance_](https://cran.r-project.org/web/packages/Distance/index.html).  Install that package as well.  There are several demonstrations of the process of installing __R__, _R-Studio_ and __R__ packages on the web.  One such description [can be found here](http://web.cs.ucla.edu/~gulzar/rstudio/).

This chapter guides you through analyses of data sets you have already seen in earlier sections of this workshop.  Specifically, you will re-visit the 

- [duck nest data]({{site.baseurl}}/exercisepdfs/Ch1/E1.4 ducknests in Distance.pdf)
- [Hawaiian amakihi data]({{site.baseurl}}/exercisepdfs/Ch5/E5.4 covariates in the detection function.pdf) (Question 4) and
- [Montrave point count data]({{site.baseurl}}/exercisepdfs/Ch3/E3.1 point transects.pdf) (Question 2).

You will also analyse data from a lure survey of Scottish crossbills.  Data from this type of survey, described in the [lecture on multipliers]({{site.baseurl}}/lecturepdfs/Ch6/L6-2 Multipliers.pdf) (Slide 21), cannot be analysed in Distance for Windows; and demonstrates the flexibility available for distance sampling analysis using R.

--------

### Lecture on using R for distance sampling analysis
* <a href="#" data-reveal-id="L1">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch7/L7-1 R version.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

### Exercises

#### Conventional distance sampling - Monte Verde duck nest line transects
* <a href="#" data-reveal-id="E1">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch7/E7-1-ducknests-q.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - [Duck nest line transect csv file]({{site.baseurl}}/exercisepdfs/Ch7/datasets/ducks-area-effort.csv) <img src="{{site.baseurl}}/images/csv32b.png">
* <a href="#" data-reveal-id="E1soln">Narrative solution for duck nest analysis in R <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch7/E7-1-ducknests-sol.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
* [R markdown file creating duck nest exercise]({{site.baseurl}}/exercisepdfs/Ch7/E7-1-ducknests.rmd) <img src="{{site.baseurl}}/images/md32.png">

#### Fitting detection function with covariates - Hawaiian amakihi point transects
* <a href="#" data-reveal-id="E2">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch7/E7-2-covariates-q.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - [Amakihi point transect csv file]({{site.baseurl}}/exercisepdfs/Ch7/datasets/amakihi.csv) <img src="{{site.baseurl}}/images/csv32b.png">
* <a href="#" data-reveal-id="E2soln">Narrative solution for amakihi point transects in R <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch7/E7-2-covariates-sol.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
* [R markdown file creating amakihi exercise]({{site.baseurl}}/exercisepdfs/Ch7/E7-2-covariates.rmd) <img src="{{site.baseurl}}/images/md32.png">

#### Lure point transects: dual surveys - Scottish crossbills
* <a href="#" data-reveal-id="E3">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch7/E7-3-crossbills-q.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - [Crossbill lure trials csv file]({{site.baseurl}}/exercisepdfs/Ch7/datasets/lure-trials.csv) <img src="{{site.baseurl}}/images/csv32b.png">
  - [Crossbill main survey csv file]({{site.baseurl}}/exercisepdfs/Ch7/datasets/mainsurveydetections.csv) <img src="{{site.baseurl}}/images/csv32b.png">
* <a href="#" data-reveal-id="E3soln">Narrative solution for lure point transects in R <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch7/E7-3-crossbills-sol.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
* [R markdown file creating crossbill exercise]({{site.baseurl}}/exercisepdfs/Ch7/E7-3-crossbills.rmd) <img src="{{site.baseurl}}/images/md32.png">


#### Multi-species survey - Montrave line transects
* <a href="#" data-reveal-id="E4">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch7/E7-4-multispecies-q.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - [Montrave line transect csv file]({{site.baseurl}}/exercisepdfs/Ch7/datasets/amakihi.csv) <img src="{{site.baseurl}}/images/csv32b.png">
* <a href="#" data-reveal-id="E4soln">Narrative solution for Montrave line transects in R <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch7/E7-4-multispecies-sol.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
* [R markdown file creating Montrave exercise]({{site.baseurl}}/exercisepdfs/Ch7/E7-4-multispecies.rmd) <img src="{{site.baseurl}}/images/md32.png">


{% comment %}

    below here are the links to video clips of lectures and exercise setup and solutions
     Particularly note that youtube video identifiers need to be specified for each clip 
	Chapter 7			
	Lectures		
		L1	nPyQcLLJwns 
	Exercises		
		E1Q	KizkMRuNnfE 
		E1S	s5HXvFN6Avc 
		E2Q	igKEHILGYQg  
		E2S	apBPl86OjB4  
		E3Q	QMOehuEs_Yw  
		E3S	-AovikGwrNc  
		E4Q	A0J7b5B62D0  
		E4S	A8fMzjgLyDw  

{% endcomment %}

<div id="L1" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture - overview of distance sampling analysis with R</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/nPyQcLLJwns?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 1 - conventional distance sampling</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/KizkMRuNnfE?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 1 - conventional distance sampling</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/s5HXvFN6Avc?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E2" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 2 - covariates in detection function</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/igKEHILGYQg?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E2soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 2 - covariates in detection function</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/apBPl86OjB4?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E3" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 3 - lure point transects</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/QMOehuEs_Yw?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E3soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 3 - lure point transects</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/-AovikGwrNc?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E4" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 4 - analysis of multi-species surveys</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/A0J7b5B62D0?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E4soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 4 - analysis of multi-species surveys</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/A8fMzjgLyDw?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>