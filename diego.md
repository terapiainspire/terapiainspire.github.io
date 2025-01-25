---
layout: page
language: pt-br
title: Diego Santos
description: Especialista em Psicanálise e áreas afins, ajudo a reduzir estresse, organizar rotinas e desenvolver autoconhecimento e harmonia interior.
image: ../images/diego.jpg
---
{% if page.language == "en" %}{% assign data = site.data.dataen %}{% else %}{% assign data = site.data.data %}{% endif %} 
{% include about.html %}
{% include home/planos.html %}
{% include contact.html %}		