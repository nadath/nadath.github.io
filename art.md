---
layout: default
title: art
permalink: /art/
---

{% include photo.html folder="img" %}

<style>
.footer {
  position: fixed;
  left: 0;
  bottom: 1%;
  width: 100%;
  color: var(--oc-green-4);
  text-align: center;
}
</style>

<div class="footer">
  {% assign home = site.url | split: "//" | slice: 1 %}
  <a href="{{ site.url }}">{{ home }}</a>
</div>
