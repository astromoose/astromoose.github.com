---
layout: page
---

	  {% for post in site.posts offset: 0 limit: site.theme.homepage_featured %}
  			{% include post_featured.html %}
 		{% endfor %}
<br>

<hr>

<a href="/archive.html">Older Posts »</a>
