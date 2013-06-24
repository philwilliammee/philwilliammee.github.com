---
layout: page
title: Controlled Systems
tagline: <br>Interfacing with the world....Hello World
--- 
<!-- edit styles -->
<!--
<style type="text/css">
  body{background:grey}
</style>
-->
<section role="banner">
  <img src="/img/banner.jpg" />
</section>
## My Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

This blog contains my post pages and blog data, it also contains jeykll samples.

{% include JB/setup %}
## Interfaces
One of the first Jobs I had was in manufacturing. I worked on a simple machine that had a motor, valves, a LCD monitor, and a keypad. I was amazed at how the machine worked and how I could control the machine from a terminal. I wondered how the designers could use electronics to control mechanics. This Blog I will explore answering that question.
{% include JB/setup %}
A [control system](http://en.wikipedia.org/wiki/Control_system)is a device, or set of devices, that manages, commands, directs or regulates the behavior of other device(s) or system(s).
There are many ways of controlling a system and there are many companies that would like to sell you their system and their software package. This blog will focus on open source hardware and software, and projects that have a good value for the cost of components. 
<section role="debian">
  <font size="6"><b>Debian </b> </font>
  <img src="/img/debian.JPG" style="position: relative; top: 0px; left: 0px;" />
</section>
{% include JB/setup %}
All of my projects will use some sort of interface. In computer science, an [interface](http://en.wikipedia.org/wiki/Interface_%28computing%29),  is the point of interaction with software, or computer hardware, or with peripheral devices such as a computer monitor or a keyboard.  The interface I will use will usually be my laptop. Most input and output will be through my monitor and keyboard. 
My computer is  a simple dual core processor running the Debian operating system. 
<section role="python">
  <font size="6"><b>Python 2.7</b> </font>
  <img src="/img/python.JPG" style="position: relative; top: 0px; left: -10px;" />
</section>
{% include JB/setup %}
Python 2.7 will be the software running most of the control algorithms, and GUI. 
That handles our interface and our controller. Next we need some data ports to communicate with, again there are a lot of ways to handle this but the most common is to go from the USB port of my laptop through a USB to serial converter, cable like this one <img>, that communicates with our subsystems. Next we will need a controller most of the controllers we will use have a serial RX/TX pins, and input output pins, for turning on and off peripherals like motors and relays. 
Then we need the mechanical objects to control, like motors, relays, sensors, ect..
{% include JB/setup %}
My blog posts will cover hardware software and testing. Thanks for stopping by feel free to comment on anything.
Phil 
    
<section role="raspberry_pi">
  <font size="6"><b>RaspberryPi</b> </font>
  <img src="/img/raspberry_pi.JPG" style="position: relative; top: 0px; left: -10px;" />
</section>
This site was made with a RaspberryPi and the Raspbian OS
    
This site uses `ruby gems`, `jekyll`, `html` and is hosted by github.
On your raspberryPi you will have to get ruby and jekyll
    
    sudo apt-get install ruby1.9.1-full
    gem install jekyll.

mkdir your USERNAME.github.com folder in your home directory and not your root directory. I did it in root and had key issues.

<div id="wrapper" style="width:100%; text-align:center">
<img src="/img/palm_pi.JPG" />
</div>
check out my raspberrypi [project log](http://www.raspberrypi.org/phpBB3/viewtopic.php?f=41&t=34300) at the raspberry pi forums. 

## To-Do
This site is still under construction, as I try and figure out how I want it set up.


All of the code for this site is at my [github repository](http://github.com/philwilliammee/philwilliammee.github.com)<br>
Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)



