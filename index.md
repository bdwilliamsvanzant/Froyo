---
layout: home
comments: true
---

<div class="header">
<img src="images/bg-home.jpg" alt="">
<div> 
    <a href="product.html">Freeze Delight</a>
</div>
</div>
<div class="body" >
<div markdown="1">
<div markdown="1">

# NEW PRODUCT
## The Twist of Healthy Yogurt
This website template has been designed by freewebsitetemplates.com for you, for free. You can replace all this text with your own text.

</div>
<div>
{% if page.comments %}
<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = '{{ site.baseurl }}';  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = '{{ site.baseurl }}'; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://bensfroyo.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}

</div>

![](images/yogurt.jpg)

</div>
</div>