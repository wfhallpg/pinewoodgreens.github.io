---
layout: default_with_title
title:  Neighborhood News and Features
---

<ul class="posts">  
	{% for post in site.posts %}  
	   <li>  
		   <span>{{ post.date | date_to_string }}</span> &raquo;  
		   <a href="{{ site.baseurl }}{{ post.url }}">  
		   {{ post.title }}</a>  
	   </li>  
	{% endfor %}  
</ul>
