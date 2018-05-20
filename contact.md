---
title: Contact
layout: page
permalink: /contact/
sitemap: true
---

<div style="text-align:center">
	{% include contact-form.html %}

	<br /><br />
	{{ site.data.text[site.locale].newsletter_cta | default: 'Get Notified via Email' }}: <a href="{{ site.newsletter_url }}" target="_blank">{{ site.newsletter_url }}</a>
	<br />
	{{ site.data.text[site.locale].itunes_rating_cta | default: 'Rate on iTunes' }}: <a href="{{ site.itunes_url }}" target="_blank">{{ site.itunes_url }}</a> 
	<br />
	{{ site.data.text[site.locale].pod_feed_cta | default: 'Add to Podcatcher' }}: <a href="{{ site.pod_feed }}" target="_blank">{{ site.pod_feed }}</a>
	<br />
	{{ site.data.text[site.locale].fundraing_cta | default: 'Support Us' }}: <a href="{{ site.fundraising_url }}" target="_blank">{{ site.fundraising_url }}</a>
</div>
