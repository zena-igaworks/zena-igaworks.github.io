---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---



<h1>Docs</h1>
{% for docs in site.docs %}
<ul>
    <li><a href="{{site.baseurl}}{{docs.url}}">{{docs.title}}</a></li>
</ul>
{% endfor %}