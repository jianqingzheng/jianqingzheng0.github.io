---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<hr color="000000"/>

#{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

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
