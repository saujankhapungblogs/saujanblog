---
layout: default
title: Blogs
permalink: /blog.html
---

<h1>Latest Posts</h1>

<ul>
    {% for i in site.posts %}
    <li>
        <h2><a href="{{site.baseurl}}{{i.url}}">{{i.title}}</a></h2>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>