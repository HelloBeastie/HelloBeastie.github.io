---
layout: default
---

# [](#Contact Us)Contact Us

Contact us and heres my gitpage twitter etc etc

<ul>
  <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
</ul>

<ul>

  {% if site.github_username %}
  <li>
    {% include icon-github.html username=site.github_username %}
  </li>
  {% endif %}

  {% if site.twitter_username %}
  <li>
    {% include icon-twitter.html username=site.twitter_username %}
  </li>
  {% endif %}
  
</ul>

{::comment}
Find out how to get the feed that the minima page has with the icons for facebook and we should also have a list of other places where they can find us
for example facebook, github, twitter, instagram etc
{:/comment}

* * *
[back](./)
