---
layout: page
permalink: /contests/
title: Contests
description: >
nav: false
nav_order: 5
---

Detailed analysis and walkthroughs of coding contests from Codeforces.

## Codeforces

{% include codeforces_rating.liquid %}

### Division 1

<ul>
    {% for contest in site.contests reversed %}
    {% if contest.division == 1 %}
    <li>
        <a href="{{ contest.url | relative_url }}">
            {{ contest.title }}
        </a>
    </li>
    {% endif %}
    {% endfor %}
</ul>

---

### Division 2

<ul>
    {% for contest in site.contests reversed %}
    {% if contest.division == 2 %}
    <li>
        <a href="{{ contest.url | relative_url }}">
            {{ contest.title }}
        </a>
    </li>
    {% endif %}
    {% endfor %}
</ul>

---

### Division 3

<ul>
    {% for contest in site.contests reversed %}
    {% if contest.division == 3 %}
    <li>
        <a href="{{ contest.url | relative_url }}">
            {{ contest.title }}
        </a>
    </li>
    {% endif %}
    {% endfor %}
</ul>

---

### Division 4

<ul>
    {% for contest in site.contests reversed %}
    {% if contest.division == 4 %}
    <li>
        <a href="{{ contest.url | relative_url }}">
            {{ contest.title }}
        </a>
    </li>
    {% endif %}
    {% endfor %}
</ul>
