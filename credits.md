---
title: Credits
layout: page
permalink: /credits/
sitemap: true
---

# Hosts

{% for member in site.data.team %}
  **{{ member.name }}** {{ member.bio }}<br />
  {% if member.website %}<br />{{ site.data.text[site.locale].website | default: 'Website' }}: [{{ member.website }}]({{ member.website }}){% endif %} 
  {% if member.twitter %}<br />Twitter: [@{{ member.twitter }}](http://twitter.com/{{ member.twitter }}){% endif %}
{% endfor %}


# Creative

* *Music* (Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) or freer)
	* Theme: "U Make Me Feel" by **MK2** via [YouTube Audio Library](https://www.youtube.com/audiolibrary/music)
	* Additional: **Chris Zabriskie** via [Free Music Archive](http://freemusicarchive.org/music/chris_zabriskie/), **Kevin MacLeod** via [Incompetech](https://incompetech.com/)
* *Audio Editing*: TBD
* *Graphics*: **Rosarian Cook** [rosieinc.studio](https://www.rosieinc.studio/)
* *Website Theme*: **Michael Rose** [mademistakes.com](https://mademistakes.com/work/so-simple-jekyll-theme/)
