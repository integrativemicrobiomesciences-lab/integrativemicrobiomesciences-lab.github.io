---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We’re building and training a team of interdisciplinary scientists, including, for example, microbiologists, bioinformaticians, ecologists, and clinicians who are interested in tackling global problems at the interface of infectious diseases, antibiotic resistance, and phage biology, from the vantage point of integrative microbiome sciences.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Collaborators

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo_JAyres.jpg" %}
{% include figure.html image="images/photo_RKnight.jpg" %}
{% include figure.html image="images/photo_TWong.jpg" %}
{% include figure.html image="images/photo_TLawley.jpg" %}
{% include figure.html image="images/photo_TStinear.jpg" %}
{% include figure.html image="images/photo_RSchittenhelm.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
