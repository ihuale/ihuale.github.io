---
layout: page
title: About
description: 个人博客，记录栈
keywords: ihuale
comments: true
menu: 关于
permalink: /about/
---
菜鸡语录：不怕变秃，就怕秃了还没变强

## Skill Keywords

{% for skill in site.data.skills %}

<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
