---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

## Reading Materials
Trochim, W.M.K. [The Research Methods Knowledge Base.](https://conjointly.com/kb/){:target="_blank"} (Online version hosted at Conjointly.)

Other readings outlined in the weekly schedule below.

Required readings should be completed before the corresponding class; they are designed to facilitate your understanding of the week's topic and to help with class discussions and your projects. Additional materials are optional resources for you; in fact, I do not expect you to read all the additional materials, but dive into the ones that interest you.

## Weekly Schedule

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}