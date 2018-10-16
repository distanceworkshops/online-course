---
layout: page
sidebar: right
subheadline: An alternative analysis workflow
title: Chapter 7 Analysis using R
permalink: /syllabus/Chapter7/
header:
  image_fullwidth: rawpixel-983726-unsplash.jpg
---

Previous chapters have described analysis of distance sampling data using the Distance software.  Much of the code that underlies the graphical interface of the Distance software is written in the programming language __R__.  Some people use the [R software](https://www.r-project.org/about.html) for data management and exploratory data analysis.  Use of __R__ has been made easier with the advent of a development environment [_R-Studio_](https://www.rstudio.com/products/RStudio/).  Both pieces of software are free of charge and can be easily downloaded and installed.  Please install both of those pieces of software before beginning these exercises.  In addition, software for analysing distance sampling data in __R__ resides in a package called [_Distance_](https://cran.r-project.org/web/packages/Distance/index.html).  Install that package as well.  There are several demonstrations of the process of installing __R__, _R-Studio_ and __R__ packages on the web.  One such description [can be found here](http://web.cs.ucla.edu/~gulzar/rstudio/).

This chapter guides you through analyses of data sets you have already seen in earlier sections of this workshop.  Specifically, you will re-visit the 

- [duck nest data]({{site.baseurl}}/exercisepdfs/Ch1/E1.4 ducknests in Distance.pdf)
- [Hawaiian amakihi data]({{site.baseurl}}/exercisepdfs/Ch5/E5.4 covariates in the detection function.pdf) (Question 4) and
- [Montrave point count data]({{site.baseurl}}/exercisepdfs/Ch3/E3.1 point transects.pdf) (Question 2).

You will also analyse data from a lure survey of Scottish crossbills.  Data from this type of survey, described in the [lecture on multipliers]({{site.baseurl}}/lecturepdfs/Ch6/L6-2 Multipliers.pdf) (Slide 21), cannot be analysed in Distance for Windows; and demonstrates the flexibility available for distance sampling analysis using R.
***

##### Demonstration of data import to Distance
* <a href="#" data-reveal-id="L1">Demonstration video <img src="{{site.baseurl}}/images/video32.png"></a>
  - Text files containing data used in demonstration
    - [SimpleData.txt]({{site.baseurl}}/distance projects/Ch6/SimpleData.txt) <img src="{{site.baseurl}}/images/txt32.png">
    - [SimpleDataSpp.txt]({{site.baseurl}}/distance projects/Ch6/SimpleDataSpp.txt) <img src="{{site.baseurl}}/images/txt32.png">
    - [SimpleDataSppLabel.txt]({{site.baseurl}}/distance projects/Ch6/SimpleDataSppLabel.txt) <img src="{{site.baseurl}}/images/txt32.png">	
    - [Stratum.txt]({{site.baseurl}}/distance projects/Ch6/Stratum.txt) <img src="{{site.baseurl}}/images/txt32.png">
    - [transect.txt]({{site.baseurl}}/distance projects/Ch6/transect.txt) <img src="{{site.baseurl}}/images/txt32.png">
    - [Observation.txt]({{site.baseurl}}/distance projects/Ch6/Observation.txt) <img src="{{site.baseurl}}/images/txt32.png">	
	
##### Introductory lecture
* <a href="#" data-reveal-id="L1">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch7/L7-1 R version.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Exercise using multipliers: deer density estimation from faecal pellets
* <a href="#" data-reveal-id="E1">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch6/E6.1 multipliers.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - Deer pellet data from southern Scotland [Distance project zip file]({{site.baseurl}}/distance projects/Ch6/Deer pellets.zip) <img src="{{site.baseurl}}/images/zip32.png">
* <a href="#" data-reveal-id="E1soln">Narrative solution for deer pellet exercise <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch6/E6.1 multipliers SOLUTION_DH_adjusted.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
  - Completed deer pellet project [Distance project zip file]({{site.baseurl}}/distance projects/Ch6/Deer pellets solution.zip) <img src="{{site.baseurl}}/images/zip32.png">

##### Where to go next?  
* <a href="#" data-reveal-id="L3">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch6/L6-3 whats next-ER.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

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

<div id="L2" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 2 - multipliers</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/wMI-F6qsi30?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 1 - multipliers for deer pellet analysis</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/F71J2cRnAlk?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 1 - multipliers for deer pellet analysis</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/RnEAHnAl5aY?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="L3" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 3 - advance distance sampling analysis methods</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/8KWHu2Hj7Ys?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

