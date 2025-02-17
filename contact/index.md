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
  text="email Megan"
  link="megan.leask@otago.ac.nz"
%}
{%
  include button.html
  type="phone"
  text="03 556 5243"
  link="+6435565243"
%}

{% include section.html %}

{%
  include gmap.html
  caption="Where we are"
%}

{% include section.html dark=true %}

{% capture col1 %}
Mailing address:  
Department of Physiology  
School of Biomedical Sciences  
University of Otago  
PO Box 56  
Dunedin 9054  
New Zealand  
{% endcapture %}

{% capture col2 %}
Visting address:  
Department of Physiology  
Lindo Ferguson Building  
270 Great King Street  
Dunedin Central  
Dunedin 9016  
New Zealand  
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
