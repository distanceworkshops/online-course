---
layout: page
sidebar: right
title: "Chapter 5 Stratification, clusters and covariates"
subheadline: "More sophisticated analysis tools"
permalink: /syllabus/Chapter5/
header:
  image_fullwidth: single bird cloud.jpg
---

In this chapter we introduce more challenging designs and analyses.  The study area may be subdivided into smaller regions (strata) and density/abundance estimated within each strata.  Animals may be detected in groups (clusters).  In this situation, cluster density is estimated and individual density is derived by multiplying by expected group size.  However estimating expected group size requires some careful analysis.  Lastly, we can incorporate the effect of factors that might affect detectability into our estimated detection function.

***

##### Variance estimation with systematic survey designs
* <a href="#" data-reveal-id="L1">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch5/L5-1 Variance Estimation for Systematic Designs.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Estimating variance under systematic survey designs
* <a href="#" data-reveal-id="E1">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch5/E5.1 systematic variance estimation.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - Systematic survey design data [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Systematic_variance_2.zip) <img src="{{site.baseurl}}/images/zip32.png">
  - Systematic survey design data (without animal gradient), page 4 of exercise [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Systematic_variance_1.zip) <img src="{{site.baseurl}}/images/zip32.png">  
* <a href="#" data-reveal-id="E1soln">Narrative solution of variance estimation with systematic survey design <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch5/E5.1 systematic variance estimation SOLUTION.pdf)<img src="{{site.baseurl}}/images/pdf32.png">

##### Stratification
* <a href="#" data-reveal-id="L2">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch5/L5-2 Stratification.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Stratification exercise
* <a href="#" data-reveal-id="E2">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch5/E5.2 stratification.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - Antarctic minke whales, stratification [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Stratify exercise.zip) <img src="{{site.baseurl}}/images/zip32.png">
* <a href="#" data-reveal-id="E2soln">Narrative solution to stratification exercise <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch5/E5.2 stratification SOLUTION.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
  - Completed minke whale project [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Stratify solutions.zip) <img src="{{site.baseurl}}/images/zip32.png">

##### Bias associated with group size estimation
* <a href="#" data-reveal-id="L3">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch5/L5-3 Cluster Size.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Bias in group size exercise
* <a href="#" data-reveal-id="E3">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch5/E5.3 cluster size.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - Animals detected in clusters [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Cluster exercise.zip) <img src="{{site.baseurl}}/images/zip32.png">
* <a href="#" data-reveal-id="E3soln">Narrative solution to size-bias exercise <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch5/E5.3 cluster size SOLUTION.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
  - Completed project for size bias correction [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Cluster solutions.zip) <img src="{{site.baseurl}}/images/zip32.png">
  
##### Covariates in the detection function
* <a href="#" data-reveal-id="L4">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch5/L5-4 MCDS.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Complications in detection function models with covariates
* <a href="#" data-reveal-id="L5">Lecture video <img src="{{site.baseurl}}/images/video32.png"></a>
* [Lecture slides]({{site.baseurl}}/lecturepdfs/Ch5/L5-5 MCDS Complications.pdf) <img src="{{site.baseurl}}/images/pdf32.png">

##### Covariate detection function exercise
* <a href="#" data-reveal-id="E4">Exercise description <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise instructions]({{site.baseurl}}/exercisepdfs/Ch5/E5.4 covariates in the detection function.pdf) <img src="{{site.baseurl}}/images/pdf32.png">
  - Exercise section 1
    - Simulated whale survey with covariates [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/CovarWhaleSim.zip) <img src="{{site.baseurl}}/images/zip32.png">
  - Exercise section 2
      - Survey of golf tees with covariates [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/GolfteesExercise.zip) <img src="{{site.baseurl}}/images/zip32.png">
  - Exercise section 3
      - Eastern tropical Pacific dolphin survey [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/Dolphin.zip) <img src="{{site.baseurl}}/images/zip32.png">
  - Exercise section 4
      - Hawaiian amakihi point transect survey [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/fTAMAUK07.zip) <img src="{{site.baseurl}}/images/zip32.png">
      - Alternative method of analysing amakihi data
        - [Description of analysis of these data using R]({{site.baseurl}}/syllabus/Chapter7/#multi-species-survey---montrave-line-transects) <img src="{{site.baseurl}}/images/R_logo32.png">
* <a href="#" data-reveal-id="E4soln">Narrative solution to covariates in detection functions <img src="{{site.baseurl}}/images/video32.png"></a>
* [Exercise solution]({{site.baseurl}}/exercisepdfs/Ch5/E5.4 covariates in the detection function SOLUTION.pdf)<img src="{{site.baseurl}}/images/pdf32.png">
  - Completed project for simulated whale survey [Distance project zip file]({{site.baseurl}}/distance projects/Ch5/CovarWhaleSim-solutions.zip) <img src="{{site.baseurl}}/images/zip32.png">

{% comment %}	
     below here are the links to video clips of lectures and exercise setup and solutions
     Particularly note that youtube video identifiers need to be specified for each clip 
	 
	 Chapter 5			
	Lectures		
		L1	TlNgDFYh_7c
		L2	xzBgwUQtPJQ
		L3	bTcLnQddVSo
		L4	gD11jLtlF-w
		L5	ySMVAuIV8x8
	Exercises		
		E1Q	4NY1nwhf64A
		E1S	Wr6RslBQu5M
		E2Q	oKIzmLQQWO8
		E2S	lAEgJsNHeYs
		E3Q	-ubiLuJUvNo
		E3S	Ewl_8Y_Vgo4
		E4Q	XyZ8apcvsZI
		E4S	eAR1l8oITLI
{% endcomment %}

<div id="L1" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 1 - assessing model performance</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/TlNgDFYh_7c?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 1 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/4NY1nwhf64A?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E1soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 1 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/Wr6RslBQu5M?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="L2" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 2 - assessing model performance</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/xzBgwUQtPJQ?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E2" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 2 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/oKIzmLQQWO8?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E2soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 2 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/lAEgJsNHeYs?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="L3" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 3 - assessing model performance</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/bTcLnQddVSo?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E3" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 3 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/-ubiLuJUvNo?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E3soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 3 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/Ewl_8Y_Vgo4?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="L4" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 4 - assessing model performance</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/gD11jLtlF-w?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="L5" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Lecture 5 - assessing model performance</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/ySMVAuIV8x8?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E4" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Exercise 4 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/XyZ8apcvsZI?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="E4soln" class="reveal-modal large" data-reveal="" aria-labelledby="modalTitle">
  <h3 id="modalTitle">Solution to Exercise 4 - model selection with ducknest data</h3>
  <div class="flex-video widescreen" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/eAR1l8oITLI?vq=hd720&amp;rel=0;showinfo=0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
