---
layout: index
title: "Talks"
subtitle: Jake Zimmerman
---

I've been lucky enough to have given a number of talks on subjects I care about.
This site acts as a repository of the talk descriptions and slides in the hopes
that they might be useful.


{% capture numposts %}{{ site.posts | size }}{% endcapture %}
{% if numposts != '0' %}
## Talks by Year

{% for post in site.posts %}{% assign currentyear = post.date | date: "%Y" %}{% if currentyear != prevyear %}
### {{ currentyear }}
{% assign prevyear = currentyear %}{% endif %} - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: '%B %-d' }}
{% endfor %}
{% endif %}


