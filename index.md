---
layout: home
---

Hi!

I'm currently a research assistant at [Politecnico di Milano](polimi.it) under the supervision of [Prof. Gianni Antichi](https://gianniantichi.github.io).

My research interests are in the field of computer networks, specifically in the design and implementation of network stacks and protocols for high-performance and low-latency applications.

I hold a Master's degree and a Bachelor's degree in Computer Science from [Politecnico di Milano](https://www.polimi.it/en/) .

My latest work has been porting XDP/AF_XDP zero copy to the [OpenNIC](https://github.com/Xilinx/open-nic-driver) driver. 



## Blog Posts

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small>
        </li>
    {% endfor %}
</ul>