---
permalink: /publications/
title: "Publications"
excerpt: "Full publication list"
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

A complete, filterable list of my publications, pulled automatically from [Google Scholar]({{ site.author.googlescholar }}).

<div class="publication-filter" id="publication-year-filter" aria-label="Filter publications by year"></div>
<div class="publication-list" id="google-scholar-publications">
  <p>Loading publications from Google Scholar...</p>
</div>
