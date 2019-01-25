---
layout: layouts/base.njk
title: My meetup is amazing
---


## Is it amazing? I MADE CHANGES!

Yes it is. Look at the different editions!

And I want to stage some changes too. Over here. On this branch.


## Editions
<ul>
{% for edition in collections.editions | reverse %}
{% set item = edition %}
{% include "edition-details.njk" %}
{% endfor %}
</ul>


## Subscribe

Never miss out. You can subscribe to an [RSS feed](/feed.xml) of the meetups.
