---
layout: page
title: W0lfb1t | Just another happy software developer
header: W0lfb1t
---

<div class="row">
	<div class="span6">
		<img src="http://www.gravatar.com/avatar/8e687484647e5b4598b88ec484a60f84?s=200">
		<p>
My name is Hilario.
I'm a software developer.
I also like to play PC games.

I enjoy learning new technologies.
		<p>
You can find me here:
 * [Google+](https://plus.google.com/110325304617093683727)
 * [Twitter](http://twitter.com/hpcorona)
 * [Steam](http://steamcommunity.com/id/muymaton/)
 * [Github](https://github.com/hpcorona)

	</div>
	
	<div class="span8">
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

	</div>

</div>
