---
layout: default
---

<h1>Docs</h1>
{% for docs in site.docs %}
<ul>
    <li><a href="{{site.baseurl}}{{docs.url}}">{{docs.title}}</a></li>
</ul>
{% endfor %}