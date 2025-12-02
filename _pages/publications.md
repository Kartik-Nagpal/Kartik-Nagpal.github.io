---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  You can find the most up-to-date on my <a href="{{ author.googlescholar }}">Google Scholar <i class="fas fa-fw fa-graduation-cap"></i></a>, but I have primers for some of my most interesting work below.
{% endif %}

---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}

  ---

{% endfor %}
