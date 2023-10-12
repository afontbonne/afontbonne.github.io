---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <u><a href="https://scholar.google.com/citations?user=ZEPnKhoAAAAJ&hl=fr&oi=ao">Google Scholar profile</a></u>, or on my <u><a href="https://cv.hal.science/alice-fontbonne?langChosen=en">HAL</a></u> account.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
