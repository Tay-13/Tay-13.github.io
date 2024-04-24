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

[1] **Jiaqian Liu**, Haipeng Dai, Rui Xia, Meng Li, Ran Ben Basat, Rui Li and Guihai Chen. ["DUET: A Generic Framework for Finding Special Quadratic Elements in Data Streams"](https://dl.acm.org/doi/pdf/10.1145/3485447.3512019). In Proceedings of the Web Conference (TheWebConf), Lyon, France, April 25–29, 2022.

[2] **Jiaqian Liu**, Ran Ben Basat, Louis de Wardt, Haipeng Dai, and Guihai Chen. "DISCO: A Dynamically Configurable Sketch Framework in Skewed Data Streams". In Processing of IEEE International Conference on Data Engineering (ICDE), Utrecht, The Netherlands, May 13-17, 2024.

[3] **Jiaqian Liu**, Haipeng Dai, Rui Xia, Meng Li, Ran Ben Basat, Rui Li, Rong Gu, Jiaqi Zheng, and Guihai Chen. "A Generic Framework for Finding Special Quadratic Elements in Data Streams". IEEE/ACM Transactions on Networking (TNET), 2024.
