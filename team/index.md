---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team of geneticisits, statisticians, cell biologists, neuroscientists and zebrafish lovers working to find better treatments and preventative measures for metabolic disorders.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Past members

{% include section.html %}

{% capture content %}

{% include figure.html image="images/members/robert_paulson.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
