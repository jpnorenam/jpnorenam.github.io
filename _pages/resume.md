---
layout: archive
title: "RESUMÉ"
permalink: /resume/
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

#rtos {
  width: 50%;
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

#elk_stack {
  width: 45%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#influx_grafana{
  width: 60%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}

#devops{
  width: 65%;
  height: 5px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}
</style>
</html>

---

Education
------
* **B.S. in Electrical Engineering**, Universidad Nacional de Colombia, 2015-2020. *GPA: 4.3/5.0*
* **M.Sc. in Electrical Engineering**, Universidad Nacional de Colombia, 2020-2022(expected). *Thesis proposal: "PMU Digital Twins for Applications in Power System Control Centres"*

---

Work experience
------
* **Student Researcher & Contractor** *(february 2018 - present) at Laboratorio de gestión de sistemas en tiempo-real, Facultad de Minas, Universidad Nacional de Colombia.*

**UNPowerEstimator: Library for Power System State Estimation** | Devolpment and implementation of a .NET Framework Class Library for online non-linear state estimator for the Colombian national power system operator -XM-, including CIM standard files processing and GPA - Project Alpha adapters for the phasor data concentrator. | *Supervisor: Prof. Jairo Espinosa*
**Storm Tracking for Minimization of Risk in Power System Operation Based on Real-Time Lighting Information** | Development of a software with tools that allows to take real-time decisions minimizing the risk over a power system operation based on thunderstorm following, grouping and processing. | *Supervisor: Prof. Ernesto Pérez*
**Real-Time Cosimulation Laboratory for the Scientic Ecosystem "Energética 2030"** | Development and implementation of cosimulation laboratory as a service for the scientic ecosystem, that allows to perform real-time simulation of multi-domain systems including the penetration of distributed energy resources. | *Supervisor: Prof. Ernesto Pérez*
**Intelligent Traffic Lights Programming Recommender Based on Real-Time Information** |Development of a software that combines AI and model based optimization, capable of finding the current traffic regime, based of patterns in the movility, and dynamically suggest the most convenient traffic lights coordinated plan. | *Supervisor: Prof. Jairo Espinosa*
  
---
  
Skills
------

* C/C++
<html>
<body> 
<div id="myProgress">
  <div id="cpp"></div>
</div>
</body>
</html> 

* C#/.NET Framework
<html>
<body> 
<div id="myProgress">
  <div id="netframework"></div>
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

* OPAL RT-LAB Suite
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

* RTOS (Linux PREEMPT_RT)
<html>
<body> 
<div id="myProgress">
  <div id="rtos"></div>
  <div style="margin-bottom: 40px;"></div>
</div>
</body>
</html>


* ELK Stack
<html>
<body> 
<div id="myProgress">
  <div id="elk_stack"></div>
  <div style="margin-bottom: 40px;"></div>
</div>
</body>
</html>


* InfluxDB & Grafana
<html>
<body> 
<div id="myProgress">
  <div id="influx_grafana"></div>
  <div style="margin-bottom: 40px;"></div>
</div>
</body>
</html>

* DevOps (Git, Vagrant & Ansible)
<html>
<body> 
<div id="myProgress">
  <div id="devops"></div>
  <div style="margin-bottom: 40px;"></div>
</div>
</body>
</html>

---

Publications
------
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
