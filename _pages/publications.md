---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

RESEARCH ARTICLES
======
* Runhua Wang, Jyh-An Lee, Jingwen Liu, “Governing the NFT Market by Static and Dynamic IP Laws,” American Business Law Journal, Vol.61, Issue1 (forthcoming 2024).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
