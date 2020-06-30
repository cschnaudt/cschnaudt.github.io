---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---


{% include base_path %}

A [list](http://cschnaudt.github.io/files/sitemap.xml) of all pages found on the site. There is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
