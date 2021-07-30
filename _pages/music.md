---
layout: page
title: Music
permalink: /music/
description: a cappella, a cappella, a cappella
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

### Arrangements

| Song                   | OPB             | Arrangers                                                          | Semester   |
| ---------------------- | --------------- | ------------------------------------------------------------------ | ---------- |
| Hold On                | Justin Bieber   | Vivek Gopalakrishnan                                               | Spring '21 |
| New York New York      | Frank Sinatra   | Vivek Gopalakrishnan, Sebastian Durfee, Will McBride, Lucas Polack | Spring '21 |
| Green Light            | Lorde           | Lucas Polack, Vivek Gopalakrishnan                                 | Spring '21 |
| Palace                 | Sam Smith       | Vivek Gopalakrishnan                                               | Fall '20   |
| Try                    | Lawrence        | Vivek Gopalakrishnan                                               | Fall '19   |
| We Find Love           | Daniel Caeser   | Vivek Gopalakrishnan                                               | Fall '19   |
| Broke                  | Samm Henshaw    | Lucas Polack, Vivek Gopalakrishnan                                 | Fall '19   |
| Birds of a Feather     | Vulfpeck        | Vivek Gopalakrishnan                                               | Spring '19 |
| The Night We Met       | Lord Huron      | Lucas Polack, Vivek Gopalakrishnan                                 | Spring '19 |
| Silvertongue           | Young the Giant | Tim Jones, Vivek Gopalakrishnan, Sebastian Durfee                  | Spring '19 |
| The Only Thing         | Sufjan Stevens  | Vivek Gopalakrishnan, Tim Jones                                    | Fall '18   |
| Circus                 | Brittany Spears | Vivek Gopalakrishnan                                               | Fall '18   |
| Somebody to Love       | Quenn           | Vivek Gopalakrishnan                                               | Fall '18   |
| Bring It On Home to Me | Sam Cooke       | Vivek Gopalakrishnan                                               | Spring '18 |
| River                  | Bishop Briggs   | Vivek Gopalakrishnan                                               | Fall '17   |
