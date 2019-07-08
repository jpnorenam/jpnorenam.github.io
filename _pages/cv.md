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
  width: 40%;
  background-color: #ddd;
}

#netframework {
  width: 80%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#cpp {
  width: 55%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#python {
  width: 70%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#matlab {
  width: 60%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#openHistorian2 {
  width: 75%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#powerfactory {
  width: 35%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#pscad {
  width: 40%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#opal {
  width: 40%;
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
* feb 2018 - dic 2018: Research Assistant
  * Laboratorio de gestión de sistemas en tiempo-real
  * **Real-time Power System State Estimator **
  * Duties included: Implementation of an online non-linear state estimator for the Colombian national power system operator -XM S.A E.S.P-.
  * Supervisor: Jairo Espinosa

* jun 2019 - present: Research Assistant
  * Laboratorio de gestión de sistemas en tiempo-real
  * **Energética 2030 Cosimulation Laboratory**
  * Duties included: Integration of several node in the development of the cosimulation laboratory for the scientific ecosystem.
  * Supervisor: Ernesto Pérez
  
Skills
======

* C#/.NET Framework
  * Grid Solution Framework
  * ILNumerics
  * Alglib 
<html>
<body> 
<div id="myProgress">
  <div id="netframework"></div>
</div>
</body>
</html>

* C/C++
  * Linux PREEMPT_RT real-time applications
  * POSIX API
  * MPI
<html>
<body> 
<div id="myProgress">
  <div id="cpp"></div>
</div>
</body>
</html> 
 
* Python
<html>
<body> 
<div id="myProgress">
  <div id="python"></div>
</div>
</body>
</html>

* Matlab/Simulink
<html>
<body> 
<div id="myProgress">
  <div id="matlab"></div>
</div>
</body>
</html>

* OPAL RT-LAB
<html>
<body> 
<div id="myProgress">
  <div id="opal"></div>
</div>
</body>
</html>

* PowerFactory
<html>
<body> 
<div id="myProgress">
  <div id="powerfactory"></div>
</div>
</body>
</html>

* openHistorian2
<html>
<body> 
<div id="myProgress">
  <div id="openHistorian2"></div>
</div>
</body>
</html>

* PSCAD
<html>
<body> 
<div id="myProgress">
  <div id="pscad"></div>
  <div style="margin-bottom: 40px;"></div>
</div>
</body>
</html>

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
