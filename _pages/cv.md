---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Civil Engineering, University of Glasgow (2021 – 2024)
  * Thesis: Modelling Piezoresistive Behaviour in Finitely Deformed Elastomeric Composites ([download](https://theses.gla.ac.uk/84772/))
* M.Sc. in Mechanical Engineering, University of Guilan (2014 – 2017)
* B.Sc. in Mechanical Engineering, Razi University (2009 – 2013)
* Diploma in Mathematics, National Organisation for Development of Exceptional Talents ([NODET](https://en.wikipedia.org/wiki/National_Organization_for_Development_of_Exceptional_Talents)) (2002 – 2009)

Professional Experience
======
* Postdoctoral Research Fellow (Feb 2025 – Present)
  * Department of Mathematics, University College London
  * EPSRC-funded OncoEng project
* Research Assistant (Jan 2021 – Dec 2024)
  * Glasgow Computational Engineering Centre (GCEC), University of Glasgow
* Visiting Researcher (Sep 2023 – Nov 2023)
  * Institute of Applied Mechanics, Friedrich-Alexander-Universität Erlangen-Nürnberg
* Research Fellow (Jan 2018 – Jan 2020)
  * DFG-Heisenberg group, Universität Siegen 
* Research Fellow (Jan 2015 – Jan 2018)
  * Mechanics of nanocomposite materials group, University of Guilan
* Engineer Intern (Apr 2012 – Oct 2012)
  * Ilam Province Water & Wastewater Co

Research Areas
======
* Computational Mechanics
* Finite Element Method
* Fracture Mechanics
* Multiscale Modelling
* Biomechanics
* Composite Materials
* Computational Mechanics

Technical Skills
======
* Programming
  * C++
  * Python
  * MATLAB
  * Fortran
* Scientific Computing
  * Firedrake
  * FEniCS
  * HPC / parallel computing
* CAE
  * ABAQUS
  * COMSOL Multiphysics
  * ANSYS

Publications
======
  {% if site.author.googlescholar %}
  <div class="wordwrap">For a full list of publications, please visit my <a href="{{site.author.googlescholar}}">Google Scholar</a> profile.</div>
  {% endif %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
* Teaching Assistant, Lab Demonstrator, and Marker (Sep 2021 – Dec 2024)
  * James Watt School of Engineering, University of Glasgow
    * ENG4025: Finite Element Analysis 4
    * ENG1062: Dynamics 1
    * ENG4122: Structural Analysis 4
    * ENG2082: Mechanics of Structures 2
    * ENG3035: Design and Manufacture 3
* Independent Tutor (Jun 2017 – Dec 2019)
  * Statics
  * Mechanics of Materials
  * ABAQUS
* Teaching Assistant (Jan 2015 – Sep 2017)
  * Faculty of Mechanical Engineering, University of Guilan
    * Finite Element Method using ABAQUS
    * Numerical Analysis
    * Mechanics of Materials
    * Mechanical Vibration

Honours & Awards
======
* Jim Gatheral Scholarship for placement, by James Watt School of Engineering, University of Glasgow (Sep 2023)
* Full College Scholarship for Ph.D., by the College of Science and Engineering, University of Glasgow (Jan 2021)
* Exceptional talent, by NODET (National Organisation for Development of Exceptional Talents), High School (Sep 2005)
* Ranked 3rd in NODET national Chess competition (May 2004)
* Exceptional talent, by NODET, Middle School (Sep 2002)
