---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I'm a software engineer living in Nairobi, Kenya. I make applications usually with Python/Django and Angular,love programming,reading anything about tech,traveling and listening to good music ;). I help build solutions for Nouveta, a company that provides channels such as SMS, USSD, app & web that businesses use to engage their customers enable payments across the channels.

For more info, check out my projects and photos..

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>