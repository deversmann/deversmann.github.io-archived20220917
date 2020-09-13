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

### Social Media and Contact Info

{% for item in site.data.social %}{% if item.name != "Feed" %}* <a href="{{ item.link }}" class="{{ item.class }}"><span class="label">{{ item.name }}</span></a> - [{{ item.link }}]({{ item.link }})
{% endif %}{% endfor %}

