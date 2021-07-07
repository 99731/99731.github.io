---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my full articles on [my Google Scholar profile]({{site.author.googlescholar}} "my Google Scholar profile")
{% endif %}
 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
