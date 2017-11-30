---
layout: page
title: About
description: Change the world with electronics
keywords: Ali Rumane, Ali
comments: true
menu: About
permalink: /about/
---

I am Ali Rumane
Admired "The Art of Elegant coding".

Believe that practice makes perfect, and strive to change life.

## Contact

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
