---
title: Press Kit
permalink: /press-kit
---


### Biographies for Publication

{% capture bio %}{% include damien-bio.md %}{% endcapture %}
<div class="tabbed">
    <input name="tabbed" id="tabbed1" type="radio" checked />
    <section>
        <h1>
            <label for="tabbed1">Text</label>
        </h1>
        <div>
            {{ bio | markdownify }}
        </div>
    </section>
    <input name="tabbed" id="tabbed2" type="radio" />
    <section>
        <h1>
            <label for="tabbed2">HTML</label>
        </h1>
        <div>
            {% highlight html %}{{ bio | markdownify }}{% endhighlight %}
        </div>
    </section>
    <input name="tabbed" id="tabbed3" type="radio" />
    <section>
        <h1>
            <label for="tabbed3">Markdown</label>
        </h1>
        <div>
            {% highlight md %}{{ bio }}{% endhighlight %}
        </div>
    </section>
</div>  
<br class="clear" />  
### Photos for Publication



### Social Media and Contact Info