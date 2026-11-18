---
layout: archive
title: 'Sitemap'
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## Main Pages

- [About]({{ '/' | relative_url }})
- [Publications]({{ '/publications/' | relative_url }})
- [CV]({{ '/cv/' | relative_url }})

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
