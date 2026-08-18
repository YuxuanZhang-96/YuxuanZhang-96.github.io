---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Or  <a href="https://www.researchgate.net/profile/Yuxuan-Zhang-61?ev=hdr_xprf"> my ResearchGate </a>

Or if you would like to check my Chinese version official website at <a href="https://jsjxy.bua.edu.cn/info/1108/3431.htm"> my Beijing University of Agriculture Website </a>



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
