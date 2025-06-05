---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "Home"
permalink : /
---

Currently I am Research Assistant at Politecnico Di Milano, under the supervision of [Prof. Gianni Antichi](https://gianniantichi.github.io).

My research interests include End-Host Networking, Operating Systems, Network Protocols and Hardware Acceleration.


# home

<ul>
{% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>