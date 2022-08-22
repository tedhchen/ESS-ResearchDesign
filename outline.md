---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

## Reading Materials
Trochim, W.M.K. [The Research Methods Knowledge Base.](https://conjointly.com/kb/) (Online version hosted at Conjointly.)

Required readings should be completed before the corresponding class; they are designed to facilitate your understanding of the lectures or to help you with your group work. Additional materials are recommended but optional.

## Weekly Schedule

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}