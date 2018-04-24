---
layout: page
title: Leistungen
permalink: /leistungen/
page-title: Leistungen
---

<div class="row collapse">
{% for item in site.data.img-grid %}
<div class="large-8 medium-12 small-24 columns">
<div class="overview-image">
<a href="{{ site.baseurl }}{{ item.path }}"><img src="{{ site.baseurl }}/assets/images/{{ item.img }}" alt=" {{ item.name }} "></a>
<div class="overview-desc"><a href="{{ site.baseurl }}{{ item.path }}"><span>{{ item.name }}</span></a></div>
</div>
</div>
{% endfor %}
</div>