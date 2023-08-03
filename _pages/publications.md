---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The full list of my publications can be found in [Google Scholar](https://scholar.google.com/citations?user=OeiDn_8AAAAJ) or [DBLP](https://dblp.uni-trier.de/pid/59/5241-5.html).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include publications.html %}
{% endfor %}
