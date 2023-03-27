---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<hr color="000000"/>

<a href='https://scholar.google.co.uk/citations?user=2bNsYR0AAAAJ&hl=en'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjianqingzheng%2Fjianqingzheng.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

You may find my more articles and preprints on <u><a href="https://scholar.google.co.uk/citations?user=2bNsYR0AAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}
<br>
# <i>Journal</i>
{% for post in site.journal reversed %}
  {% include archive-single.html %}
{% endfor %}
<br>

# <i>Conference</i>
{% for post in site.conference reversed %}
  {% include archive-single.html %}
{% endfor %}
<br>

# <i>Patent</i>
{% for post in site.patent reversed %}
  {% include archive-single.html %}
{% endfor %}
