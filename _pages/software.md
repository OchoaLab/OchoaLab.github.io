---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

## Major packages

{% for post in site.software_package_major reversed %}
  {% include software-single.html %}
{% endfor %}

## Minor packages

{% for post in site.software_package_minor reversed %}
  {% include software-single.html %}
{% endfor %}

## Paper repositories

{% for post in site.software_paper reversed %}
  {% include software-single.html %}
{% endfor %}
