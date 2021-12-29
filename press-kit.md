---
title: Press Kit
permalink: /press-kit
---


### Biographies for Publication

{% capture bio %}{% include damien-bio.md %}{% endcapture %}


<!-- tabPanel from https://codepen.io/thierry/pen/gPoWxj -->
<div class="tabPanel-widget">
    <label for="tab-1" tabindex="0"></label>
    <input id="tab-1" type="radio" name="tabs" checked="true" aria-hidden="true">
    <h2>Text</h2>
    <div>{{ bio | markdownify }}</div>
    <label for="tab-2" tabi ndex="0"></label>
    <input id="tab-2" type="radio" name="tabs" aria-h idden="true">
    <h2>HTML</h2>
    <div>{% highlight html %}{{ bio | markdownify }}{% endhighlight %}</div>
    <label for="tab-3" tabindex="0"></label>
    <input id="tab-3" type="radio" name="tabs" aria-hidden="true">
    <h2>Markdown</h2>
    <div>{% highlight md %}{{ bio }}{% endhighlight %}</div>
</div>

<br class="clear" />  

### Photos for Publication

{% include image-gallery.html folder="/assets/images/headshots" %}

### Certifications

<a href="https://rhtapps.redhat.com/certifications/badge/verify/TKTO7OS6YC7EJ5K5BPTWAJ2S3MAEQU3CUPSQX2KSDXT6RW46LQ33TZNCC5VGOAYPFY7HVVIGB5XKUTI5W6QLZX6UMV3D6ILAY7YA4GY="><img src="https://rhtapps.redhat.com/certifications/badge/download/TKTO7OS6YC7EJ5K5BPTWAJ2S3MAEQU3CUPSQX2KSDXT6RW46LQ33TZNCC5VGOAYPFY7HVVIGB5XKUTI5W6QLZX6UMV3D6ILAY7YA4GY=?download" /></a>

<a href="https://rhtapps.redhat.com/certifications/badge/verify/TKTO7OS6YC7EJ5K5BPTWAJ2S3MAEQU3CUPSQX2KSDXT6RW46LQ3T7ULZ55KZZ56SKO7EQ3ETTLYZQ4U5NQYTCNA62RUWOCM34WWBUYQ="><img src="https://rhtapps.redhat.com/certifications/badge/verify/TKTO7OS6YC7EJ5K5BPTWAJ2S3MAEQU3CUPSQX2KSDXT6RW46LQ3T7ULZ55KZZ56SKO7EQ3ETTLYZQ4U5NQYTCNA62RUWOCM34WWBUYQ=?download" /></a>

### Social Media and Contact Info

{% for item in site.data.social %}{% if item.name != "Feed" %}* <a href="{{ item.link }}" class="{{ item.class }}"><span class="label">{{ item.name }}</span></a> - [{{ item.link }}]({{ item.link }})
{% endif %}{% endfor %}

