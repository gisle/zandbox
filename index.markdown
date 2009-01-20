---
layout: default
title: Gisle's GitHub Sandbox
---

{{page.title}}
==============

This is some sample text.  Does this work out?  Nope.

What about now? Much better for sure.  Now it's almost workable.

Posts
=====

<ul class="posts">
{% for post in site.posts %}
   <li><span>{{ post.date | date_to_string }}</span> <a href="{{post.url }}">{{post.title}}</a></li>
{% endfor %}
</ul>

