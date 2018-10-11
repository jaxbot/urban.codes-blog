---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

I'm Jonathan. I write software, study robots and advocate for safer streets and bike lanes.

<a href="https://jaxbot.me/">Main blog</a><br>
<a href="https://twitter.com/jaxbot/">Twitter</a>

</div>
