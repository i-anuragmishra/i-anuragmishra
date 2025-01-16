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
* [Degree] in [Field], [University], [Year]
* [Another Degree] in [Field], [University], [Year]

Work experience
======
* [Current Position]
  * [Company/Organization]
  * [Duration]
  * [Key responsibilities]
  * [Achievements]

* [Previous Position]
  * [Company/Organization]
  * [Duration]
  * [Key responsibilities]
  * [Achievements]

Skills
======
* [Skill Category 1]
  * [Sub-skill 1.1]
  * [Sub-skill 1.2]
* [Skill Category 2]
  * [Sub-skill 2.1]
  * [Sub-skill 2.2]

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