---
layout: page
title: Welcome!
tagline: from Vic and crew
---
{% include JB/setup %}

Welcome to my home page! Here you will find...

![Mumfred](http://farm9.staticflickr.com/8245/8463266030_35d330e35a.jpg "Mumfred")

## My blog

with all of my recent posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
    
## My gaming company

I am starting a gaming company. We are designing video games, card games, etc. My friends and I have decided to call it "Jungle Games." Our first game will be [Midnight's Protector](MP.html)


## To-do

Stay tuned for more content from me, including game walk-throughs and reviews, art, and more!


