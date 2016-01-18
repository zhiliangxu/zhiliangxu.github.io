---
layout: default
title: My Blog
---

# {{ page.title }}
## Posts
{% for post in site.posts %} 
- {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}