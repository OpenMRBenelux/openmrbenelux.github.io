---
title: OpenMR Benelux 2020
subtitle: Program
layout: page
show_sidebar: false
#tabs: example_tabs
#hero_image: assets/ext_images/Home_logo.png
---

<!-- ## Information about the program -->

<html>
<head>
<style>
   table.fixed { table-layout: fixed; }

/* Popup container */
.popup {
  position: relative;
  display: inline-block;
  cursor: pointer;
}

/* The actual popup (appears on top) */
.popup .popuptext {
  visibility: hidden;
  width: 450px;
  background-color: #555;
  color: #fff;
  text-align: justify;
  border-radius: 6px;
  padding: 15px 15px 15px 15px;
  position: absolute;
  z-index: 1;
  bottom: 125%;
  left: 50%;
  margin-left: -80px;
}
.popuptext {
  font-size: 11px;
}

/* Popup arrow */
.popup .popuptext::after {
  content: "";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #555 transparent transparent transparent;
}

/* Toggle this class when clicking on the popup container (hide and show the popup) */
.popup .show {
  visibility: visible;
  -webkit-animation: fadeIn 1s;
  animation: fadeIn 1s
}

/* Add animation (fade in the popup) */
@-webkit-keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity:1 ;}
}
</style>
</head>

<body>

<p align=" justify">The preliminary program for <i>OpenMR Benelux 2020</i> is shown below. The event will span three days, with the first day consisting of talks by prominent researchers in the field of MRI and open science. The second and third day will be spent on workshops, hackathons, interactive discussions, and training sessions. A more detailed program will follow soon.</p>

<p>&nbsp;</p>

<div style="overflow-x:auto;">
<table width="100%" cellspacing="0" cellpadding="2" class="fixed">
    <col width="150px" />
    <col width="650px" />
    <col width="200px" />
    <col width="100px" />
<tbody>

<tr valign="top">
<td style="background: #004777;" bgcolor="#004777" width="14%">
<p><strong><font color="white">Time</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="66%">
<p><strong><font color="white">Program: Tuesday, 21 January 2020</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Talk/Workshop/Demo</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Slides</font></strong></p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>8:15 &ndash; 9:00</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="66%">
<p><strong>Registration and Coffee</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #bcecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>9:00 &ndash; 9:45</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Introduction and Welcome</strong></p>
<p>Stephan Heunis & Organizing Committee</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>9:45 &ndash; 10:15</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<p><strong>Diving Into Metascience – Doing Research on Research</strong></p> 
<p>Marjan Bakker</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>10:15 &ndash; 10:30</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>10:30 &ndash; 11:00</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="66%">
<p><strong>Coffee Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>11:00 &ndash; 11:30</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<div class="popup" onclick="myFunction_cass()"><p><strong>Analytical Flexibility and Questionable Research Practices in MRI</strong></p> 
  <span class="popuptext" id="myPopup_cass"><b>Abstract: </b>The number of methods available for MRI analysis is growing every year. Each of these methods requires the specification of a bewildering array of parameters, not all of which are amenable to optimisation by consensus. The combination of these factors leads to an almost infinite number of ways in which we may analyse our data, and accordingly and infinite number of results which we may choose to report, or not. In this talk I will discuss concerns of such analytic flexibility and the draw of questionable research practices to help uncover the "publishable story" in our data. I will present recent developments in our discipline which may assist the identification of robust effects, and what individual actions we may take in order to retain confidence in our own findings.</span>
