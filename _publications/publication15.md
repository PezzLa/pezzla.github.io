---
title: "Accurate standard siren cosmology with joint gravitational-wave and &gamma;-ray burst observations"
collection: publications
permalink: /publications/publication15
excerpt: "We develop a way to perform unbiased estimations of the expansion rate of the Universe from gravitational-wave + &gamma;-ray burst detections and a new gravitational-wave likelihood approximant."
date: 2024-12-26
venue: "Phys. Rev. Lett. 133, 261001"
authorlist: "M. Mancarella, **F. Iacovelli**, S. Foffa, N. Muttoni, M. Maggiore"
classes: wide
pubtype: "published"
---

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2783222';
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
We show how to get rid of biases in H<sub>0</sub> estimations from GW+GRB detections by including the EM model in the likelihood, and at the same time estimate the GRB jet parameters. We further develop a new GW likelihood approximant which treats the dependence on distance and inclination as exact.

### Contribution
I took part in the development and implementation of the new GW approximant and the inclusion of noise scatter in the measurement, as well as in the reviewing of the hierarchical bayesian likelihood and writing. 

### Abstract
Joint gravitational-wave and &gamma;-ray bursts (GRB) observations are among the best prospects for standard siren cosmology. However, the strong selection effect for the coincident GRB detection, which is possible only for sources with small inclination angles, induces a systematic uncertainty that is currently not accounted for. We show that this severe source of bias can be removed by inferring the *a priori* unknown electromagnetic detection probability directly from multimessenger data. This leads at the same time to an unbiased measurement of the Hubble constant, to constrain the properties of GRB emission, and to accurately measure the viewing angle of each source. Our inference scheme is applicable to real data already in the small-statistics regime, a scenario that might become reality in the near future. Additionally, we introduce a novel likelihood approximant for GW events which treats the dependence on distance and inclination as exact.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2405.02286" target="_blank" rel="noopener">2405.02286 [astro-ph.HE]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://doi.org/10.1103/PhysRevLett.133.261001" target="_blank" rel="noopener">10.1103/PhysRevLett.133.261001</a>