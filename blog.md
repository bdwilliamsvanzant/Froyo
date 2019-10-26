---
layout: blog
title: blog
---
<div class="header" markdown="1">
<div markdown="1">

# Blog

</div>
</div>

<div class="blog" markdown="1">
<div class="featured" markdown="1">
<ul>
{% for post in site.posts offset:1 %}
<li>
<image src="{{post.image}}"></image>
<div>
{{ post.content }}
<a href="{{ site.baseurl }}{{ post.url }}" class="more">Read More</a>
</div>
</li>

{% endfor %}
</ul>
</div>



<div class="sidebar" markdown="1">

# Recent Posts

{% for post in site.posts limit:1 %}
<image src="{{post.image}}"></image>
{{ post.content }}
<a href="{{ site.baseurl }}{{ post.url }}" class="more">Read More</a>
{% endfor %}

</div>
</div>