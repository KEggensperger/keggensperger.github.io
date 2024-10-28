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
  
  <div class="col-sm-6">
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

 * 2024 · (external) Lennart Metz: *Robust and Fast Transformer-based Models for Bio-medical Data*

## Former MSc and BSc Students

 * 2024 · Magnus Hornstein: *Stopping Criteria for Bayesian Optimization with Random Forests*
 * 2024 · Timothy Shinners [MSc]: *Prior-Data Fitted Networks Dan Do Mixed-Variable Bayesian Optimization*
 * 2024 · Samuel Wörz [MSc]: *Probabilistic Wind Power Forecasting with Automated Machine Learning Frameworks* (co-supervised with [Dr. Nicole Ludwig](https://www.mlsustainableenergy.com/de/))
 * 2024 · (external) Arne Cremer [MSc]: *Using GANs to interpolate between AUTOSAR graphs considering model validity*

--- 

**Want to work with me?**
  * For PhD Students: I recruit PhD students via [IMPRS-IS](https://imprs.is.mpg.de/) (Deadline mid-November each year). Please reach out to me for more details.
  * For MSc/BSc thesis: Please do reach out to me. Don't forget to mention your interests and adding list of AI-related courses you have taken.

