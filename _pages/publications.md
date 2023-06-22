---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
1. **Valencia, Miles**, "Early-Exercise Effects on Mice Tendon Remodeling" (2022). Electronic Theses, Projects, and Dissertations. 1554. [https://scholarworks.lib.csusb.edu/etd/1554](https://scholarworks.lib.csusb.edu/etd/1554)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
