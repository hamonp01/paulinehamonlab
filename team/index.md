---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We believe that scientific excellence thrives through diversity of perspectives, experiences, and backgrounds. Our lab is committed to fostering an inclusive and respectful environment where everyone can contribute, grow, and feel valued. We welcome individuals with diverse expertise, origins, and career paths, and we strive to build a team that reflects the diversity of the scientific community.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/Team/Lab_picture_1.jpeg" %}
{% include figure.html image="images/Team/Camilles_pose.JPG" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
