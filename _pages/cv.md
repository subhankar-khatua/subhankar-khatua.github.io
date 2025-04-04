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
* Ph.D., The Institute of Mathematical Sciences, Chennai, 2016 - 2022
* M.Sc., The Institute of Mathematical Sciences, Chennai, 2014 - 2016
* B.Sc., University of Calcutta, 2010 - 2013

Work experience
======
* 2024 - Present: Hallwachs-Röntgent Postdoctoral Researcher
  * Institute for Theoretical Solid State Physics, IFW Dresden, Germany
  * Supervisor: Prof. Jeroen van Den Brink and Prof. Fakher Assaad

* 2022 - 2024: Joint Postdoctoral Reseacher
  * University of Waterloo and University of Windsor, Canada
  * Supervisor: Prof. Michel J. P. Gingras and Prof. Jeffrey G. Rau


Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
{% comment %}
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 {% endcomment %} 

Selected publications
======
<ol>
  {% for post in site.publications reversed %}
    <li>
      <strong>{{ post.title }}</strong><br>
      {% assign authors = post.authors | split: ',' %}
      {% for author in authors %}
        {% if author contains "S. Khatua" %}
          <span style="color: steelblue;">{{ author }}</span>
        {% else %}
          {{ author }}
        {% endif %}
        {% if forloop.last == false %}, {% endif %}
      {% endfor %}
      — 
      <a href="{{ post.paperurl }}" target="_blank" style="text-decoration: none;">{{ post.venue }}</a>
    </li>
  {% endfor %}
</ol>

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