</div>
<p>Cassandra Gould van Praag</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>11:30 &ndash; 11:45</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>11:45 &ndash; 12:15</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<p><strong>How can Open Science Contribute to (Clinical) Research in Radiology?</strong></p>
<p>Pim Pullens</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>12:15 &ndash; 12:30</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>12:30 &ndash; 13:30</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="66%">
<p><strong>Lunch</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>13:30 &ndash; 14:00</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<p><strong>Open Science in the Context of Companies, Intellectual Property, and Collaborative Research</strong></p>
<p>TBA</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>14:00 &ndash; 14:15</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>14:15 &ndash; 14:45</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<p><strong>The Open Source Imaging Initiative</strong></p>
<p>Joao Periquito</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>14:45 &ndash; 15:00</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>15:00 &ndash; 15:30</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="66%">
<p><strong>Coffee Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>15:30 &ndash; 16:00</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<div class="popup" onclick="myFunction_daniele()"><p><strong>Current and Future Scenarios for Open Scientific Publishing and Reviewing</strong></p>
  <span class="popuptext" id="myPopup_daniele"><b>Abstract: </b>Communicating our research is a fundamental part of our work as scientists, and a duty towards the society. Typically this communication happens through articles published in scientific journals, after having been reviewed by our peers. We will discuss several aspects of scholarly communication and in particular of scientific publishing and peer review. Some of these aspects are (un-)surprisingly in clear contrast with the idea of science as an open and collaborative public mission. Several solutions and improvements have been proposed and sometimes implemented over the years; on some of them there’s wide consensus, on others there is not. And even when there is consensus to change, the change is slow. We will explore the state of the art and different future perspectives, and discuss our experiences and expectations.</span>
</div>
<p>Daniele Marinazzo</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Interactive Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>16:00 &ndash; 16:15</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>16:15 &ndash; 16:45</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="66%">
<div class="popup" onclick="myFunction_kirstie()"><p><strong>The Turing Way: Reproducible, Inclusive, Collaborative Data Science</strong></p>
  <span class="popuptext" id="myPopup_kirstie"><b>Abstract: </b>Reproducible research is necessary to ensure that scientific work can be trusted. By sharing data, analysis code, and the computational environment used to generate the results, researchers can more effectively stand on the shoulders of their peers and colleagues and deliver high quality, trustworthy, and verifiable outputs. This requires skills in data management, library sciences, software development, and continuous integration techniques: skills that are not widely taught or expected of academic researchers. Skills that are unreasonable, in fact, to expect in one individual team member. 
<br><br> The Turing Way is a handbook to support students, their supervisors, funders, and journal editors in ensuring that reproducible research is "too easy not to do". It includes training material on version control, analysis testing, collaborating in distributed groups, open and transparent communication skills, and effective management of diverse research projects. The Turing Way is openly developed and any and all questions, comments, and recommendations are welcome at our GitHub repository: https://github.com/alan-turing-institute/the-turing-way. 
<br><br> In this talk, Kirstie Whitaker, lead developer of The Turing Way, will take you on a whirlwind tour of the chapters that already exist, the interactive demonstrations you can use and re-use for your own research, and the directions in which we're continuing to develop. All participants will leave the talk knowing that "Every Little Helps" when making their work reproducible, where to ask for help as they start or continue their open research journey, and how they can contribute to improve The Turing Way for future readers.
</span>
</div>
<p>Kirstie Whitaker</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #ffffff;" bgcolor="#ffffff" width="14%">
<p><strong>16:45 &ndash; 17:00</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="66%">
<p><strong>Open Discussion</strong></p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #ffffff;" bgcolor="#ffffff" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>17:00 &ndash; ...</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="66%">
<p><strong>Drinks and Further Discussion</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

</tbody>
</table>
</div>

<!--<p><br><br><strong>Wednesday and Thursday, 22-23 January 2020 </strong>: Parallel sessions for <strong>hackathons</strong> and <strong>training workshops</strong> will take place.</p>-->

<p>&nbsp;</p>
<div style="overflow-x:auto;">  
<table width="100%" cellspacing="0" cellpadding="2" class="fixed">
    <col width="150px" />
    <col width="325px" />
    <col width="325px" />
    <col width="200px" />
    <col width="100px" />
<tbody>

