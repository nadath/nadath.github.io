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
  bottom: 0;
  width: 100%;
  color: var(--oc-green-4);
  background-color: var(--oc-gray-9);
  text-align: left;
}
</style>

<div class="footer">
  {% assign home = site.url | split: "//" | slice: 1 %}
  <a href="{{ site.url }}">{{ home }}</a>
</div>
