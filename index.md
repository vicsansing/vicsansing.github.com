---
layout: page
title: Vic Sansing
tagline: and crew
---
{% include JB/setup %}

Welcome to my home page! Here you will find...

## My blog

with all of my recent posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
    
## My gaming company

I am starting a gaming company. We are designing video games, card games, etc. My friends and I have decided to call it "Jungle Games."


## To-do

Stay tuned for more content from me, including game walk-throughs and reviews, art, and more!


