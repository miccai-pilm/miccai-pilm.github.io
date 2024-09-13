---
layout: default
---

# Workshop program

Please note that the workshop will take place in conjunction with the [AIPAD](https://aipad-miccai.github.io) workshop.

<!--{% for entry in site.workshop.program %}
{% if entry.type == "organizer" %}
* {{ entry.time }}: {{ entry.desc }}
{% elsif entry.type == "oral" %}
* {{ entry.time }}: {{ entry.author }}, *{{ entry.title }}*
{% elsif entry.type == "keynote" %}
* {{ entry.time }}: **Keynote**: *{{ entry.title }}* ({{ entry.author }}, {{ entry.affiliation }})
{% endif %}
{% endfor %}-->

{% for entry in site.workshop.program2 %}
{% if entry.type == "organizer" %}
* {{ entry.time }} – {{ entry.desc }}
{% elsif entry.type == "orals" %}
* {{ entry.time }} – {{ entry.desc }}
{% for paper in entry.paper_list %}
  * {{ paper.author }}. **"{{ paper.title }}"**
{% endfor %}
{% elsif entry.type == "keynote" %}
* {{ entry.time }} – **{{ entry.ws }} Keynote** - {{ entry.author }} ({{ entry.affiliation }})
{% endif %}
{% endfor %}
