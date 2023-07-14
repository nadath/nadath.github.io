---
layout: default
title: art
permalink: /art/
---

{% include photo.html folder="img" %}

<main>
    <div class="block">
        {% assign home = site.url | split: "//" | slice: 1 %}
        <a href="{{ site.url }}">{{ home }}</a>
    </div>
</main>
