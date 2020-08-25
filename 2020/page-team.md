---
title: OpenMR Benelux 2020
subtitle: Meet the team
layout: page
show_sidebar: false
menubar: past_events
#hero_image: assets/ext_images/Home_logo.png
---

<html>
<head>
<style>
img {
  width: 30%;
  height: auto;
  display: inline-block;
}
.accordion:after {
  content: '\002B'; /* Unicode character for "plus" sign (+) */
  font-size: 13px;
  color: #ffffff;
  float: right;
  margin-left: 5px;
}
.active:after {
  content: "\2212"; /* Unicode character for "minus" sign (-) */
  font-size: 13px;
  color: #ffffff;
  float: right;
  margin-left: 5px;
}
/* Style the buttons that are used to open and close the accordion panel */
.accordion {
  background-color: #004777;
  color: #ffffff;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  text-align: left;
  border: none;
  outline: none;
  transition: 0.4s;
}
/* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
.active, .accordion:hover {
  background-color: #004777;
}
/* Style the accordion panel. Note: hidden by default */
.panel {
  padding: 0 18px;
  background-color: #ffffff;
  display: none;
  overflow: hidden;
}
</style>
</head>
<body>

<a name="top"></a>
<h2 style="color:#004777"> Organizing committee </h2>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="stephan"></a>
{% include speaker-card.html
  avatarurl="stephan.png"
  profilename="Stephan Heunis"
  affiliation="Eindhoven University of Technology"
  city="Eindhoven, The Netherlands"
  homepage="https://www.fmrwhy.com/"
  git="https://github.com/jsheunis/"
  twitter="https://www.twitter.com/fmrwhy"
  researchgate="https://www.researchgate.net/profile/Stephan_Heunis2" %}
</td>
<td width="500px" align="left" valign="center">
<a name="emanoel"></a>
{% include speaker-card.html
  avatarurl="emanoel.jpg"
  profilename="Emanoel Sabidussi"
  affiliation="University Medical Center Rotterdam"
  city="Rotterdam, The Netherlands"
  git="https://github.com/Emanoel-sabidussi"
  twitter="https://www.twitter.com/sabidussi"%}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Stephan is a researcher and PhD candidate at the Electrical Engineering Department of the Eindhoven University of Technology in the Netherlands. His research focuses on developing new acquisition and signal processing methods for functional neuroimaging that allow the real-time tracking and visualisation of distributed MRI brain activity patterns. Stephan is passionate about making research and scientific practice more transparent, rigorous, and inclusive. He started the <a href="https://osceindhoven.github.io/">Open Science Community Eindhoven</a>, which is part of a wide Dutch network of researchers and university employees that focuses on improving scientific practice. He is also the founder of <a href="https://openmrbenelux.github.io/">OpenMR Benelux</a>, a community working on wider adoption of open science principles in MRI research through talks, discussions, workshops, and hackathons.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Emanoel is a PhD researcher at the Erasmus Medical Center, in Rotterdam, The Netherlands. His research is focused on integrated methods for MR relaxometry and patient motion correction. Within the <a href="http://bigr.nl/">Biomedical Imaging Group Rotterdam</a>, he is involved in developing deep learning and analytical methods to reduce the influence motion corruption has in quantitative maps, increasing the reliability of estimation and patient comfort. He is one of the 15 early stage researchers of the B-Q Minded EU H2020 project which combines research, innovation, and education in the field of quantitative MRI.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="vincenzo"></a>
{% include speaker-card.html
  avatarurl="vincenzo.jpg"
  profilename="Vincenzo Anania"
  affiliation="icometrix, Leuven<br> imec-Visionlab, University of Antwerp, Antwerp"
  city="Belgium"
  git="https://github.com/vins9100" %}
