---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true

---
{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">talk map!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
