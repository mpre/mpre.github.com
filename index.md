---
layout: page
title: Hello World!
tagline: It'a-me, Marco!
---

My name  is Marco Previtali and  I am currently a  collaborator at the
Department  of   Computer  Science   (DISCo)  at  the   University  of
Milan-Bicocca.

I'm   mostly  interested   in   bioinformatics   and  I'm   developing
[https://github.com/AlgoLab/LightStringGraph](LighStringGraph).

You can find my contacts [here](http://mpre.github.io/WhoAmI.html).

## Post list:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
