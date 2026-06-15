---
layout: page
title: Group
permalink: /group/
---

{% assign active_members = site.members | where: "active", true %}
{% if active_members.size > 0 %}
## Current Members

{% for member in active_members %}
**[{{ member.title }}]({{ member.url | relative_url }})** — {{ member.role }}
{% endfor %}
{% endif %}

{% assign former_members = site.members | where: "active", false %}
{% if former_members.size > 0 %}
## Former Members

{% for member in former_members %}
**[{{ member.title }}]({{ member.url | relative_url }})** — {{ member.role }}{% if member.period %} ({{ member.period }}){% endif %}
{% endfor %}
{% endif %}
