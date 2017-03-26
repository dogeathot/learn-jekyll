---
layout: post
title:  "Obrázky - Albert Hofmann a LSD"
date:   2017-03-26 114:09:48 +0100
tags: 
    - lsd
    - data
---

This is just another post. See how to include data inside your posts:

## Beatles Discography

<ul>
{% for album in site.data.beatles %}
    <li><b>{{ album.Name }}</b> (released on {{ album.Released }})</li>
{% endfor %}
</ul>
