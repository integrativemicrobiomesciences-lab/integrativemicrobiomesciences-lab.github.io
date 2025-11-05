---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

If you are interested in joining our team, [please get in touch](https://integrativemicrobiomesciences-lab.github.io/contact/) with a CV and cover letter explaining your interests in our research so as to initiate a conversation regarding potential opportunities. Please also submit a concise research proposal for prospective PhD projects (1 - 2 pages written) that aligns with the lab’s establshed topics and expertise to ensure appropriate support and mentoring can be provided.<br/>


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Collaborators

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo_JAyres.jpg" caption="[Prof. Janelle S. Ayres](https://www.salk.edu/scientist/janelle-ayres/)<br/>Salk Institute for Biological Studies, and<br/>Howard Hughes Medical Institute Investigator, USA" %}
{% include figure.html image="images/photo_JBarr.jpg" caption="[Prof. Jeremy Barr](https://research.monash.edu/en/persons/jeremy-barr/)<br/>Monash University, AUS" %}  
<!--{% include figure.html image="images/photo_RKnight.jpg" caption="Prof. Rob Knight<br/>University of California San Diego, USA" %}-->
{% include figure.html image="images/photo_TLawley.jpg" caption="[Dr. Trevor D. Lawley](https://www.sanger.ac.uk/person/lawley-trevor/)<br/>Wellcome Sanger Institute, UK" %}  
{% include figure.html image="images/photo_RSchittenhelm.jpg" caption="[Prof. Ralf B. Schittenhelm](https://research.monash.edu/en/persons/ralf-schittenhelm/)<br/>Monash University, AUS" %}
{% include figure.html image="images/DStrugnell.jpg" caption="[Prof. Richard (Dick) A. Strugnell, AO](https://www.doherty.edu.au/people/professor-richard-dick-strugnell)<br/>University of Melbourne, AUS" %}
<!--{% include figure.html image="images/photo_TStinear.jpg" caption="Prof. Timothy P. Stinear<br/>University of Melbourne, AUS" %}-->  
{% include figure.html image="images/photo_TWong.jpg" caption="[Assist. Prof. Tania Wong](https://www.taniawonglabrutgers.com/about)<br/>Rutgers Institute for Infectious & Inflammatory Diseases, USA" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
