---
title: Resources
layout: page
permalink: /resources/
sitemap: true
---

<div style="text-align:center">
<p>Dying to know more?</p>

<p>
{% for resource in site.data.resources %}
	<a href="{{ resource.link }}" target="_blank">{{ resource.name }}</a>
	<br />
{% endfor %}
</p>
</div>
