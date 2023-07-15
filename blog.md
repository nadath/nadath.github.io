---
layout: default
title: blog
---

{% include element.html %}

<main>
  <div class="block">
    <h1>Latest Posts</h1>
    <ul>
      {% for post in site.posts %}
        <li>
          <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
          {{ post.excerpt }}
        </li>
      {% endfor %}
    </ul>
  </div>
</main>
