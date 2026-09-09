---
layout: archive
title: "📝 Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% assign publications = site.data.publications | sort: "year" | reverse %}
{% assign publications_by_year = publications | group_by: "year" %}

<div class="publication-list">
{% for year in publications_by_year %}
  <h2 class="publication-list__year">{{ year.name }}</h2>
  <ul class="publication-list__items">
  {% for publication in year.items %}
    <li class="publication-list__item">
      <a class="publication-list__title" href="{{ publication.url }}">{{ publication.title }}</a>{% if publication.authors %},
      <span class="publication-list__authors">{% for author in publication.authors %}{% if author == "Jiali You" or author == "游佳莉" %}<strong>{{ author }}</strong>{% else %}{{ author }}{% endif %}{% unless forloop.last %}, {% endunless %}{% endfor %}</span>{% endif %}{% if publication.venue %},
      <strong>{{ publication.venue }}</strong>{% endif %} <strong>{{ publication.year }}</strong>{% if publication.codeurl %}
      <a class="publication-list__code" href="{{ publication.codeurl }}">[code]</a>{% endif %}
    </li>
  {% endfor %}
  </ul>
{% endfor %}
</div>
