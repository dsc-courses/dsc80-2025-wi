---
layout: page
title: 👩‍🏫 Staff
description: A listing of all the course staff members.
nav_order: 6
---

# 👩‍🏫 Staff

## Instructor

<div class="staffer">
  <img class="staffer-image" src="/assets/staff-images/watson-parris.jpg" alt="Duncan Watson-Parris">

  <div>
    <h3 class="staffer-name">
      <a href="https://www.samlau.me/">Duncan Watson-Parris</a>
    </h3>

    <!-- Contact Information -->
    <p>
      <a href="mailto:dwatsonparris@ucsd.edu">dwatsonparris@ucsd.edu</a><br>
    </p>

    <!-- Instructor Paragraph -->
    <p>
    Duncan Watson-Parris is an Assistant Professor in the Halıcıoğlu Data Science Institute and Scripps Institution of Oceanography, working at the interface of climate research and machine learning. The <a href="https://climate-analytics-lab.github.io">Climate Analytics Lab</a> he leads focuses on understanding the interactions between aerosols and clouds, and their representation within global climate models. CAL is leading the development of a variety of machine learning tools and techniques to optimally combine the huge variety of available observational datasets, including global satellite and aircraft measurements, to constrain and improve these important models.
    </p>
  </div>
</div>


## Staff

{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

{% assign staff = site.staffers | where: 'role', 'Tutor' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>
