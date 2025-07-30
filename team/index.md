---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We’re building and training a team of interdisciplinary scientists, including, for example, microbiologists, bioinformaticians, ecologists, and clinicians who are interested in tackling global problems at the interface of infectious diseases, antibiotic resistance, and phage biology, from the vantage point of integrative microbiome sciences.


If you are interested in joining our team, [please get in touch](https://integrativemicrobiomesciences-lab.github.io/contact/) with a CV and cover letter explaining your interests in our research so as to initiate a conversation regarding potential opportunities. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Collaborators

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo_JAyres.jpg" caption="Prof. Janelle S. Ayres<br/>Salk Institute for Biological Studies, USA" %}
<!--{% include figure.html image="images/photo_JIredell.jpg" caption="Prof. Jonathan R. Iredell <br/>Westmead Institute for Medical Research; University of Sydney, AUS" %}-->  
{% include figure.html image="images/photo_RKnight.jpg" caption="Prof. Rob Knight<br/>University of California San Diego, USA" %}
{% include figure.html image="images/photo_TLawley.jpg" caption="Dr. Trevor D. Lawley<br/>Wellcome Sanger Institute, UK" %}
{% include figure.html image="images/photo_RSchittenhelm.jpg" caption="Prof. Ralf B. Schittenhelm<br/>Monash University, AUS" %}
{% include figure.html image="images/DStrugnell.jpg" caption="Prof. Richard (Dick) A. Strugnell, AO<br/>University of Melbourne, AUS" %}
<!--{% include figure.html image="images/photo_TStinear.jpg" caption="Prof. Timothy P. Stinear<br/>University of Melbourne, AUS" %}-->  
{% include figure.html image="images/photo_TWong.jpg" caption="Assist. Prof. Tania Wong<br/>Rutgers Institute for Infectious & Inflammatory Diseases, USA" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
