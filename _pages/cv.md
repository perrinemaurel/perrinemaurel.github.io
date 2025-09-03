---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Here is my academic CV in PDF format.  
You can **download** it or **open it directly** below:

- 📄 [Download my CV (PDF)](/files/Curriculum_université_MAUREL.pdf)

---

Education
======
* Ph.D in Comparative Litterature, "" GitHub University, 2018 (expected)
* Master in Digital Humanities, PSL University (École nationale des chartes), 2023
* Double Bachelor in Computer Sciences and Modern Literature, Sorbonne University, 2021

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Programmation/Balisage [années d’apprentissage formel]
  * Python [5 ans]
  * R [2 ans]
  * XML [2 ans]
  * C [3 ans]
  * Scilab [2 ans]
  * Java [2 ans]
  * PHP [6 mois]
  * Ocml [1 an]
  * Javascript [1 an]

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
