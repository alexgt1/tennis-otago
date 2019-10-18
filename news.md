---
layout: page
page_title: Recent News
page_description: Bringing you the latest news and information from Tennis Otago
permalink: news
page_image: img/ball.jpg
---

<section>
<div class="container">
    <div class="row">
        {% for post in site.posts %}
        <div class="col-md-6 news">
        <h2><a href="{{ site.url }}{{ post.url }}"> {{ post.page_title }} </a></h2>
        <p> {{ post.page_description }}</p>
        </div> 
        <div class="col-md-6 news-img">
        <img src='{{ post.page_image }}'/>
        </div>
        {% endfor %}
        </div>
</div> 
</section>