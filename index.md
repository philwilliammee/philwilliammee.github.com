---
layout: page
title: Phil's Intro <br>
tagline: Welcome to my electronics blog!
---
{% include JB/setup %}

## Raspberry pi
This site was made and is maintaned using a RaspberryPi and the Raspbian OS
    
    This site uses `ruby gems`, `jeykyll`, `html` and is hosted by github.
    I don't know anything about ruby or html, but I'm learning:
    
All of the code for this site is at my [github repository](http://github.com/philwilliammee/philwilliammee.github.com)
    
## My Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

This blog contains my post pages and blog data, it also contains jeykll samples.

## To-Do

Hi my site is still heavily under construction as I try and figure out how I want it set up.
I have borrowed from [jekyll bootsrap](http://github.com/plusjade/jekyll-bootstrap) to help me get started so you will see a lot of refernces to jekyll.

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)


