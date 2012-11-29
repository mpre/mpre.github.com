---
layout: page
title: Hello World!
tagline: It'a-me, Marco!
---

Hi folks! My name is Marco Previtali and I am a student at
[Università degli studi di Milano-Bicocca](http://www.disco.unimib.it) currently
pursuing my Master degree in computer science.

I am currently working on my thesis which title is "Algoritmi per la predizione
di eventi di splicing alternativo da dati NGS" (*Algorithms for predicting
alternative splicing's events on NGS data*).  My favourite fields of CS are
algorithm design, bioinformatics and AI and my accademic career as a student
includes various class ranging from computer architecture to soft computing. My
Post-graduate course was mainly focused on software development (Test &
Analysis, development process such as agile methodology and so on),
Algorithms and models (AI, Complex Systems, bioinformatics, soft computing).

As I stated before, I am mainly interested in methods used to solve _hard_
problems in a smart way.

You can find my contacts [here](http://mpre.github.com/WhoAmI.html).

## Post list:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
