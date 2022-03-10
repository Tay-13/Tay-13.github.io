---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


# Selected Publications

[1] **Jiaqian Liu**, Haipeng Dai, Rui Xia, Meng Li, Ran Ben Basat, Rui Li and Guihai Chen. "DUET: A Generic Framework for Finding Special Quadratic Elements in Data Streams". In Proceedings of the World Wide Web Conference (WWW), Lyon, France, April 25–29, 2022.
