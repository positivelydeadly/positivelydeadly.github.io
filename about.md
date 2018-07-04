---
title: About
layout: about
permalink: /about/
sitemap: true
---

**Positively Deadly Podcast** is a podcast talking all things death in American culture, with [Death Positive](http://www.orderofthegooddeath.com/resources/death-positive-movement) sensibility.

The podcast was started in 2018 by two brothers based in Queens - one studying aging and the other dabbling in podcasts. The realization that topics on death are so vast yet talk of death so limited inspired this project based around learning and dialogue.

### Hosts

{% for member in site.data.team %}
  **{{ member.name }}** {{ member.bio }}<br />
  {% if member.website %}<br />{{ site.data.text[site.locale].website | default: 'Website' }}: [{{ member.website }}]({{ member.website }}){% endif %} 
  {% if member.twitter %}<br />Twitter: [@{{ member.twitter }}](http://twitter.com/{{ member.twitter }}){% endif %}
{% endfor %}


### Credits

* *Music* (Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) or freer)
	* Theme: "U Make Me Feel" by **MK2** via [YouTube Audio Library](https://www.youtube.com/audiolibrary/music)
	* Additional: **Chris Zabriskie** via [Free Music Archive](http://freemusicarchive.org/music/chris_zabriskie/), **Kevin MacLeod** via [Incompetech](https://incompetech.com/)
* *Audio Editing*: **Audio Editing Solutions** [audioeditingsolutions.com](http://audioeditingsolutions.com/)
* *Graphics*: **Rosarian Cook** [rosieinc.studio](https://www.rosieinc.studio/)
* *Website Theme*: **Michael Rose** [mademistakes.com](https://mademistakes.com/work/so-simple-jekyll-theme/)
