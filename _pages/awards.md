---
layout: archive
title: "Awards"
permalink: /awards/
author_profile: true
---

{% include base_path %}

<ul class="award-list">
{% for post in site.awards reversed %}
    {% include archive-single-award.html %}
{% endfor %}
</ul>
