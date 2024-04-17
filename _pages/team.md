---
layout: archive
title: "Research Group"
permalink: /team/
author_profile: true
---

## Current Team Members

<div>
{% assign number_printed = 0 %}
{% for member in site.data.members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-2">

<img src="{{ site.url }}{{ site.baseurl }}/images/profile_pictures/{{ member.avatar }}" width="50%" style="max-width:200px"/>
</div>
<div class="social-icons">
  <h3>{{ member.name }}</h3>
  <i>{{ member.info }}<br></i>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fas fa-fw fa-home"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fas fa-fw fa-envelope"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="fas fa-fw fa-graduation-cap"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fab fa-fw fa-github"></i></a> {% endif %}
{% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fab fa-fw fa-linkedin"></i></a> {% endif %}

</div>
<!-- </div> -->

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
</div>

## Currrent MSc and Bsc Students

  
  * Samuel Wörz: *Probabilistic Wind Power Forecasting with Automated Machine Learning Frameworks* (co-supervised with [Dr. Nicole Ludwig](https://www.mlsustainableenergy.com/de/))

## Former MSc Students

 * 2024 · Timothy Shinners: *Prior-Data Fitted Networks Dan Do Mixed-Variable Bayesian Optimization*

--- 

**Want to work with me?**
  * For PhD Students: I recruit PhD students via [IMPRS-IS](https://imprs.is.mpg.de/) (Deadline mid-November each year). Here is an [example call for a PhD position](https://keggensperger.github.io/files/2023_JobPosting.pdf) or reach out to me for more details.
  * For MSc/BSc thesis: Please do reach out to me. Don't forget to mention your interests and adding list of AI-related courses you have taken.

