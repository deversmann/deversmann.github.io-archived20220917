---
title: About
permalink: /about
---

### About This Site

![DamienLIVE](/images/d_logo_mini.png){: width="100px" .image .left}
This site is the resource for all things Damien.  You'll find collected within these pages Damien's presentations and musings.  There is a smattering of videos and a regular newsletter about happenings and events at Red Hat and beyond.  Subscribe to the newsletter and check back often for updated posts and writings.

{% for author in site.authors %}
### About {{ author.name }} 

![{{ author.name }}]({{ author.headshot }}){: width="150px" .image .left} {{ author.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}

#### Colophon

- Site Generator: [Jekyll](http://jekyllrb.com/)
- Host: [GitHub](http://github.com/)
- Base Template Design: [HTML5 UP](http://html5up.net/)
