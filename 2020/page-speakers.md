---
title: OpenMR Benelux 2020
subtitle: Speakers
layout: page
show_sidebar: false
menubar: past_events
#tabs: example_tabs
#hero_image: assets/ext_images/Home_logo.png
---

<!--- ## Information about the confirmed speakers -->

<html>
<head>
<style>
table tr:nth-of-type(3n) td {
    border-bottom: 2px solid #004777;
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

<!-- <h2 style="color:#004777"> Speakers </h2> -->
<h2 style="color:#004777"> Tuesday, 21 January 2020 </h2>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="marjan"></a>
{% include speaker-card-2020.html
  avatarurl="marjan.png"
  profilename="Marjan Bakker"
  affiliation="Tilburg School of Social and Behavioral Sciences <br>Department of Methodology and Statistics <br>Tilburg University"
  city="Tilburg, The Netherlands"
  homepage="http://www.marjanbakker.eu/"%}
</td>
<td width="500px" align="left" valign="center">
<a name="cassandra"></a>
{% include speaker-card-2020.html
  avatarurl="cass.png"
  profilename="Cassandra Gould van Praag"
  affiliation="Psychopharmacology and Emotion Research Laboratory <br>Department of Psychiatry <br>University of Oxford"
  city="Oxford, UK"
  homepage="https://www.psych.ox.ac.uk/team/cassandra-gould-van-praag"
  git="https://github.com/cassgvp"
  twitter="https://twitter.com/cassgvp" 
  researchgate="https://www.researchgate.net/profile/Cassandra_Gould_Van_Praag" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Marjan Bakker is an assistant professor at the Methods and Statistics Department at Tilburg University. She is part of the Meta-Research Center in Tilburg at which they study the scientific system in psychology; in general to find its flaws and empirically test potential solutions. She wants to improve science by investigating problems and possible solutions. Her interests consist of reporting errors, the use of questionable research practices, statistical power, outliers in data, publication bias, and preregistration. Currently, she is mainly working on some larger projects on preregistration and on a project to replicate Mahoney’s seminal study on publication bias (for which she got an NWO replication grant).</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Cass is a postdoctoral researcher at the University of Oxford Department of Psychiatry. She provides support for (f)MRI experimental design and analysis in the investigation of treatments for mood disorders. In this role, she has to stay up to speed with the leading edge of analytic tools, and is constantly on the lookout for tips, tricks, and techniques to make this research quicker, slicker, and more effective. This goes hand-in-hand with making the research more transparent and reproducible, and freely sharing the outputs of our labour. She is a contributor to <a href="https://the-turing-way.netlify.com/introduction/introduction">The Turing Way</a> and works with the <a href="https://www.win.ox.ac.uk/open-neuroimaging/open-neuroimaging-project">Wellcome Centre for Integrative Neuroimaging Open Community Team</a>. She is a passionate believer in accessibility and the equitable dissemination of knowledge, and spends a lot of time showing people that programming isn’t scary.</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Diving Into Metascience – Doing Research on Research</b><br><br>Marjan Bakker will build her talk around the replication crisis in science. She will show examples of p-hacking and will discuss the surprising fraction of confirmed hypotheses. This is not only a problem in psychology attested by examples of failure to replicate studies in other fields. She pleads for preregistration of hypothesis, study-design, and analysis plan to minimize the researcher’s degrees of freedom.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Analytical Flexibility and Questionable Research Practices in MRI</b><br><br>The number of methods available for MRI analysis is growing every year. Each of these methods requires the specification of a bewildering array of parameters, not all of which are amenable to optimisation by consensus. The combination of these factors leads to an almost infinite number of ways in which we may analyse our data, and accordingly an infinite number of results which we may choose to report, or not. In this talk, I will discuss concerns of such analytic flexibility and the draw of questionable research practices to help uncover the "publishable story" in our data. I will present recent developments in our discipline which may assist the identification of robust effects, and what individual actions we may take in order to retain confidence in our own findings.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="pim"></a>
{% include speaker-card-2020.html
  avatarurl="pim.png"
  profilename="Pim Pullens"
  affiliation="Department of Radiology (Ghent University - Ghent University Hospital) and Ghent Institute for Functional and Metabolic Imaging (GIfMI)"
  city="Ghent, Belgium" 
  twitter="https://www.twitter.com/pim_pullens" 
  researchgate="https://www.researchgate.net/profile/Pim_Pullens" %}
</td>
<td width="500px" align="left" valign="center">
<a name="dirk"></a>
{% include speaker-card-2020.html
  avatarurl="DirkSmeets.jpg"
  profilename="Dirk Smeets"
  affiliation="icometrix"
  city="Leuven, Belgium" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Pim Pullens (PhD) is MR physicist in the University Hospital Ghent & Ghent Institute for functional and Metabolic Imaging. He is responsible for the management of three clinical MRs and one research system. Next to his clinical work, he is involved in various research projects, both in Ghent and internationally, on functional and structural imaging in multiple organs and body parts. Pim is co-lead of the Reproducibility and Standardisation workgroup of COST Action PARENCHIMA (CA16103) on the development of renal MRI biomarkers. After his initial training as biomedical engineer in medical image processing and biomedical NMR, Pim has worked both in industry (start-up and small business) and in academia. His main interests are functional and quantitative imaging of the brain and kidneys, standardisation of MR imaging, and validation/quality assurance in MRI.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>How can Open Science Contribute to (Clinical) Research in Radiology?</b><br><br>At the moment the use of open source tools and sharing data is not common in radiology practice. Is there a place for open source tools in a radiology department? What are drawbacks or advantages of using open source? How to deal with liabilities and regulations? What are risks and benefits of sharing data? Some examples of use of open source tools in our department will be shown.
</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Open Science in the Context of Companies, Intellectual Property, and Collaborative Research</b><br><br>There is an interesting interplay between open science practices in publicly funded research and intellectual property and patenting in for-profit companies. This especially comes to light when such research institutions and companies collaborate, which is often the case in MRI-related work. For example, both companies and universities could be doing interesting and important work together, but apparent goals might differ: for universities it might be to publish papers and adhere to funding criteria; for companies it might be to secure a patent and monetize the work. Do these approaches necessarily contradict each other? How should they co-exist (if they can)? What should companies be doing, if anything, to improve or interact with open science practices? What should universities and research institutions be doing, if anything, to engage with companies in open science practices. This talk will explore these questions.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="joao"></a>
{% include speaker-card-2020.html
  avatarurl="Joao.jpg"
  profilename="João Periquito" 
  affiliation="Berlin Ultrahigh Field Facility (B.U.F.F.)"
  city="Berlin, Germany" %}
</td>
<td width="500px" align="left" valign="center">
<a name="daniele"></a>
{% include speaker-card-2020.html
  avatarurl="daniele.png"
  profilename="Daniele Marinazzo"
  affiliation="Department of Data Analysis <br>Faculty of Psychology and Educational Sciences <br>Ghent University"
  city="Ghent, Belgium"
  homepage="http://users.ugent.be/~dmarinaz/"
  twitter="https://twitter.com/dan_marinazzo"                                                                                                
  git="https://github.com/danielemarinazzo"
  researchgate="https://www.researchgate.net/profile/Daniele_Marinazzo" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>João is currently finishing his PhD at Berlin Ultrahigh Field Facility (B.U.F.F.), Berlin, Germany. His research is focused on development of new diagnosis techniques for renal MRI. Open source invaded his heart when he realized that he did not need to spend one year implementing an algorithm because someone kind went the extra mile and published a well-documented open-source tool that others can use to their purposes. João is also involved in the project: <a href="https://www.opensourceimaging.org/">Open Source Imaging Initiative</a> (OSI²), a creative community of volunteers with the aim of facilitating medical devices to more people all around the world.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Daniele Marinazzo is an associate professor in the Department of Data Analysis of the Faculty of Psychology and Educational Sciences at Ghent University. His team focuses on methodological and computational aspects of neuroscience research, and on the dynamical networks subserving function, as well as thorough statistical validation of the results. They develop new techniques for inferring connectivity architectures from the dynamics of the recorded data, in challenging cases of short, noisy and redundant time series, as those encountered in neuroimaging. Daniele cares about open science and ways to improve the review/editorial process. He is an editor at several journals in his field, including PLOS Computational Biology, PLOS One, NeuroImage, Brain Topography, Network Neuroscience. Visit Daniele’s <a href="https://publons.com/researcher/663417/daniele-marinazzo">Publons review profile</a> for more.</p>
</div>
</td>
</tr>
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>The Open Source Imaging Initiative</b><br><br>MR technology is one of the most powerful medical tools ever made, yet it is not available in many places around the world. How can we change that? Make the technology cheaper? Would be a good start, but it is not enough! We need sustainable long term solutions. By applying the open-source strategy it is possible to use the immense potential of the research community in a more efficient way by means of collaboration. This will trigger innovation, customization, and cost-efficiency, but will also lead to local/regional production and knowhow transfer into regions that desperately need it. An open source strategy would furthermore diffuse into all important areas of our healthcare system, such as: technological optimization, scientific progress, regulatory harmonization, democratized markets, device safety, global health, education, and many more. Not less than that is our vision of the Open Source Imaging Initiative (OSI²) with our communication platform: <a href="http://www.opensourceimaging.org./">www.opensourceimaging.org</a>. We focus on sharing and not competing, because this is healthier to all of us. In this presentation we will give an update on the workings of OSI², what happened so far and what is about to happen very soon.<br><br><b>Spoiler alert</b>: The world's first open source hardware standard will be released soon and we are preparing the open source documentation of a first open source hardware MRI that makes quite decent images. Our efforts are on a voluntary basis and we are open to all who want to join and who support our vision.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Current and Future Scenarios for Open Scientific Publishing and Reviewing</b><br><br>Communicating our research is a fundamental part of our work as scientists, and a duty towards the society. Typically this communication happens through articles published in scientific journals, after having been reviewed by our peers. We will discuss several aspects of scholarly communication and in particular of scientific publishing and peer review. Some of these aspects are (un-)surprisingly in clear contrast with the idea of science as an open and collaborative public mission. Several solutions and improvements have been proposed and sometimes implemented over the years; on some of them there’s wide consensus, on others there is not. And even when there is consensus to change, the change is slow. We will explore the state of the art and different future perspectives, and discuss our experiences and expectations.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="kirstie"></a>
{% include speaker-card-2020.html
  avatarurl="kirstie_2.png"
  profilename="Kirstie Whitaker"
  affiliation="The Alan Turing Institute"
  city="London, UK"
  homepage="https://kirstiewhitaker.com/"
  twitter="https://twitter.com/kirstie_j"
  git="https://github.com/KirstieJane"
  researchgate="https://www.researchgate.net/profile/Kirstie_Whitaker" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Kirstie Whitaker is a research fellow at the <a href="https://www.turing.ac.uk/">Alan Turing Institute</a> (London, UK) and senior research associate in the Department of Psychiatry at the University of Cambridge. Her work covers a broad range of interests and methods, but the driving principle is to improve the lives of neurodivergent people and people with mental health conditions. Dr Whitaker uses magnetic resonance imaging to study child and adolescent brain development and participatory citizen science to educate non-autistic people about how they can better support autistic friends and colleagues. She is the lead developer of <a href="https://github.com/alan-turing-institute/the-turing-way">The Turing Way</a> an openly developed educational resource to enable more reproducible data science. Kirstie is a passionate advocate for making science “open for all” by promoting equity and inclusion for people from diverse backgrounds, and by changing the academic incentive structure to reward collaborative working. She is the chair of the Turing Institute’s Ethics Advisory Group, a Fulbright scholarship alumna and was a <a href="https://science.mozilla.org/programs/fellowships/fellows">2016/17 Mozilla Fellow for Science</a>. Kirstie was named, with her collaborator Petra Vertes, as a <a href="https://2016globalthinkers.foreignpolicy.com/2016/profile/petra-vertes-and-kirstie-whitaker?3fa4cfa909=">2016 Global Thinker</a> by Foreign Policy magazine. You can find more information at her <a href="https://whitakerlab.github.io/">lab website</a>.</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>The Turing Way: Reproducible, Inclusive, Collaborative Data Science</b><br><br>Reproducible research is necessary to ensure that scientific work can be trusted. By sharing data, analysis code, and the computational environment used to generate the results, researchers can more effectively stand on the shoulders of their peers and colleagues and deliver high quality, trustworthy, and verifiable outputs. This requires skills in data management, library sciences, software development, and continuous integration techniques: skills that are not widely taught or expected of academic researchers. Skills that are unreasonable, in fact, to expect in one individual team member.<br><br>The Turing Way is a handbook to support students, their supervisors, funders, and journal editors in ensuring that reproducible research is "too easy not to do". It includes training material on version control, analysis testing, collaborating in distributed groups, open and transparent communication skills, and effective management of diverse research projects. The Turing Way is openly developed and any and all questions, comments, and recommendations are welcome at our GitHub repository: <a href="https://github.com/alan-turing-institute/the-turing-way">https://github.com/alan-turing-institute/the-turing-way</a>.<br><br>In this talk, Kirstie Whitaker, lead developer of The Turing Way, will take you on a whirlwind tour of the chapters that already exist, the interactive demonstrations you can use and re-use for your own research, and the directions in which we're continuing to develop. All participants will leave the talk knowing that "Every Little Helps" when making their work reproducible, where to ask for help as they start or continue their open research journey, and how they can contribute to improve The Turing Way for future readers.</p>
</div>
</td>
</tr>
</table>
</div>

<img class="img-separator" src="{{ site.baseurl }}/assets/ext_images/2020/post_separator.png" alt="horizontal separator" />
<br>
<a href="#"><i class="fas fa-arrow-alt-circle-up" style="position: relative; top: -3px; text-indent: 0px; vertical-align: middle; color:#004777;"></i></a>

<h2 style="color:#004777"> Wednesday, 22 January 2020 </h2>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="fatma"></a>
{% include speaker-card-2020.html
  avatarurl="FatmaDeniz.jpg"
  profilename="Fatma Deniz" 
  affiliation="Postdoctoral Fellow, University of California, Berkeley; Visiting Scientist, Technical University Berlin, Germany"
  city="Berkeley, USA" %}
</td>
<td width="500px" align="left" valign="center">
<a name="remi"></a>
{% include speaker-card-2020.html
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
  <p align="justify" style="font-family: arial;"><br>Fatma Deniz is currently a Visiting Scientist at TU Berlin and a PostDoc at the Gallant Lab in UC Berkeley. Prior to her current position, Fatma was a Moore-Sloan Data Science Fellow at Berkeley Institute for Data Science and a fellow at the International Computer Science Institute in Berkeley. She is interested in how linguistic information is encoded in the brain and uses machine-learning approaches to fit computational models to large-scale brain data. Her current work focuses on cross-modal language representation in the human brain. She did her PhD at Bernstein Center for Computational Neuroscience in Berlin, where she studied functional connectivity changes during conscious perception in humans and got a bachelor’s and master’s degrees in Computer Science from the Technical University Munich. During her master’s work, Dr. Deniz worked with Dr. Christof Koch at Caltech, where she studied visual saliency and automated text detection. As an advocate of reproducible research practices, she is the editor of the book titled “The Practice of Reproducible Research”. In addition, she works on improving Internet security applications using the knowledge gained from cognitive neuroscience and Mooney images (<a href="https://mooneyauth.org/static/index.php">mooneyauth.org</a>). Her work is at the intersection between computer science, human cognition, and neuroscience. She is a passionate coder, baker, and loves to play the cello.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Remi is a postdoctoral fellow in the Crossmodal Perception and Plasticity laboratory (<a href="https://cpplab.be" >CPP-Lab</a>) at the Université catholique de Louvain. His work focuses on the multisensory aspects of perception and he uses high-resolution MRI to address these questions. He sees in open science a way to a) build a more inclusive research community based on cooperation rather than competition and b) addresses some of the replicability and reproducibility issues that are affecting many areas of science.</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Reproducibility in Decoded: Case Studies from Data-Intensive Sciences</b><br><br>Reproducibility in research is one of the main building blocks of the scientific method. However, there is rising concern about reproducibility in current scientific research that reduces the reliability of published findings in various domains. In this workshop, we will learn about the tools and practices that will help us to improve the reproducibility of our own research pipeline. Based on the book <a href="https://www.practicereproducibleresearch.org/">The Practice of Reproducible research</a>, I will first introduce reproducible research workflows by providing case-study examples. In the second part, participants will walk through their own research pipeline and create their own reproducible research workflow. In small working groups, participants will reflect on their own computational practices and learn how they can improve the reproducibility of their own research workflow.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Software Version Control with git and GitHub</b><br><br>GIT is a tool to keep track of the successive versions of your code: from different pilot experiments to the final version or for different stages of your analysis pipeline. A side effect of using GIT is that it can also improve how you organize your code. When associated with GitHub, this also facilitates collaboration with others on the same codebase, automation of many tasks, and can help you streamline your workflow.
GIT and GitHub are potentially very powerful tools but tend to have a steep learning curve associated with a confusing and obscure terminology. This 2 hours workshop will not turn you into GIT and GitHub wizards but it should 1) make the terminology less scary so that you won’t be as confused when you try it on your own, 2) guide you on how to version control some simple code, 3) guide you on how to use some of GitHub’s functions by quikly creating your own academic website (e.g. <a href="https://academicpages.github.io/">https://academicpages.github.io/</a>).</p>
<p align="justify" style="font-family: arial;">Things to do before to prepare for this workshop:</p>
<ol>
<li><div align="justify" style="font-family: arial;">Download the file editor <a href="https://atom.io/">Atom</a>.</div></li>
<li><div align="justify" style="font-family: arial;">Create a GitHub account: <a href="https://github.com">https://github.com</a>.</div></li>
<li><div align="justify" style="font-family: arial;">Download gitkraken to interact with git/GitHub: <a href="https://www.gitkraken.com/">https://www.gitkraken.com/</a>.</div></li>
</ol>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="sofie"></a>
{% include speaker-card-2020.html
  avatarurl="sofie.png"
  profilename="Sofie Van Den Bossche"
  affiliation="Department of Data Analysis <br> Faculty of Psychology and Educational Sciences <br> Ghent University"
  city="Ghent, Belgium"
  git="https://github.com/sofievdbos"
  twitter="https://www.twitter.com/sofie_vdbos"
  researchgate="https://www.researchgate.net/profile/Sofie_Van_Den_Bossche2" %}
</td>
  <td width="500px" align="left" valign="center">
<a name="serena"></a>
{% include speaker-card-2020.html
  avatarurl="serena.png"
  profilename="Serena Bonaretti"
  affiliation="Transparent MSK Research"
  homepage="https://sbonaretti.github.io/"
  git="https://github.com/sbonaretti"
  twitter="https://www.twitter.com/SerenaBonaretti" %}
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
  <p align="justify" style="font-family: arial;"><br>Serena Bonaretti is founder and research scientist at <a href="https://sbonaretti.github.io/transparentMSKresearch.html">Transparent MSK Research</a>. Previously, she was research scientist and postdoctoral fellow at the Departments of Radiology at Stanford University and University of California, San Francisco. She holds a PhD in Biomedical Engineering from the University of Bern, Switzerland. Her background is image acquisition, image processing, and biomechanics to investigate aging diseases of the musculoskeletal system. She has recently released <a href="https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsbonaretti.github.io%2FpyKNEEr%2F&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142714487&sdata=kWnO3g%2F3wM%2F0vQJmjgETe6wJVf%2Fxi2BxmkSS4%2F4f2Sk%3D&reserved=0">pyKNEEr</a>, an image analysis workflow for open and reproducible research on femoral knee cartilage. Previously, she developed <a href="https://eur01.safelinks.protection.outlook.com/?url=http%3A%2F%2Fwebapps.radiology.ucsf.edu%2Frefline%2F&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142724500&sdata=kjT0exJ6lnMijM1Gd8CnYyUV7nKUy15PYM%2F6Hn0RINo%3D&reserved=0">Reference line</a>, a web application to train and evaluate HR-pQCT operators. As a member of the quantitative musculoskeletal imaging (QMSKI) working group for transparent research, she is creating hands-on <a href="https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2FQMSKI%2FTransparentQMSKI%2Fwiki&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142734504&sdata=vCR7GAdJJOzI4JoiJSvH66D%2BO2iQDyP18pPaLFh5%2FcI%3D&reserved=0">guidelines</a> on how to conduct open and reproducible research.</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Software Version Control with git and GitHub</b><br><br>GIT is a tool to keep track of the successive versions of your code: from different pilot experiments to the final version or for different stages of your analysis pipeline. A side effect of using GIT is that it can also improve how you organize your code. When associated with GitHub, this also facilitates collaboration with others on the same codebase, automation of many tasks, and can help you streamline your workflow.
GIT and GitHub are potentially very powerful tools but tend to have a steep learning curve associated with a confusing and obscure terminology. This 2 hours workshop will not turn you into GIT and GitHub wizards but it should 1) make the terminology less scary so that you won’t be as confused when you try it on your own, 2) guide you on how to version control some simple code, 3) guide you on how to use some of GitHub’s functions by quikly creating your own academic website (e.g. <a href="https://academicpages.github.io/">https://academicpages.github.io/</a>).</p>
<p align="justify" style="font-family: arial;">Things to do before to prepare for this workshop:</p>
<ol>
<li><div align="justify" style="font-family: arial;">Download the file editor <a href="https://atom.io/">Atom</a>.</div></li>
<li><div align="justify" style="font-family: arial;">Create a GitHub account: <a href="https://github.com">https://github.com</a>.</div></li>
<li><div align="justify" style="font-family: arial;">Download gitkraken to interact with git/GitHub: <a href="https://www.gitkraken.com/">https://www.gitkraken.com/</a>.</div></li>
</ol> 
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>The Basics of Python and Jupyter Notebooks for Medical Image Analysis</b><br><br>Python and Jupyter notebooks are becoming more and more essential tools to conduct open and reproducible research. In this workshop, we will first briefly discuss how these tools can facilitate transparent science. Then, we will have a hands-on session where we will code in Jupyter notebook using Python. We will create reproducible workflows using packages that are both basic and specific for medical image analysis (e.g. SimpleITK). Information and materials are available at <a href="https://github.com/sbonaretti/2020_OpenMR_jupyter">https://github.com/sbonaretti/2020_OpenMR_jupyter</a>.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="lukas"></a>
{% include speaker-card-2020.html
  avatarurl="Lukas_Snoek.png"
  profilename="Lukas Snoek"
  affiliation="Department of psychology <br> University of Amsterdam"
  city="Amsterdam, The Netherlands"
  git="https://github.com/lukassnoek"
  twitter="https://www.twitter.com/LukasSnoek"
  homepage="https://lukas-snoek.com" %}
</td>
<td width="500px" align="left" valign="center">
<a name="agah"></a>
{% include speaker-card-2020.html
  avatarurl="karakuzu.jpeg"
  profilename="Agah Karakuzu" 
  affiliation="NeuroPoly Lab Ecole Polytechnique de Montréal"
  city="Montréal, Canada"
  git="https://github.com/agahkarakuzu/"
  twitter="https://www.twitter.com/agahkarakuzu"
  researchgate="https://www.researchgate.net/profile/Agah_Karakuzu"  %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>I am a PhD student at the Psychology Department of the University of Amsterdam, supervised by Dr. Steven Scholte and Dr. Suzanne Oosterwijk. I’m interested in the neural representation of affective processes such as emotion experience and (facial) emotion perception. Additionally, I’m a methods nerd, interested in novel analyses and statistical methods (for fMRI). Next to my research, I work at the Spinoza Centre for Neuroimaging (UvA), where I provide technical assistance and develop software for automated data management and preprocessing (using Docker!). Throughout the years, I developed a passion for open and transparent (neuro)science, to which I aim to contribute with various open-source projects aimed at improving transparency and reproducibility. </p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Agah is a PhD student at NeuroPoly Lab (Biomedical Engineering, Polytechnique Montreal, Montreal, Canada), supervised by Dr. Nikola Stikov. His research focuses on <a href="https://qmrlab.org">bringing quantitative MRI (qMRI) applications under one umbrella</a> <a href="https://github.com/bids-standard/bep001">through data standardization</a>, <a href="https://github.com/qMRLab/pulse_sequences">vendor-neutral acquisitions</a>, <a href="https://github.com/qMRLab/qMRFlow">fully transparent & reproducible workflows</a> and <a href="https://qmrlab.org/blog.html">community building</a>. He plays an active role in organizing of Open Science events (<a href="https://mrathon.github.io/">MRathon</a>, <a href="https://brainhackmtl.github.io/school2019/index.html">Brain Hack School</a>) and as a science communication contributor on various platforms (<a href="https://blog.ismrm.org/category/highlights/">MRM Highlights</a>, <a href="https://blog.ismrm.org/">MR Pulse</a> and <a href="https://www.ohbmbrainmappingblog.com/">OHBM Blog</a>).</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Introduction to Docker and Binder</b><br><br>With the 'reproducibility crisis' in psychology and neuroscience, there is a trend towards publishing one’s data and code along with the associated article — which is great! Often, however, providing your code is not enough to reproduce your analyses, as it may depend on specific software versions, system requirements, or even operating systems. Docker and Binder are two tools that offer a solution for this! Docker allows you to specify an environment (a Docker container) using a 'recipe' (a Dockerfile), containing the particular (Linux-based) operating system (e.g., Ubuntu 18.04), software packages (FSL 6.0.1 and Python 3.6.1 with scikit-learn 0.21.3), and runtime executables (entrypoint, e.g., my_analysis.py) of your choice. Binder is a less 'complete' solution than Docker, but definitely not less useful! With Binder, you can turn your Git(hub) repository into a collection of interactive Jupyter notebooks, making them instantly reproducibly for anyone. In this workshop, you will get some hands-on experience with writing Dockerfiles and creating Docker containers in a scientific context, as well as getting started with Binder. Some experience with the (Linux) command line interface is useful, but not strictly required.</p>
</div>
</td>
  <td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Introduction to Docker and Binder</b><br><br>The arrival of Docker containers has revolutionized the way software is developed, tested and pushed to production. Billions of containers are spawn on a weekly basis to deliver some of the most frequently used web services. We unknowingly benefit from this technology doing a web search on <a href="https://github.com/google/gvisor">Google</a> at work, on an <a href="https://github.com/uber/makisu">Uber</a> ride back home and watching our favorite TV shows on <a href="https://github.com/Netflix/conductor">Netflix</a> (ps. all hyperlinks direct to GitHub).  But, how do we foster the use of containers to boost reproducibility and efficiency in the scientific realm? Following a hands-on Introduction to Docker and Binder, we will briefly explore some example use cases of container technology in creating reproducible computational workflows and mapping them onto supercomputers!</p>
</div>
</td>
</tr>

</table>

</div>

<img class="img-separator" src="{{ site.baseurl }}/assets/ext_images/2020/post_separator.png" alt="horizontal separator" />
<br>
<a href="#"><i class="fas fa-arrow-alt-circle-up" style="position: relative; top: -3px; text-indent: 0px; vertical-align: middle; color:#004777;"></i></a>

<h2 style="color:#004777"> Thursday, 23 January 2020 </h2>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="malvika"></a>
{% include speaker-card-2020.html
  avatarurl="Malvika.png"
  affiliation="European Molecular Biology Laboratory (EMBL) Heidelberg"
  city="Heidelberg, Germany"
  profilename="Malvika Sharan" %}
</td>
<td width="500px" align="left" valign="center">
<a name="natalia"></a>
{% include speaker-card-2020.html
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
  <p align="justify" style="font-family: arial;"><br>Malvika is a computational biologist at the European Molecular Biology Laboratory, Heidelberg, Germany, where she coordinates the Bio-IT project, a community-driven platform for bioinformaticians. She organizes training activities and events for EMBL, de.NBI/ELIXIR Germany and other open source communities such as The Carpentries. She promotes Open Science and inclusiveness through her work as a community outreach coordinator.</p>
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
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Fostering Open and Inclusive Communities</b><br><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Where to Go Next? The Landscape of Post-PhD Career Tracks</b><br><br>There is a growing disparity between the number of new PhD graduates and the available faculty positions. Effectively, most of the PhD graduates needs to find jobs outside academia. Yet, there is little amount of services dedicated to assisting early career researchers in discovering their core competencies, in searching for employers and landing their dream jobs in industry. Ideally, one should anticipate the potential future market sectors after completing the PhD, and focus on developing transferable skills during the PhD on that basis. This however, remains a rare practice in the graduate schools. Therefore, in this workshop, we will assume that you have no prior experience with the job market in industry. We will discuss the following: the demand for PhDs in different branches of industry; paycheck or entrepreneurship? Is a traineeship at a company a good start after a PhD?; defining your key competences, including both hard- and soft skills; searching for employers who are likely to search for these competences; searching for employers who share your personal values; the role of networking in searching for jobs; restructuring your CV and writing a competitive motivational letter; preparing for job interviews.<br><br>The workshop will be interactive: we will debunk certain myths related to the job market with the use of polls and quizzes. Sharing personal experience by participants will be highly encouraged. The goal of the workshop is to give the participants the information and confidence so they can further search for relevant information on their own, and take their first steps towards finding their dream job in industry.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="sarah"></a>
{% include speaker-card-2020.html
  avatarurl="sarah.png"
  profilename="Sarah Genon"
  affiliation="Cognitive Neuroinformatics, Institute of Neuroscience and Medicine,
Brain & Behaviour"
  city="Jülich, Germany"
  homepage="https://www.fz-juelich.de/SharedDocs/Personen/INM/INM-7/EN/genon_s.html?nn=654218"
  researchgate="https://www.researchgate.net/profile/Sarah_Genon" %}
</td>
<td width="500px" align="left" valign="center">
<a name="lyuba"></a>
{% include speaker-card-2020.html
  avatarurl="zehl.png"
  profilename="Lyuba Zehl"
  affiliation="Jülich Research Centre, Institute of Neuroscience and Medicine (INM-1), Jülich, Germany"
  city="Jülich, Germany"
  git="https://github.com/lzehl"
  twitter="https://twitter.com/LyubaZehl"
  researchgate="https://www.researchgate.net/profile/Lyuba_Zehl" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Sarah Genon is a research group leader of the working group “Cognitive Neuroinformatics”, which is part of the Institute of Neuroscience and Medicine, Brain & Behaviour (INM-7), located in the Jülich Research Centre (Germany).</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Lyuba Zehl studied Biology and Neuroscience at the University of Cologne. During this time of study, she worked on kinematic of insect legs during locomotion (BSc thesis, supervisor: Prof. Ansgar Büschges), and the anatomical cartography of auditory nuclei in the brain stem of toothed whales using cluster analysis (Msc thesis, supervisor: Prof. Wolfgang Walkowiak). For her doctoral studies, she switched to the RWTH Aachen University and joined the Statistical Neuroscience Group of Prof. Sonja Grün at the Institute for Neuroscience and Medicine (INM-6) of the Jülich Research Centre. In her thesis, she worked on analysing multi-electrode array recordings of monkey motor cortex and, in particular, on data and metadata management of complex neuroscience experiments. After receiving her doctorate degree (Dr. rer. nat.) in 2017, she started working as a junior scientist in the curation team of the Neuroinformatics Platform of the Human Brain Project (HBP), located at the Jülich Research Centre as part of the Big Data Analytics Group from Timo Dickscheid at the Institute for Structural and Functional Organisation of the Brain (INM-1) led by Prof. Katrin Amunts. Having a high interdisciplinary orientation towards computational neuroscience and software development for data and metadata management and a broad experience in various neuroscience laboratories, she focuses now on developing and implementing concepts, standards and tools for neuroscience data and metadata management. With her current work, she strongly supports the integration of heterogeneous neuroscience data into the unified data sharing platform and the interactive atlas viewers of the HBP. </p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Probing Brain Organization and Function with Neuroimaging Markers of Connectivity (HBP)</b><br><br>Across the past years, many developments arose in connectivity analyses based on MRI data offering now a wide range of connectivity markers. Capitalizing on this wealth of neuroimaging markers, connectivity-based parcellation can be used to unravel the complexity of brain organization. Furthermore, large population-based neuroimaging datasets with extensive psychometric characterization now open promising perspectives to link brain organization to behavior. In particular, interindividual variability in brain’s region functional connectivity can be related to interindividual variability in psychometric data by using a connectivity-based psychometric prediction approach. Despite some challenges associated to the use of these data-driven approaches, they also offer opportunities to better understand the relationships between brain connectivity and human behavior.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>The HBP Human Brain Atlas</b><br><br>The Human Brain Project (HBP) provides access to a comprehensive, multi-level Human Brain Atlas which includes different brain parcellations and template spaces. In particular, it integrates the 20 micron BigBrain model with 3D maps of cytoarchitectonic areas and cortical layers at microscopic detail, with the JuBrain probabilistic cytoarchitectonic atlas which covers variability across 10+ postmortem brains, as well as with a probabilistic fibre bundle atlas derived from in-vivo neuroimaging studies. HBP’s brain atlases are exposed through a set of web-based services that allow users to discover, explore and access not only the reference atlases themselves, but also a range of well curated human brain data at different scales and modalities that were linked to atlas regions in a well structured data integration process. The most intuitive interface to these atlas services is a freely accessible, web-based interactive atlas viewer, which allows intuitive visual navigation of brain anatomy and atlas regions in 3D, down to the microscopic resolution.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="stephanklein"></a>
{% include speaker-card-2020.html
  avatarurl="stefan.jpg"
  profilename="Stefan Klein" 
  affiliation="Biomedical Imaging Group Rotterdam - Eramus Medical Center"
  city="Rotterdam, The Netherlands"
  homepage="http://bigr.nl/people/StefanKlein/" %}
</td>
<td width="500px" align="left" valign="center">
<a name="marcel"></a>
{% include speaker-card-2020.html
  avatarurl="Marcel.png"
  affiliation="Donders Institute for Brain, Cognition and Behaviour"
  city="Nijmegen, The Netherlands"
  profilename="Marcel Zwiers" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>In 2002, Stefan received his MSc degree at the University of Twente, Enschede, the Netherlands, at the faculty of mechanical engineering. His MSc-project was on the segmentation of fingerprint images, using Hidden Markov Models. From 2003-2008, he worked as a PhD student on the subject of medical image registration at the Image Sciences Institute, UMC Utrecht, the Netherlands, resulting in a thesis about “Optimisation methods for medical image registration”. An important result was the development (with Marius Staring) of the open-source software package for image registration, <a href="http://elastix.isi.uu.nl">Elastix</a>. Currently in use by several (national and international) research institutions and companies. Since 2008, he works at the Biomedical Imaging Group Rotterdam (<a href="http://www.bigr.nl">BIGR</a>), Erasmus MC, Rotterdam, the Netherlands. There, he is assistant-professor and leading a research line on medical image registration.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Marcel is a physicist and has a PhD in auditory neuroscience. His main research interest is in MR physics and MR image analysis, particularly in the field of diffusion imaging, brain connectivity and morphometry, and in the application of these techniques to clinical samples. He has extensive experience with analyzing large datasets and merging data from multi-center studies.</p>
</div>
</td>
</tr>                                                                                                                                  
<tr> 
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>MR Image Registration with Elastix and Simple Elastix</b><br><br>From multi-modality superpositioning to atlas alignment, image registration plays a central role in medical image analysis. In this talk/workshop, Stefan will give us insights on how Elastix and Simple Elastix work, applicable modalities and how to profit the most from this amazing tool. During the workshop, a hands-on guided practical session will demonstrate how versatile Elastix is, even in novel fields, such as quantitative MRI. </p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Converting Neuroimaging Data to BIDS</b><br><br>TBA</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="robert"></a>
{% include speaker-card-2020.html
  avatarurl="Robert.png"
  affiliation="Donders Institute for Brain, Cognition and Behaviour"
  city="Nijmegen, The Netherlands"
  homepage="https://robertoostenveld.nl/research/"
  profilename="Robert Oostenveld" %}
</td>
<td width="500px" align="left" valign="center">
<a name="tim"></a>
{% include speaker-card-2020.html
  avatarurl="tim.png"
  profilename="Tim van Mourik"
  affiliation="Donders Institute for Brain, Cognition and Behaviour"
  homepage="https://timvanmourik.com/"
  city="Nijmegen, The Netherlands"
  twitter="https://twitter.com/tim_van_mourik?lang=nl"                                  
  git="https://github.com/TimVanMourik"
  researchgate="https://www.researchgate.net/profile/Tim_Van_Mourik" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Robert's main interest is in developing novel methods for the analysis of MEG and EEG data with applications in cognitive neuroimaging. His scientific contributions include signal processing, source reconstruction, connectivity analysis and statistical analysis. Furthermore, Robert is interested in improving the methodological aspects of cognitive neuroimaging at the meta level: he contributes to the dissemination of state-of-the-art analysis methods by developing open-source software, by data sharing and by organizing educational and scientific workshops. His contributions to the methodological advancement of the field of non-invasive electrophysiology are exemplified by FieldTrip, a project that he started about 10 years ago and that he has been heading since. To strengthen the MEG and EEG research community, Robert is not managing FieldTrip only as a data analysis toolbox, but also as a platform for the exchange of ideas and expertise.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Tim van Mourik is a PostDoc at the Donders Centre for Cognitive Neuroimaging. During his PhD he developed analysis tools to analyse fMRI scans at an even finer level of detail: that of the cortical layers. In doing so, he not only developed the new tools for obtaining laminar signals, but also applications to build graphical pipelines with these tools (<a href="https://timvanmourik.github.io/Porcupine/">Porcupine</a>). In addition, he set up web applications to facilitate sharing fMRI results in augmented reality (<a href="https://armadillo-brain.herokuapp.com">ARmadillo</a>) and improved collaboration on interactive workflows (<a href="https://giraffe.tools">GiraffeTools</a>). At the OHBM conference 2019, Tim was the chair of the Open Science Room and in charge of organising a week long program with talks, discussions, and demos towards open and reproducible research practices.</p>
</div>
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Converting Neuroimaging Data to BIDS</b><br><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Web Technologies in Neuroimaging</b><br><br>How do we share and communicate our analysis pathways? By means of a text-description in a paper, or are there other ways? In this day and age where everything happens online, it should be possible to leverage web technologies for neuroimaging. Indeed, there is a growing number of web tools to share and communicate project information, data sets, and entire interactive workflows online. In this talk I will discuss a variety of these projects, how to get started or even involved in them, and what I believe is the future of data analysis and neuroimaging.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="tony"></a>
{% include speaker-card-2020.html
  avatarurl="tony.png"
  profilename="Tony Stöcker" 
  git=" https://github.com/JEMRIS/jemris"
  affiliation="MR physics group German Center for Neurodegenerative Diseases"
  city="Bonn, Germany"
  homepage="http://www.dzne.de/en/sites/bonn/research-groups/stoecker.html"
  researchgate="https://www.researchgate.net/profile/Tony_Stoecker" %}
</td>
<td width="500px" align="left" valign="center">
<a name="oliver"></a>
{% include speaker-card-2020.html
  avatarurl="oli.jpg"
  profilename="Oliver Schmid"
  affiliation="EPFL (École politechnique fédérale de Lausanne), Switzerland"
  city = "Lausanne, Switzerland" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Tony Stöcker has been Professor of Medical Physics at Bonn University since 2014 and Head of MR Physics Research Group (DZNE-Bonn) since 2012. 
His research focus is MRI sequence development at 7 Tesla, probing for neurodegeneration with high sensitivity and resolution, and the development of high-throughput and high-quality neuroimaging protocols for large-scale patient and population studies. Together with his group, he investigates novel medical imaging methods for biomarkers of neurodegenerative diseases.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Oliver Schmid is the Product Owner of the EBRAINS Knowledge Graph developed by EPFL for the Human Brain Project. Oliver has worked as a Software Engineer and Software Architect in different companies for many years and has studied Computer Science (PhD), Information Management (MA) and Educational Sciences (BSc) at the University of Fribourg, Switzerland. His main interest is to improve existing processes by the application of interdisciplinary knowledge - accordingly, he contributes to the creation of a (neuro-)scientific IT infrastructure for data sharing and Open Science in his current position.</p>
</div>
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Numerical Simulation of MR Physics</b><br><br>MR simulations based on the Bloch Equations are of high educational value. Further, they serve as essential tools in MRI method development, e.g. for MR sequence design and protocol optimization or generating ground truth data for image reconstruction and post-processing algorithms. This lecture provides insight into practical implementation of computer simulations based on classical MR physics. Analytical solutions versus numerical implementations will be discussed. Based on pictorial examples, an introduction to various MRI simulator software packages will be given. The JEMRIS simulation environment will serve for most of the examples shown in this lecture.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Find, Use and Share Scientific Data with the EBRAINS Knowledge Graph (HBP)</b><br><br>The EBRAINS Knowledge Graph (KG) has been built to easily find, use and share neuroscientific data originating from the Human Brain Project as well as other data providers. In this talk / demo, we present the various tools built to simplify and standardize the annotation of data, to find published and citable data sets and to use the available resources in automated and semi-automated scientific workflows.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="stephan"></a>
{% include speaker-card-2020.html
  avatarurl="stephan.png"
  profilename="Stephan Heunis"
  affiliation="Eindhoven University of Technology"
  city="Eindhoven, The Netherlands"
  homepage="https://www.fmrwhy.com/"
  git="https://github.com/jsheunis/"
  twitter="https://www.twitter.com/fmrwhy"
  researchgate="https://www.researchgate.net/profile/Stephan_Heunis2" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Stephan is a researcher and PhD candidate at the Electrical Engineering Department of the Eindhoven University of Technology in the Netherlands. His research focuses on developing new acquisition and signal processing methods for functional neuroimaging that allow the real-time tracking and visualisation of distributed MRI brain activity patterns. Stephan is passionate about making research and scientific practice more transparent, rigorous, and inclusive. He started the <a href="https://osceindhoven.github.io/">Open Science Community Eindhoven</a>, which is part of a wide Dutch network of researchers and university employees that focuses on improving scientific practice. He is also the founder of <a href="https://openmrbenelux.github.io/">OpenMR Benelux</a>, a community working on wider adoption of open science principles in MRI research through talks, discussions, workshops, and hackathons.</p>
</div>
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-comment" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br><b>Sharing GDPR Compliant Neuroimaging Research Data</b><br><br>Personal data privacy and research data sharing seem, on the surface, to be at odds. On the one hand the European General Data Protection Regulation provides important regulations for protecting personal information to a high standard, something that we should uphold in multiple facets of life. On the other hand, current principles of transparency and reproducibility in research (in short, open science) suggests that we should publicly share the data underlying our scientific findings. This leaves us with a conundrum: how do we protect the individual's privacy, while allowing others to access and process their data? In this talk I will provide an overview of what has been done at several EU institutions to enable neuroimaging data sharing under GDPR. We will also look at the progress made with a collaborative and open project that aims to provide open templates and resources for informed consent forms, data anonymization techniques, data usage agreements, and more.</p>
</div>
</td>
</tr>

</table>

</div>

<img class="img-separator" src="{{ site.baseurl }}/assets/ext_images/2020/post_separator.png" alt="horizontal separator" />
<br>
<a href="#"><i class="fas fa-arrow-alt-circle-up" style="position: relative; top: -3px; text-indent: 0px; vertical-align: middle; color:#004777;"></i></a>

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