</td>
<td width="500px" align="left" valign="center">
<a name="hannes"></a>
{% include speaker-card.html
  avatarurl="hannes.png"
  profilename="Hannes Almgren"
  affiliation="Department of Data Analysis <br> Faculty of Psychology and Educational Sciences <br> Ghent University"
  city="Ghent, Belgium"
  git="https://github.com/halmgren"
  twitter="https://www.twitter.com/Hannes_Almgren" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Vincenzo Anania is a PhD researcher at icometrix (Leuven, Belgium) and imec-Visionlab (University of Antwerp, Belgium). His research focuses on robust parameter estimation from diffusion weighted MR images. He is one of the 15 early stage researchers of the B-Q Minded EU H2020 project which combines research, innovation, and education in the field of quantitative MRI.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Hannes is a PhD candidate at the Department of Data Analysis (Ghent University, Belgium). His main research interests concern functional and effective connectivity during task execution and resting state, in both a methodological and applied context. He is a passionate proponent of open science in general, with a specific interest in open analyses (e.g., computer code) and open data. He has been previously co-organizer of Brainhack Ghent 2017 and 2018, and has given multiple talks on open science. </p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="sofie"></a>
{% include speaker-card.html
  avatarurl="sofie.png"
  profilename="Sofie Van Den Bossche"
  affiliation="Department of Data Analysis <br> Faculty of Psychology and Educational Sciences <br> Ghent University"
  city="Ghent, Belgium"
  git="https://github.com/sofievdbos"
  twitter="https://www.twitter.com/sofie_vdbos"
  researchgate="https://www.researchgate.net/profile/Sofie_Van_Den_Bossche2" %}
</td>
<td width="500px" align="left" valign="center">
<a name="remi"></a>
{% include speaker-card.html
  avatarurl="remi.png"
  profilename="Remi Gau"
  affiliation="Université catholique de Louvain"
  city="Louvain-la-Neuve, Belgium"
  homepage="https://remi-gau.github.io/"
  git="https://github.com/Remi-Gau"
  twitter="https://www.twitter.com/RemiGau"
  researchgate="https://www.researchgate.net/profile/Remi_Gau" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
    <p align="justify" style="font-family: arial;"><br>Sofie is currently doing a PhD at the Department of Data Analysis (Ghent University, Ghent, Belgium), supervised by Prof. Dr. Daniele Marinazzo. Her research focuses on the intertwined domains of (resting-state) neuroscience and lateralization/handedness. During her PhD, she has also been involved in Open Science events, either as part of the organizing committee (BrainHack Ghent <a href="https://brainhackghent.wixsite.com/brainhackghent/submitted-projects">2017</a>/<a href="https://brainhackghent.github.io/">2018</a> and <a href="http://www.brainhack.org/global2019/">Brainhack Global 2019</a>) or as a volunteer (e.g. Pint of Science, Ghent). Creating an Open Science community and communicating Open Science to a broader public is something she wants to be progressively involved in.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Remi is a postdoctoral fellow in the Crossmodal Perception and Plasticity laboratory (<a href="https://cpplab.be" >CPP-Lab</a>) at the Université catholique de Louvain. His work focuses on the multisensory aspects of perception and he uses high-resolution MRI to address these questions. He sees in open science a way to a) build a more inclusive research community based on cooperation rather than competition and b) addresses some of the replicability and reproducibility issues that are affecting many areas of science.</p>
</div>
</td>
</tr>
</table>

</div>

<img src="../../assets/ext_images/post_separator.png" alt="text"> 

<h2 style="color:#004777"> Advisors </h2>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="daniele"></a>
{% include speaker-card.html
  avatarurl="daniele.png"
  profilename="Daniele Marinazzo"
  affiliation="Department of Data Analysis <br>Faculty of Psychology and Educational Sciences <br>Ghent University"
  city="Ghent, Belgium"
  homepage="http://users.ugent.be/~dmarinaz/"
  twitter="https://twitter.com/dan_marinazzo"                                                           
  git="https://github.com/danielemarinazzo"
  researchgate="https://www.researchgate.net/profile/Daniele_Marinazzo" %}
