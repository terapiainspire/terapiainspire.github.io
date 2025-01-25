---
layout: home
language: en
description: Take care of your mental, emotional and spiritual health 
---
{% if page.language == "en" %}{% assign data = site.data.dataen %}{% else %}{% assign data = site.data.data %}{% endif %} 
{% include home/inspire.html %}
{% include home/planos.html %}
{% include contact.html %}		
{% include home/terapia.html %}
{% include home/logoterapia.html %}
{% include about.html %}
{% include home/agenda.html %}