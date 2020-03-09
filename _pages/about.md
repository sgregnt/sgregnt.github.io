---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I'm studying towards a PhD degree at [the University of Chicago](https://www.uchicago.edu/), in the department of [Statistics](https://galton.uchicago.edu/). My research is conducted under the supervision of [Prof. Lek-Heng Lim.](https://www.stat.uchicago.edu/~lekheng/)

I'm interested in applying non-standard tools form abstract algebra and topology to the study of neural networks. 


### Announcements and latest whereabouts
- I gave a talk at ICIAM 2019 Minisymposium on Deep Learning that took place in [Valencia](https://en.wikipedia.org/wiki/Valencia), organized by [Tingran Gao](https://gaotingran.com/) and [Haizhao Yang](http://www.math.nus.edu.sg/~matyh/). 
- I've oraganized [2019 SIAM minisymposium on application of tropical
geometry for machine learning](http://wiki.siam.org/siag-ag/index.php/SIAM_AG_19_Proposed_Minisymposia) (with focus on deep neural networks) [(SIAM AG19)](https://www.siam.org/Conferences/CM/Main/ag19), Bern, Switzerland. 
- Last December I have participated in a course on finite elements modeling using [FEniCS](https://fenicsproject.org/) in Paris organized by [Prof. L.R. Scott](http://people.cs.uchicago.edu/~ridg/). 
- I gave a talk at [applied algebra day at MIT](http://math.mit.edu/~erobeva/seminar.html) on tropical geometry of deep neural networks. 
- I've participated in [Oberwolfach Seminar: Mathematics of Deep Learning](https://www.mfo.de/occasion/1842b/www_view), that took place in Oct 14-20 2018, in [Oberwolfach, Germany](https://en.wikipedia.org/wiki/Oberwolfach). 
- During the summer of 2018  I've spent wonderful time working as a PhD machine learning intern in Blink startup (Haifa, Israel) working with TensorFlow and Caffe.  


## Most recent research projects

* Topology of Deep Neural Networks. 
A key insight of topological data analysis is that “data has shape”.
We study how modern deep neural networks transform shape of data sets, 
with the goal of shedding light on their breathtaking yet somewhat mysterious effectiveness.
Most existing approaches tend to focus on what a network does to a single object, e.g. an image of a cat; but we are interested in what it does to all objects in the same class, e.g. the set of all cats. As in topological data analysis, we
employ persistent homology — a computational topology tool with proven stability, robust algorithms,
and high-quality software — to track changes in the topology of a data set as it passes through the
layers of neural network.
![TopologyChange2](https://sgregnt.github.io/images/all2.png "Topology Change")


* [Tropical algebra and tropical geometry](https://en.wikipedia.org/wiki/Tropical_geometry) of deep neural network.   
In this study, presented at ICML2018 conference in Stockholm, we've establish connections
between feedforward neural networks with ReLU activation and tropical
geometry. We've shown that the family of such neural networks is equivalent
to the family of tropical rational maps. This novel connection between two previously distinct areas of research allowed us to use machinery of tropical algebraic geometry for the study of neural networks. 

![Polytopes](https://sgregnt.github.io/images/tropical.png "Polytopes")


* Topological data analysis to boost performance of neural networks. 
[Topological data analysis (TDA)](https://en.wikipedia.org/wiki/Topological_data_analysis) is a relatively
new area of research which has rapidly developed in the past decade. 
TDA uses ideas from topology for data analysis. In the past
I've considered TDA in a setting where point cloud data is
contaminated by noise and proved a theoretical convergence results for
the Euler Integral, which is one of the tools in TDA ([Justin Curry Et al.](https://www.math.upenn.edu/~ghrist/preprints/eulertome.pdf)). In this project I use another tool from TDA, a mapper algorithm, [(G Singh Et al., 2007)](https://research.math.osu.edu/tgda/mapperPBG.pdf) for profiling of neural networks 
and boosting their performance. The proposed algorithm provides topological
summary for the input data shape, this summary is used to measure local 
performance of neural network in the input, which in turn guides an ensemble 
scheme that improves neural network performance.

![Topological Data summary](https://sgregnt.github.io/images/tda.png "Topological Data summary")


## Past research interests and professional experience

- In the past I worked in logic design and hardware engineering:
    - I did a research project at the [Technion](https://www.technion.ac.il/en/home-2/) where we designed [a near real time logic circuit for RSA encryption](https://ieeexplore.ieee.org/abstract/document/5386066). 
    - For the period between 2006-2015 I worked as a board designer, FPGA engineer and FPGA development team leader. 

## Honors & Awards

* 2018 Invited to participate in [Oberwolfach Seminar: Mathematics of Deep Learning](). The Institute will cover the expenses for accommodation and meals. and reimburse travel expenses.
* 2018 ICML conference, I have been selected for a travel award covering travel and acommodation expenses.
* 2017 SAS institute prize for patent initiative 2017.
* 2015-2017: McCormick Fellowship. 
* 2004-2008: Technion President Excellence Award. Received 2 times.
* 2004-2008: [__"Psagot"__(Hebrew)](https://he.wikipedia.org/wiki/%D7%AA%D7%95%D7%9B%D7%A0%D7%99%D7%AA_%D7%A4%D7%A1%D7%92%D7%95%D7%AA) excellence program.



## Publications and workshops

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks and posters

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
## Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Service and leadership

* 2019 - One of the organizers of ["RTG Summer Lectures"](https://www.stat.uchicago.edu/events/rtg/) at The University of Chicago
* 2018 - Leading team of PhD and master students to helps the law school at the university of Chicago analyze gender dynamics and gender achievement disparities at the school. The report can be found [here.](https://www.law.uchicago.edu/files/2018-05/wap_final.pdf) 
* 2017 - Leading a team of PhD and master students to help reserchers in biology department analyze spatial patterns of migrating cells in zebrafish embryos (analysis of cell movement within embryo).
* Peer review for ["Artificial Intelligence Review"](https://link.springer.com/journal/10462)
* Peer review for ["Linear Algebra and its Applications"](https://www.sciencedirect.com/journal/linear-algebra-and-its-applications)
* Peer review for ["Journal of Symbolic Computation"](https://www.journals.elsevier.com/journal-of-symbolic-computation)
* Peer review for ["The Annals of Probability"](https://www.imstat.org/journals-and-publications/annals-of-probability/) (unofficial) 


## Collaborations
* [Lek-Heng Lim](https://www.stat.uchicago.edu/~lekheng/) 
* [Robert Adler](https://robert.net.technion.ac.il/)
* [Liwen Zhang](https://newtraell.cs.uchicago.edu/people/liwenz)
* [Jorge Silva](https://scholar.google.com/citations?user=rZ8yeAkAAAAJ&hl=en)
* [Namita Lokare](https://scholar.google.com/citations?user=gEmpXL0AAAAJ&hl=en)
* [Ilknur Kaynar-Kabul](https://blogs.sas.com/content/author/ilknurkaynarkabul/)
* [David Fleischer](https://il.linkedin.com/in/davidfleischer)
* [Andrey Zhitnikov](https://sipl.eelabs.technion.ac.il/members/andrey-zhitnikov/)
* Leonid Prokupetz


