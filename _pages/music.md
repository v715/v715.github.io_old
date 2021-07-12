---
layout: page
title: Music
permalink: /music/
description: a cappella, a cappella, a cappella

news: true
---

{% for project in site.projects %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.link }}">
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        </a>
    </div>
</div>

{% endfor %}

For the past 4 years, I've had the privelege of being a member of [The AllNighters](https://www.jhuallnighters.com/),
Johns Hopkins University's best-smelling all-male a cappella group.

{% if page.news %} {% include news.html %} {% endif %}
