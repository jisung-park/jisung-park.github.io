---
layout: default
title: "Publications"
---

#### Peer-Reviewed Publications

{% for paper in site.data.publications %}
- **[{{paper.venue}} {{paper.year}}]** {{paper.title}}. <br>
{{paper.authors}}.<br>
*{{paper.book}}*, {%if paper.place %} {{paper.place}}, {% end if %}{{paper.month}} {{paper.year}}{% if paper.etc %} ({{paper.etc}}){% endif %}.
{% endfor %}

#### Patent

{% for patent in site.data.patents %}
- {{patent.title}}. <br>
{{patent.inventors}}. <br>
{{patent.number}}, {{patent.date}}.
{% endfor %}
