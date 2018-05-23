---
layout: page
title: About
description: 此心不动，随机而动。
keywords: 产品, 危化品管理, 流程, 物联网
comments: true
menu: 关于
permalink: /about/
---

此心不动，随机而动。

产品, 危化品管理, 流程, 物联网

厚德载物，自强不息！

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
