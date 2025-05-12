---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Or ResearchGate <a href="https://www.researchgate.net/profile/Yuxuan-Zhang-61?ev=hdr_xprf">

Or Web of Science <a href="https://www.webofscience.com/wos/author/record/KHC-7517-2024">
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
