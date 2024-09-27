---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* O'Reilly, Patrick and Bugler, Andreas and Bhandari, Keshav and Morrison, Max and Pardo, Bryan, 'VoiceBlock: Privacy through Real-Time Adversarial Attacks with Audio-to-Audio Models,' <i> Neural Information Processing Systems. November 2022 </i>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}