---
layout: page
title: W0lfb1t | Just another happy software developer
header: W0lfb1t
---

My name is Hilario, and i'm a software developer.

For work i mostly use WinDev. For hobby pretty much everything: javascript, erlang, go, C/C++, ruby...

I love to code.
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
