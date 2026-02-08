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
* **Ph.D. in Computer Science**, King Abdullah University of Science and Technology (KAUST), 2023 Jan - present
* **Master of Science in Computer Science**, KAUST, Aug 2021 - Dec 2022
* **Bachelor's Degree in Telecommunications Engineering**, Queen Mary University of London (QMUL), 2017 Sep - 2021 Jun
  * First Class Honours
* **Bachelor's Degree in Telecommunications Engineering**, Beijing University of Posts and Telecommunications (BUPT), 2017 Sep - 2021 Jun
  * GPA 90.05/100, Rank 10/323

Internship Experience
======
* **Microsoft Research Asia (MSRA)**, Beijing, China, Sep 2023 - Jan 2024
  * Network Research Group
  * Mentor: Dr. Ran Shu
* **TU Darmstadt**, Darmstadt, Germany, Jun 2022 - Aug 2022
  * Work on network attached FPGA accelerator design
  * Mentor: Prof. Zsolt Istvan

Awards
======
* **Stars of Tomorrow Internship Award of Excellence**, Microsoft Research Asia, 2024
* **Outstanding Graduates of Beijing**, 2021
* **Second-class Merit Scholarship**, BUPT, 2017-2018, 2018-2019, 2019-2020

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
