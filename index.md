---
layout: default
title: Learn Paractice Change!
tagline: Supporting tagline
---
{% include JB/setup %}

    {%for post in site.posts %}
    {{ post.date | date_tp_string }} >> {{ posts.titile }}
    {% endfor %}
