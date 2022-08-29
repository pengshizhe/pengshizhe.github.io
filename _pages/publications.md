---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com.sg/citations?user=V2KUfigAAAAJ&hl">my Google Scholar profile</a>
<a href='https://scholar.google.com/citations?user=V2KUfigAAAAJ&hl'><img src="https://img.shields.io/badge/citations%20-21-9cf?style=flat-square&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
