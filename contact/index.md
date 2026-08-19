---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# Contact

**Macrophages & Cancer**  
Centre de Recherche des Cordeliers   
15 rue de l'école de médecine
75006 Paris, France

For general inquiries, collaborations, or scientific discussions:

**[pauline.hamon@inserm.fr](mailto:pauline.hamon@inserm.fr)**


{%
  include button.html
  type="email"
  text="pauline.hamon@inserm.fr"
  link="pauline.hamon@inserm.fr"  
%}

{% include button.html type="website" text="Centre de Recherche des Cordeliers" link="https://crcordeliers.fr/en/home/" %}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/7BtAmZTnPbehrt7W6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
