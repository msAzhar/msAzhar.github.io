---
layout: page
permalink: /poetry/
title: postlar
description: Bu postlar çoğunlukla teknik bilgi içermektedir. Arada sırada ingilizce yazılmış postlar da olabilir...:)
---

<ul class="post-list">
{% for poem in site.poetry reversed %}
    <li>
        <h2><a class="poem-title" href="{{ poem.url | prepend: site.baseurl }}">{{ poem.title }}</a></h2>
        <p class="post-meta">{{ poem.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
