---
layout: page
permalink: /repositories/
title: repositories
description: Edit the `_data/repositories.yml` and change the `NeerphuNepga` and `github_repos` lists to include your own GitHub profile and repositories.
nav: true
nav_order: 4
---

{% if site.data.repositories.NeerphuNepga %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.NeerphuNepga %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.NeerphuNepga %}
{% if site.data.repositories.NeerphuNepga.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.NerphuNepga %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.NerphuNepga %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
