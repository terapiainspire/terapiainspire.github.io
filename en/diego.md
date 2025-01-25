---
layout: page
language: en
title: Diego Santos
description: Specialist in Psychoanalysis and related fields, I help reduce stress, organize routines, and develop self-awareness and inner harmony.
image: ../images/diego.jpg
---
{% if page.language == "en" %}{% assign data = site.data.dataen %}{% else %}{% assign data = site.data.data %}{% endif %} 
{% include about.html %}
{% include home/planos.html %}
{% include contact.html %}		