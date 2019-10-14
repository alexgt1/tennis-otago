---
layout: clubs
page_title: Join A Club
page_description: Description goes here
permalink: join-a-club
page_image: img/ball.jpg
---

<section>

<div class="container">
<div class="row page-content">
    <div class="col-md-8 main-content">
        <div>
            {% for club in site.clubs %}
            <div class="club">
            <h2 href="#"> {{ club.page_title }}</h2>
            <p href="#"> {{ club.page_description }}</p>
            </div>
            {% endfor %}
            </div>
    </div>
    </div>
</div>
</section>