---
permalink: sitemap.xml
layout: none
---

<urlset>
{% for post in site.posts %}
<url>
<loc>{{post.url | absolute_url }}</loc>
<lastmod>{{post.datemodified}}</lastmod>
</url>
{% endfor %}
</urlset>