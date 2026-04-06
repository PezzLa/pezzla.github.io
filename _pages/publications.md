---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

Here you can find a complete list of my publications. Clicking on any of the links below will redirect you to the abstract and details of my contributions to the papers I am not the first author of. A PDF version of my publication list can be downloaded clicking the button below

<center><a href="../assets/cv_pdf/publication_list.pdf" download="Iacovelli_PublicationList.pdf"><button class="btn btn--custom">Publication list</button></a></center>

You can also find my papers on  <a href="https://inspirehep.net/authors/1844718" target="_blank" rel="noopener"><i class="ai ai-inspire ai-fw"></i> iNSPIRE</a>, <a href="https://ui.adsabs.harvard.edu/search/q=%20author%3A%22Iacovelli%2C%20Francesco%22&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" rel="noopener"><i class="ai ai-ads-square ai-fw"></i> NASA/ADS</a>, <a href="https://scholar.google.com/citations?hl=it&user=aTpQvZAAAAAJ" target="_blank" rel="noopener"><i class="ai ai-google-scholar-square ai-fw"></i> Scholar</a> or the <a href="https://arxiv.org/a/iacovelli_f_1.html" target="_blank" rel="noopener"><i class="ai ai-arxiv ai-fw"></i> arXiv</a>.

You can visualize my papers through BibBase [here]({{ site.baseurl }}{% link _pages/publications_bibbase.md %}).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
