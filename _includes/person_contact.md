{%- assign person_id = include.person_id %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

#### Contact

- Email: [{{person.email}}](mailto:{{person.email}})
- Bibliography: [DBLP](https://dblp.uni-trier.de/pid/123/{{person.dblp_id}}.html), [Google Scholar](https://scholar.google.com/citations?user={{person.scholar}}hl=en)
- Office: {{person.office}}
