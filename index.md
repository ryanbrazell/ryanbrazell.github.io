---
layout: default
title: Cop Shit
---
# {{ page.title }}

What is cop shit? Glad you asked. Check out Jeffrey Moro's article, <a href="https://jeffreymoro.com/blog/2020-02-13-against-cop-shit/" target="_blank">Against Cop Shit</a>.

<hr />

## Index

<ul class="posts">
	{% for post in site.posts %}
	 	<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
</ul>