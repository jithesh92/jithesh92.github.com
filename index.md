---
layout: page
title: Tech E Coder
tagline: Notes and Comments on Technology and codes
---
{% include JB/setup %}

Welcome to my blog. You can get it touch with me via here.

##About Me

Myself, am student at [Government Engineering College - Thrissur](http://gectcr.ac.in/). Pursuing Btech Computer Science And Engineeing.

You can connect with me through [mail](mailto:jithesh@outlook.in)  

My GitHub page is at [https://github.com/jithesh92](https://github.com/jithesh92)

---
<div class="row">
<div class="span12 pagination-centered">
    <h1>Latest Posts</h1>
</div>  
</div>  
---  

<ul >
    {% for post in site.posts limit 4 %}
    <h3><li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li></h3><br></br>
        {{ post.content | strip_html | truncatewords:75}}<br>
            <br><a href="{{ post.url }}" class="btn btn-primary">Read more...</a><br><br>
    {% endfor %}
</ul>




