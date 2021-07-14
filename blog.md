---
layout: tags
permalink: /blog
---

{% for post in side.posts%}
    {%include tags-single.html %}
{% endfor %}