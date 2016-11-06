---
layout: index
title: "Talks"
subtitle: Jake Zimmerman
---

I always love getting the chance to speak on topics about which I'm passionate.
This site is a repository to collect all the talks I've given.


{% capture numposts %}{{ site.posts | size }}{% endcapture %}
{% if numposts != '0' %}
## Talks by Year

{% for post in site.posts %}{% assign currentyear = post.date | date: "%Y" %}{% if currentyear != prevyear %}
### {{ currentyear }}
{% assign prevyear = currentyear %}{% endif %} - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: '%B %-d' }}
{% endfor %}
{% endif %}


