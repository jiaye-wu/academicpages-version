---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Full list of my research: <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>

{% endif %}

Statistics: 
<a href='https://scholar.google.com/citations?user=D2n8tswAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjiaye-wu%2FGoogleScholarCrawler-4-GitHubPages@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> 
<a href='https://scholar.google.com/citations?user=D2n8tswAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjiaye-wu%2FGoogleScholarCrawler-4-GitHubPages@google-scholar-stats%2Fgs_data_hindex.json&labelColor=f6f6f6&color=9cf&style=flat&label=h-index"></a> 
<a href='https://scholar.google.com/citations?user=D2n8tswAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjiaye-wu%2FGoogleScholarCrawler-4-GitHubPages@google-scholar-stats%2Fgs_data_i10.json&labelColor=f6f6f6&color=9cf&style=flat&label=i10-index"></a>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
