


You can also find my publictions listed here:

 <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
 <u><a href="https://www.aclweb.org/anthology/people/a/alexandra-birch/">ACL Papers</a>.</u>
 <u><a href="https://dblp.org/pid/24/6740.html">DBPL</a>.</u>


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
