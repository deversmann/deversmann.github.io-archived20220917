---
title: About
permalink: /about
---

### About This Site

![DamienLIVE](/images/d_logo_mini.png){: width="100px" .image .left}This site is the resource for all things Damien.  You'll find collected within these pages Damien's presentations and musings.  There is a smattering of videos and a regular newsletter about happenings and events at Red Hat and beyond.  Subscribe to the newsletter and check back often for updated posts and writings.

{% for author in site.authors %}
### About {{ author.name }} 

![{{ author.name }}]({{ author.headshot }}){: width="200px" .image .left}Having spent the bulk of his career working in or with the public sector, Damien is somewhat of a expert when it comes to IT in government and higher education. Throughout his working life, Damien has served as a Developer, System Administrator, Development Manager, Enterprise Architect, Technology Director and now Solutions Architect.  He has worked on projects running the gamut from desktop-based widgets to major multi-tiered applications with web APIs and has developed an acumen for application architecture.  Most recently, Damien has traveled the country with Red Hat to share the news of Digital Transformation. He has a penchant for teaching and demonstration and his expertise includes DevOps Culture, Application Modernization, and Enterprise Automation.
{% endfor %}

#### Colophon

- Site Generator: [Jekyll](http://jekyllrb.com/)
- Host: [GitHub](http://github.com/)
- Base Template Design: [HTML5 UP](http://html5up.net/)
