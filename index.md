---
layout: page
title: W0lfb1t | Just another happy software developer
header: W0lfb1t
---

<div class="row">
	<div class="span4">
		<img src="http://www.gravatar.com/avatar/8e687484647e5b4598b88ec484a60f84?s=200">
		<p>
<strong>My name is Hilario.</strong><br/>
I'm a software developer.<br/>
I also like to play PC games.<br/>
<br/>
I enjoy learning new technologies.
		</p>
		<p>
You can find me here:
		<ul>
 			<li><a href="https://plus.google.com/110325304617093683727">Google+</a></li>
			<li><a href="http://twitter.com/hpcorona">Twitter</a></li>
			<li><a href="http://steamcommunity.com/id/muymaton/">Steam</a></li>
			<li><a href="https://github.com/hpcorona">Github</a></li>
		</ul>
		</p>
	</div>
	
	<div class="span10">

<h2>Posts</h2>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

	</div>

</div>
