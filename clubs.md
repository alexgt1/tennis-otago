---
layout: clubs
page_title: Join A Club
page_description: Description goes here
permalink: join-a-club
page_image: img/ball.jpg
---

<section>
<div class="row">
        {% for club in site.clubs %}
        <div class="card col-md-4">
        <div class="card-body">
        <h5 class="card-title"><a href="{{ site.url }}/{{ club.permalink }}">{{ club.page_title }}</a></h5>
        <p class="card-text">{{ club.page_description }}</p>
        </div>
    </div>
    {% endfor %}
</div>
</section>

