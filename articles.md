---
layout: default
---

# [](#Articles)Articles

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} by {{post.author}}</span>
      <h3>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h3>
	  <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>



* * *
<a href="javascript:history.back()">Back</a>