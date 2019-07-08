---
layout: archive
title: "Resumé"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<html>
<style>
#myProgress {
  width: 20%;
  background-color: #ddd;
}

#netframework {
  width: 75%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}
</style>
</html>

Education
======
* **B.S. in Electrical Engineering**, Universidad Nacional de Colombia, 2020 (expected). *GPA: 4.3/5.0*

Work experience
======
* Feb 2018 - Dic 2018: Research Assistant
  * Laboratorio de gestión de sistemas en tiempo-real
  * Duties included: Implementation of an online state estimator for the Colombian national power system operator -XM S.A E.S.P-
  * Supervisor: Jairo Espinosa

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Ernesto Pérez
  
Skills
======

* C#/.NET Framework
<html>
<body> 
<div id="myProgress">
  <div id="netframework"></div>
</div>
</body>
</html>
  * Grid Solution Framework
  * ILNumerics
  * Alglib
  
* C/C++
  * Linux PREEMPT_RT real-time aplications
  * POSIX API
  * MPI
* Python 
* openHistorian2
* PowerFactory
* PSCAD
* OPAL RT-LAB

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
