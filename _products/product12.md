---
title: Lukas Snoek & Agah Karakuzu
subtitle: Introduction to Docker and Binder
slides: https://zenodo.org/record/3625531#.Xild8lNKho4
layout: product
---

[Introduction to Docker](https://zenodo.org/record/3625531#.Xild8lNKho4)

With the 'reproducibility crisis' in psychology and neuroscience, there is a trend towards publishing one’s data and code along with the associated article — which is great! Often, however, providing your code is not enough to reproduce your analyses, as it may depend on specific software versions, system requirements, or even operating systems. Docker and Binder are two tools that offer a solution for this! Docker allows you to specify an environment (a Docker container) using a 'recipe' (a Dockerfile), containing the particular (Linux-based) operating system (e.g., Ubuntu 18.04), software packages (FSL 6.0.1 and Python 3.6.1 with scikit-learn 0.21.3), and runtime executables (entrypoint, e.g., my_analysis.py) of your choice. Binder is a less 'complete' solution than Docker, but definitely not less useful! With Binder, you can turn your Git(hub) repository into a collection of interactive Jupyter Notebooks, making them instantly reproducibly for anyone. In this workshop, you will get some hands-on experience with writing Dockerfiles and creating Docker containers in a scientific context, as well as getting started with Binder. Some experience with the (Linux) command line interface is useful, but not strictly required.

[Introduction to Binder](http://lukas-snoek.com/docker-and-binder-workshop/)

The arrival of Docker containers has revolutionized the way software is developed, tested and pushed to production. Billions of containers are spawn on a weekly basis to deliver some of the most frequently used web services. We unknowingly benefit from this technology doing a web search on <a href="https://github.com/google/gvisor">Google</a> at work, on an <a href="https://github.com/uber/makisu">Uber</a> ride back home and watching our favorite TV shows on <a href="https://github.com/Netflix/conductor">Netflix</a> (ps. all hyperlinks direct to GitHub). But, how do we foster the use of containers to boost reproducibility and efficiency in the scientific realm? Following a hands-on Introduction to Docker and Binder, we will briefly explore some example use cases of container technology in creating reproducible computational workflows and mapping them onto supercomputers!
