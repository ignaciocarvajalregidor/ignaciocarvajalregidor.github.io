---
layout: single
title: title.bio
classes:
  - landing
  - dark-theme
author_profile: true
---

{% translate_file about/about.md %}
<!-- testing translate title.bio and spanish/english links

{% translate title.bio %}

{% if site.lang == "es" %}
  {% capture link1 %}{{ site.baseurl_root }}{{ page.url}}{% endcapture %}
   <a href="{{ link1 }}" >{% t global.english %}</a>
{% elsif site.lang == "en" %}
  {% capture link2 %}{{ site.baseurl_root }}/es{{ page.url  }}{% endcapture %}
  <a href="{{ link2 }}" >{% t global.spanish %}</a> and page title is {{ page.title  }} 
{% endif %}		 -->

.