<tr valign="top">
<td style="background: #004777;" bgcolor="#004777" width="14%">
<p><strong><font color="white">Time</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="33%">
<p><strong><font color="white">Program: Wednesday, 22 January 2020</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="33%">
<p>&nbsp;</p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Talk/Workshop/Demo</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Slides</font></strong></p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong></strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><font size="4"><strong>Hack Track</strong></font></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><font size="4"><strong>Train Track</strong></font></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong></strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>9:00 &ndash; 9:30</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Project Pitches</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong></strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong></strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>9:30 &ndash; 11:15</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<div class="popup" onclick="myFunction_fatma()"><p><strong>Reproducibility in Decoded: Case studies from data-intensive sciences</strong></p> 
  <span class="popuptext" id="myPopup_fatma"><b>Abstract: </b>Reproducibility in research is one of the main building blocks of the scientific method. However, there is rising concern about reproducibility in current scientific research that reduces the reliability of published findings in various domains. In this workshop, we will learn about the tools and practices that will help us to improve the reproducibility of our own research pipeline. Based on the book The Practice of Reproducible research I will first introduce reproducible research workflows by providing case-study examples. In the second part, participants will walk through their own research pipeline and create their own reproducible research workflow. In small working groups participants will reflect on their own computational practices and learn how they can improve the reproducibility of their own research workflow.</span>
</div>
<p>Fatma Deniz</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>11:15 &ndash; 11:35</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>11:35 &ndash; 13:20</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>Software Version Control with git and GitHub</strong></p>
<p>Remi Gau & Sofie Van Den Bossche</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Workshop</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>13:20 &ndash; 14:10</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Lunch</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Lunch</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>14:10 &ndash; 15:55</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<div class="popup" onclick="myFunction_serena()"><p><strong>The Basics of Python and Jupyter Notebooks for Medical Image Analysis</strong></p> 
  <span class="popuptext" id="myPopup_serena"><b>Abstract: </b>Python and Jupyter notebooks are becoming more and more essential tools to conduct open and reproducible research. In this workshop, we will first briefly discuss how these tools can facilitate transparent science. Then, we will have a hands-on session where we will code in Jupyter notebook using Python. We will create reproducible workflows using packages that are both basic and specific for medical image analysis (e.g. SimpleITK). Information and materials are available at https://github.com/sbonaretti/2020_OpenMR_jupyter.</span>
</div>
<p>Serena Bonaretti</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Workshop</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>15:55 &ndash; 16:15</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecacac" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>16:15 &ndash; 18:00</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>Introduction to Docker and Binderhub</strong></p>
<p>Lukas Snoek</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

</tbody>
</table>
</div>

<p>&nbsp;</p>

<div style="overflow-x:auto;">  
<table width="100%" cellspacing="0" cellpadding="2" class="fixed">
    <col width="150px" />
    <col width="325px" />
    <col width="325px" />
    <col width="200px" />
    <col width="100px" />  
<tbody>

<tr valign="top">
<td style="background: #004777;" bgcolor="#004777" width="14%">
<p><strong><font color="white">Time</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="33%">
<p><strong><font color="white">Program: Thursday, 23 January 2020</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="33%">
<p>&nbsp;</p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Talk/Workshop/Demo</font></strong></p>
</td>
<td style="background: #004777;" bgcolor="#004777" width="10%">
<p><strong><font color="white">Slides</font></strong></p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong></strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><font size="4"><strong>Hack Track</strong></font></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><font size="4"><strong>Train Track</strong></font></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong></strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>9:00 &ndash; 9:50</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>Building Inclusive and Open Communities</strong></p>
<p>Malvika Sharan</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>9:50 &ndash; 10:40</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<div class="popup" onclick="myFunction_natalia()"><p><strong>Where to Go Next? The Landscape of Post-PhD Career Tracks</strong></p>  
  <span class="popuptext" id="myPopup_natalia">There is a growing disparity between the number of new PhD graduates and the available faculty positions. Effectively, most of the PhD graduates needs to find jobs outside academia. Yet, there is little amount of services dedicated to assisting early career researchers in discovering their core competencies, in searching for employers and landing their dream jobs in industry. Ideally, one should anticipate the potential future market sectors after completing the PhD, and focus on developing transferable skills during the PhD on that basis. This however, remains a rare practice in the graduate schools. Therefore, in this workshop, we will assume that you have no prior experience with the job market in industry. We will discuss the following: the demand for PhDs in different branches of industry; paycheck or entrepreneurship? Is a traineeship at a company a good start after a PhD?; defining your key competences, including both hard- and soft skills; searching for employers who are likely to search for these competences; searching for employers who share your personal values; the role of networking in searching for jobs; restructuring your CV and writing a competitive motivational letter; preparing for job interviews. <br><br> The workshop will be interactive: we will debunk certain myths related to the job market with the use of polls and quizzes. Sharing personal experience by participants will be highly encouraged. The goal of the workshop is to give the participants the information and confidence so they can further search for relevant information on their own, and take their first steps towards finding their dream job in industry.</span>
