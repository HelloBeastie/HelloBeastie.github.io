---
layout: default
---

# [](#Blogs)Blogs

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} by {{post.author}}</span>
      <h3>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

* * *
