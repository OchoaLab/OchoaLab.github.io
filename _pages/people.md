---
layout: archive
title: "People"
permalink: /people/
author_profile: false
---

{% include base_path %}

{% for post in site.people %}
  {% include people-single.html %}
{% endfor %}

# Alumni

{% for post in site.alumni %}
  {% include people-single.html %}
{% endfor %}

