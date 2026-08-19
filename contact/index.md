---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-solid fa-users" %} Contact

## Find Us

**Centre de Recherche des Cordeliers**

Sorbonne Université - Université Paris Cité  

15 rue de l'École de Médecine

75006 Paris, France

{%
  include button.html
  type="email"
  text="pauline.hamon@inserm.fr"
  link="pauline.hamon@inserm.fr"  
%}

{% include button.html type="website" text="Centre de Recherche des Cordeliers" link="https://crcordeliers.fr/en/home/" %}

## Getting here

The team is located at the Centre de Recherche des Cordeliers, in the heart of the Latin Quarter in Paris.

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/7BtAmZTnPbehrt7W6"
%}

{% include section.html %}

## The Cordeliers Research Center

{% capture col1 %}

{% include figure.html
  image="images/cordeliers/cordeliers-3.jpeg"
  caption="Centre de Recherche des Cordeliers"
%}

{% endcapture %}

{% capture col2 %}

{% include figure.html
  image="images/cordeliers/cordeliers-2.jpeg"
  caption="Centre de Recherche des Cordeliers"
%}

{% endcapture %}

{% capture col3 %}

{% include figure.html
  image="images/cordeliers/cordeliers-4.jpg"
  caption="Centre de Recherche des Cordeliers"
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