</div>
<p>Natalia Bielczyk</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>10:40 &ndash; 11:00</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>11:00 &ndash; 11:50</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<div class="popup" onclick="myFunction_sarah()"><p><strong>Probing Brain Organization and Function with Neuroimaging Markers of Connectivity (HBP)</strong></p>
  <span class="popuptext" id="myPopup_sarah"><b>Abstract: </b>Across the past years, many developments arose in connectivity analyses based on MRI data offering now a wide range of connectivity markers. Capitalizing on this wealth of neuroimaging markers, connectivity-based parcellation can be used to unravel the complexity of brain organization. Furthermore, large population-based neuroimaging datasets with extensive psychometric characterization now open promising perspectives to link brain organization to behavior. In particular, interindividual variability in brain’s region functional connectivity can be related to interindividual variability in psychometric data by using a connectivity-based psychometric prediction approach. Despite some challenges associated to the use of these data-driven approaches, they also offer opportunities to better understand the relationships between brain connectivity and human behavior.</span>
</div>
<p>Sarah Genon</p>
<p><strong>Human Brain Atlas (HBP)</strong></p>
<p>TBA</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Workshop</strong></p>
<p>&nbsp;</p>
<br><p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>11:50 &ndash; 12:40</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>MR Image Registration with Elastix and Simple Elastix</strong></p>
<p>Stefan Klein</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>12:40 &ndash; 13:20</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Lunch</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Lunch</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>13:20 &ndash; 14:10</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>Converting Neuroimaging Data to BIDS</strong></p>
<p>Marcel Zwiers & Robert Oostenveld</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>14:10 &ndash; 15:00</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">

<div class="popup" onclick="myFunction_tim()"><p><strong>Web technologies in neuroimaging</strong></p>
  <span class="popuptext" id="myPopup_tony"><b>Abstract: </b>
    How do we share and communicate your analysis pathways? By means of a text-description in a paper, or are there other ways? In this day and age where everything happens online, it should be possible to leverage web technologies for neuroimaging. Indeed, there is a growing number of web tools to share and communicate project information, data sets, and entire interactive workflows online. In this talk I will discuss a variety of these projects, how to get started or even involved in them, and what I believe is the future of data analysis and neuroimaging.
  </span>
</div>

<p>Tim van Mourik</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>Workshop</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>15:00 &ndash; 15:20</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecacac" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Break</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>15:20 &ndash; 16:10</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<div class="popup" onclick="myFunction_tony()"><p><strong>Numerical Simulation of MR Physics</strong></p>
  <span class="popuptext" id="myPopup_tony"><b>Abstract: </b>MR simulations based on the Bloch Equations are of high educational value. Further, they serve as essential tools in MRI method development, e.g. for MR sequence design and protocol optimization or generating ground truth data for image reconstruction and post-processing algorithms. This lecture provides insight into practical implementation of computer simulations based on classical MR physics. Analytical solutions versus numerical implementations will be discussed. Based on pictorial examples, an introduction to various MRI simulator software packages will be given. The JEMRIS simulation environment will serve for most of the examples shown in this lecture.</span>
