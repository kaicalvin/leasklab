---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to contact us if you would like to learn more about our research or inquire about training opportunities.

{%
  include button.html
  type="email"
  text="megan.leask@otago.ac.nz"
  link="megan.leask@otago.ac.nz"
%}
{%
  include button.html
  type="phone"
  text="03 556 5243"
  link="+6435565243"
%}

{% include section.html %}

{% capture col1 %}

{%
  include gmap.html
  caption="Where we are"
%}

{% endcapture %}

{% capture col2 %}

{% "" %}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

{% capture col1 %}
Department of Physiology  
School of Biomedical Sciences  
University of Otago  
PO Box 56  
Dunedin 9054  
New Zealand  
{% endcapture %}

{% capture col2 %}
Department of Physiology  
Lindo Ferguson Building  
270 Great King Street  
Dunedin Central  
Dunedin 9016  
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
