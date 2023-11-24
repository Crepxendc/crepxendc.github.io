---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# <h1 class="page__title">About Me</h1>

<p>
  I am a Senior undergraduate students in the <a href="https://www.ee.tsinghua.edu.cn/en/">Department of Electronic Engineering</a> at Tsinghua University, where I worked with 
</p>

<p>My research interests are medical imaging, machine learning and AI security. </p>

<hr/>

<h1 class="page__title">Publications</h1>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
