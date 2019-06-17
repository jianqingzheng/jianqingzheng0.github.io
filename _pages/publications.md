---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<hr color="000000"/>


You may find my more articles and preprint on <u><a href="https://scholar.google.co.uk/citations?user=2bNsYR0AAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}
<br>

# <i>Conference</i>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<br>

# <i>Patent</i>
{% for post in site.patent reversed %}
  {% include archive-single.html %}
{% endfor %}
