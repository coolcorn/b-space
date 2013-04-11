---
layout: default
title: Brookline School Population & Capacity Exploration (B-SPACE) 
---
This is **not** the official B-SPACE page, which is over at http://www.brooklinema.gov/index.php?option=com_content&view=article&id=1503&Itemid=1742

This page was created by [a Brookline parent](http://thedurbins.com/phil/devo) and contains blog posts and links related to B-SPACE.

<ul class="posts">
{% for post in site.posts reversed %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

[recent changes]: https://github.com/coolcorn/b-space/commits/gh-pages
