---
title: "Classifying binary black holes from Population III stars with the Einstein Telescope: a machine-learning approach"
collection: publications
permalink: /publications/publication14
excerpt: "We study the prospects of classifying binary black holes originating from Population III stars observed through gravitational waves at the Einstein Telescope using machine learning."
date: 2024-10-22
venue: "A&A 690, A362"
authorlist: "F. Santoliquido, U. Dupletsa, J. Tissino, M. Branchesi, **F. Iacovelli**, G. Iorio, M. Mapelli, D. Gerosa, J. Harms, M. Pasquato"
classes: wide
pubtype: "published"
---

<span class="__dimensions_badge_embed__" data-doi="10.1051/0004-6361/202450381" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2777991';
var recurl = 'https://inspirehep.net/api/literature/?q=recid%3A'+recid+'&size=10&page=1&fields=citation_count&format=json';

if (recid === "undefined") {
	document.getElementById("inspirecount").innerHTML='';
} else {
	$.getJSON(recurl, function(data){
		if (data.hits.hits[0].metadata.citation_count === 0){
			var html = '';
		} else {
    	var html =`<a href="https://inspirehep.net/literature/${recid}" target="_blank" rel="noopener"><button type="button inspire" class="btn btn-inspire">iNSPIRE </button></a><span class="badge inspcitations">${data.hits.hits[0].metadata.citation_count} citations</span>`  
    	}  
    	document.getElementById("inspirecount").innerHTML= html
  });
}
</script>
</body>
</html>

### Summary
We study the prospects of using machine learning classifiers to assess the origin of binary black hole mergers observed at the Einstein Telescope, with a focus on disentangling objects originating from Population III and Population I-II stars.

### Contribution
I participated in the writing of some parts of the work as well as in discussions regarding the set-up of the analysis and helped perform some initial checks among *GWFish* and *gwfast*. 

### Abstract
Third-generation (3G) gravitational-wave (GW) detectors like the Einstein Telescope (ET) will observe binary black hole (BBH) mergers at redshifts up to z&sim;100.
However, unequivocal determination of the origin of high-redshift sources will remain uncertain, due to the low signal-to-noise ratio (SNR) and poor estimate of their luminosity distance. This study proposes a machine learning approach to infer the origins of high-redshift BBHs, specifically differentiating those arising from Population III (Pop. III) stars &ndash; likely the first progenitors of stellar-born BBH mergers in the Universe &ndash; and those originated from Population I-II (Pop. I-II) stars. We have considered a wide range of state-of-the-art models encompassing current uncertainties on Pop. III BBH mergers. We then estimate parameter errors of detected sources with ET using the Fisher-information-matrix formalism, followed by classification using *XGBoost*, a machine learning algorithm based on decision trees. For a set of mock observed BBHs, we provide the probability that they belong to the Pop. III class while considering the parameter errors of each source. In our fiducial model, we accurately identify &sim;10% of detected BBHs originating from Pop. III stars with >90% precision. Our study demonstrates how machine learning enables to achieve some pivotal aspects of ET science case by exploring the origin of individual high-redshift GW observations. We set the basis for further studies, which will integrate additional  simulated populations and account for population modeling uncertainties.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2404.10048" target="_blank" rel="noopener">2404.10048 [astro-ph.HE]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://doi.org/10.1051/0004-6361/202450381" target="_blank" rel="noopener">10.1051/0004-6361/202450381</a>