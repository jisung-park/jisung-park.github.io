---
layout: default
title: "Publications"
---

#### Publications

{% for paper in site.data.publications %}
- **[{{paper.venue}} {{paper.year}}]** {paper.title}.
{{paper.authors}}
*{{paper.book}}*, {{paper.place}}, {{paper.month}} {{paper.year}} 
{% endfor %}
