---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

Here you will find a complete list of my publications (as soon as I complete the website!).



You can also find my papers on  <a href="https://inspirehep.net/authors/2863689" target="_blank" rel="noopener"><i class="ai ai-inspire ai-fw"></i> iNSPIRE</a>, <a href="https://ui.adsabs.harvard.edu/search/q=author%3A%22Pezzella%2C%20Laura%22&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" rel="noopener"><i class="ai ai-ads-square ai-fw"></i> NASA/ADS</a>,  <a href="https://arxiv.org/a/pezzella_l_1.html" target="_blank" rel="noopener"><i class="ai ai-arxiv ai-fw"></i> arXiv</a>
.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
