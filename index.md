---
layout: default
---

# [](#Navigation)Navigation

* [About](about)
* [Services](services)
* [Available Subjects](available-subjects)
* [Contact Us](contact-us)
* [Cool Stuff](cool-stuff)

* * *
# [](#Blogs)Blogs

<ul>
   {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
      {{_by_ post.author _on_ post.date }}
      {{ post.excerpt }}
  {% endfor %}
</ul>

* * *
## [](#Paragraphs)Paragraphs

See our other pages in [Navigation](#navigation) for constantly updated information (~~with the old information for reference~~) on our available times as well as our tutors and subjects we offer.
Our services may change based on _your_ feedback. We value **knowledge** and **understanding** and it is our goal to make our insights _your own_.

* * *
## [](#Physics)Physics
![](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Tesla%20Coil.jpg)

* * *
## [](#Mathematics)Mathematics
![](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Mathematics.jpg)

* * *
## [](#Chemistry)Chemistry
![](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Molecule.png)

* * *
## [](#Biology)Biology
![](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Microorganism.jpg)

* * *
## [](#Languages)Languages
![](https://cdn.rawgit.com/HelloBeastie/HelloBeastie.github.io/master/_includes/Languages.jpg)

```
The final element.
```
{::comment}
logo with a motto
{:/comment}