</div>
<p>Tony Stöcker</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="14%">
<p><strong>16:10 &ndash; 17:00</strong></p>
</td>
<td style="background: #dbf4fc;" bgcolor="#dbf4fc" width="33%">
<p><strong>Hackathon</strong></p>
</td>
<td style="background: #e8f7fc;" bgcolor="#e8f7fc" width="33%">
<p><strong>Find, use and share scientific data with the EBRAINS Knowledge Graph (HBP)</strong></p>
<p>Oliver Schmid</p>
<p><strong>Sharing GDPR Compliant Neuroimaging Research Data</strong></p>
<p>Stephan Heunis</p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p><strong>TBA</strong></p>
<p>&nbsp;</p>
<p><strong>Talk</strong></p>
</td>
<td style="background: #F5F5F5;" bgcolor="#F5F5F5" width="10%">
<p>&nbsp;</p>
</td>
</tr>

<tr valign="top">
<td style="background: #cecaca;" bgcolor="#cecaca" width="14%">
<p><strong>17:00 &ndash; 18:00</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong>Project Wrap-ups and Overall Wrap-up</strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="33%">
<p><strong></strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p><strong></strong></p>
</td>
<td style="background: #cecaca;" bgcolor="#cecaca" width="10%">
<p>&nbsp;</p>
</td>
</tr>

</tbody>
</table>
</div>

<script>
// When the user clicks on <div>, open the popup
function myFunction_marjan() {
  var popup = document.getElementById("myPopup_marjan");
  popup.classList.toggle("show");
}
function myFunction_cass() {
  var popup = document.getElementById("myPopup_cass");
  popup.classList.toggle("show");
}
function myFunction_pim() {
  var popup = document.getElementById("myPopup_pim");
  popup.classList.toggle("show");
}
function myFunction_joao() {
  var popup = document.getElementById("myPopup_joao");
  popup.classList.toggle("show");
}
function myFunction_daniele() {
  var popup = document.getElementById("myPopup_daniele");
  popup.classList.toggle("show");
}
function myFunction_kirstie() {
  var popup = document.getElementById("myPopup_kirstie");
  popup.classList.toggle("show");
}
function myFunction_fatma() {
  var popup = document.getElementById("myPopup_fatma");
  popup.classList.toggle("show");
}
function myFunction_remi() {
  var popup = document.getElementById("myPopup_remi");
  popup.classList.toggle("show");
}
function myFunction_serena() {
  var popup = document.getElementById("myPopup_serena");
  popup.classList.toggle("show");
}
function myFunction_malvika() {
  var popup = document.getElementById("myPopup_malvika");
  popup.classList.toggle("show");
}
function myFunction_natalia() {
  var popup = document.getElementById("myPopup_natalia");
  popup.classList.toggle("show");
}
function myFunction_sarah() {
  var popup = document.getElementById("myPopup_sarah");
  popup.classList.toggle("show");
}
function myFunction_stefan() {
  var popup = document.getElementById("myPopup_stefan");
  popup.classList.toggle("show");
}
function myFunction_marcel() {
  var popup = document.getElementById("myPopup_marcel");
  popup.classList.toggle("show");
}
function myFunction_tim() {
  var popup = document.getElementById("myPopup_tim");
  popup.classList.toggle("show");
}
function myFunction_tony() {
  var popup = document.getElementById("myPopup_tony");
  popup.classList.toggle("show");
}
function myFunction_oliver() {
  var popup = document.getElementById("myPopup_oliver");
  popup.classList.toggle("show");
}
function myFunction_stephan() {
  var popup = document.getElementById("myPopup_stephan");
  popup.classList.toggle("show");
}
</script>
</body>
</html>
