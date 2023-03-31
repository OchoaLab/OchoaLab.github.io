---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

# Major packages

{% for post in site.software.package_major reversed %}
  {% include software-single.html %}
{% endfor %}

# Minor packages

{% for post in site.software.package_minor reversed %}
  {% include software-single.html %}
{% endfor %}

# Paper repositories

{% for post in site.software.paper reversed %}
  {% include software-single.html %}
{% endfor %}