</td>
<td width="500px" align="left" valign="center">
<a name="natalia"></a>
{% include speaker-card.html
  avatarurl="natalia.png"
  profilename="Natalia Bielczyk"
  affiliation="Founder, Director and Chairperson Stichting Solaris Onderzoek en Ontwikkeling <br> <br> eLife Associate <br> <br> Career Development and Mentoring Manager Organization for Human Brain Mapping"
  homepage="https://www.nataliabielczyk.com/"
  twitter="https://www.twitter.com/nbielczyk_neuro"
  researchgate="https://www.researchgate.net/profile/Natalia_Bielczyk2" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Daniele Marinazzo is an associate professor in the Department of Data Analysis of the Faculty of Psychology and Educational Sciences at Ghent University. His team focuses on methodological and computational aspects of neuroscience research, and on the dynamical networks subserving function, as well as thorough statistical validation of the results. They develop new techniques for inferring connectivity architectures from the dynamics of the recorded data, in challenging cases of short, noisy and redundant time series, as those encountered in neuroimaging. Daniele cares about open science and ways to improve the review/editorial process. He is an editor at several journals in his field, including PLOS Computational Biology, PLOS One, NeuroImage, Brain Topography, Network Neuroscience. Visit Daniele’s <a href="https://publons.com/researcher/663417/daniele-marinazzo">Publons review profile</a> for more.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Natalia Bielczyk has a background in Physics, Mathematics and Psychology (3 x MSc), obtained at the College of Interfaculty Studies in Mathematics and Natural Sciences, University of Warsaw. She is now completing her thesis within the Donders Graduate School, Donders Institute for Brain, Cognition and Behavior, Nijmegen, the Netherlands. Her research concerns developing new methods for connectomics in the domain of cognitive neuroimaging, i.e. for functional and effective connectivity research. Natalia also currently holds a position of a Career Development and Mentoring Manager within the <a href="https://www.ohbmtrainees.com/">Organization for Human Brain Mapping Student and Postdoc Special Interest Group</a>, and serves as an eLife Associate within the <a href="https://elifesciences.org/inside-elife/a946c355/elife-community-ambassadors-243-volunteers-join-the-programme-in-2019">eLife Ambassadors community</a>. In private, she is also a dedicated <a href="https://www.nataliabielczyk.com/">blogger</a>, and a speaker, giving workshops and talks about self-development in academia and transitions to industry. In November 2018, she founded Stichting Solaris Onderzoek en Ontwikkeling in a response to lack of assistance for early career researchers in career development in academia and beyond.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="tim"></a>
{% include speaker-card.html
  avatarurl="tim.png"
  profilename="Tim van Mourik"
  affiliation="Donders Institute for Brain, Cognition and Behaviour"
  city="Nijmegen, The Netherlands"
  homepage="https://timvanmourik.com/"
  twitter="https://twitter.com/tim_van_mourik?lang=nl"                                  
  git="https://github.com/TimVanMourik"
  researchgate="https://www.researchgate.net/profile/Tim_Van_Mourik" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Tim van Mourik is a PostDoc at the Donders Centre for Cognitive Neuroimaging. During his PhD he developed analysis tools to analyse fMRI scans at an even finer level of detail: that of the cortical layers. In doing so, he not only developed the new tools for obtaining laminar signals, but also applications to build graphical pipelines with these tools (<a href="https://timvanmourik.github.io/Porcupine/">Porcupine</a>). In addition, he set up web applications to facilitate sharing fMRI results in augmented reality (<a href="https://armadillo-brain.herokuapp.com">ARmadillo</a>) and improved collaboration on interactive workflows (<a href="https://giraffe.tools">GiraffeTools</a>). At the OHBM conference 2019, Tim was the chair of the Open Science Room and in charge of organising a week long program with talks, discussions, and demos towards open and reproducible research practices.</p>
</div>
</td>
</tr>
</table>

</div>

<img src="../../assets/ext_images/post_separator.png" alt="text"> 
<br>
<a href="../page-team#top"><i class="fas fa-arrow-alt-circle-up" style="position: relative; top: -3px; text-indent: 0px; vertical-align: middle; color:#004777;"></i></a>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    /* Toggle between adding and removing the "active" class,
    to highlight the button that controls the panel */
    this.classList.toggle("active");

   /* Toggle between hiding and showing the active panel */
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>

</body>
</html>
