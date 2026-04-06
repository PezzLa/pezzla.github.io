---
title: "Cosmology and Astrophysics with Standard Sirens and Galaxy Catalogs in View of Future Gravitational Wave Observations"
collection: publications
permalink: /publications/publication12
excerpt: "We develop a code to perform a joint population and cosmological inference on gravitational-wave data and galaxy catalogs, and apply it to simulated O4 and O5 catalogs of gravitational waves."
date: 2024-03-29
venue: "ApJ 964 191"
authorlist: "N. Borghi, M. Mancarella, M. Moresco, M. Tagliazucchi, **F. Iacovelli**, A. Cimatti, M. Maggiore"
classes: wide
pubtype: "published"
---

<span class="__dimensions_badge_embed__" data-doi="10.3847/1538-4357/ad20eb" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2734729';
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
We develop a public code to carry a joint population and cosmological inference of GW events and galaxy catalogs. We discuss the formalism, validate the code, and apply it to scenarios representatives of the O4 and O5 runs of LIGO-Virgo-KAGRA assuming a complete galaxy catalog with both photometric and spectroscopic redshift measurements, discussing the differences among the outcomes.

### Contribution
I took part in the discussions regarding the theoretical and methodological aspects of the paper as well as in the writing.     

### Abstract
With the growing number of gravitational-wave detections and the advent of large galaxy redshift surveys, a new era in cosmology is unfolding. This study explores the synergies between gravitational waves and galaxy surveys to jointly constrain cosmological and gravitational-wave population parameters. We introduce *CHIMERA*, a novel code for gravitational-wave cosmology combining information from the population properties of compact binary mergers and galaxy catalogs. We study constraints for scenarios representative of LIGO-Virgo-KAGRA O4 and O5 observing runs, assuming to have a complete catalog of potential host galaxies with either spectroscopic or photometric redshift measurements. We find that a percent-level measurement of H<sub>0</sub> could be achieved with the best 100 binary black holes in O5 using a spectroscopic galaxy catalog. In this case, the intrinsic correlation that exists between H<sub>0</sub> and the binary black hole population mass scales is broken. Instead, by using a photometric catalog the accuracy is degraded up to a factor of &sim;9, leaving a significant correlation between H<sub>0</sub> and the mass scales that must be carefully modeled to avoid bias. Interestingly, we find that using spectroscopic redshift measurements in the O4 configuration yields a better constraint on H<sub>0</sub> compared to the O5 configuration with photometric measurements. In view of the wealth of gravitational-wave data that will be available in the future, we argue the importance of obtaining spectroscopic galaxy catalogs to maximize the scientific return of gravitational-wave cosmology.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2312.05302" target="_blank" rel="noopener">2312.05302 [astro-ph.CO]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ad20eb" target="_blank" rel="noopener">10.3847/1538-4357/ad20eb</a>
