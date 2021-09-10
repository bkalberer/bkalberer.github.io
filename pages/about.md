---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi! My name is **{{ site.author.name }}** :wave:,<br>
Welcome to my personal homepage. See below for some information about me and where I've been.

<div class="row">
{% include about/skills.html title="Industry Skills" source=site.data.industry-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
