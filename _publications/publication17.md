---
title: "Forecasting the population properties of merging black holes"
collection: publications
permalink: /publications/publication17
excerpt: "We develop a Fisher tool for forecasts on population analyses at third-generation detectors."
date: 2025-02-18
venue: "Phys. Rev. D 111, 044048"
authorlist: "V. De Renzis, **F. Iacovelli**, D. Gerosa, M. Mancarella, C. Pacilio"
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
var recid = '2842196';
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
We implement the formalism derived by Gair *et al.* [<a href="https://doi.org/10.1093/mnras/stac3560" target="_blank" rel="noopener">MNRAS 519, 2736 (2023)</a>] to realistic populations of binary black holes and produce forecasts for the constraints attainable on population parameters at third-generation detectors.

### Contribution
I had a major role in the theoretical development and writing of the paper, and in developing the associated code.

### Abstract
Third-generation gravitational-wave detectors will observe up to millions of merging binary black holes. With such a vast dataset, stacking events into population analyses will arguably be more important than analyzing single sources. We present the first application of population-level Fisher-matrix forecasts tailored to third-generation gravitational-wave interferometers. We implement the formalism first derived by Gair *et al.* [<a href="https://doi.org/10.1093/mnras/stac3560" target="_blank" rel="noopener">MNRAS 519, 2736 (2023)</a>] and explore how future experiments such as Einstein Telescope and Cosmic Explorer will constrain the distributions of black-hole masses, spins, and redshift. Third-generation detectors will be transformative, improving constraints on the population hyperparameters by several orders of magnitude compared to current data. At the same time, we highlight that a single third-generation observatory and a network of detectors will deliver qualitatively similar performances. Obtaining precise measurements of some population features (e.g. peaks in the mass spectrum) will require only a few months of observations while others (e.g. the fraction of binaries with aligned spins) will instead require years if not decades. We argue population forecasts of this kind should be featured in white papers and feasibility studies aimed at developing the science case of future gravitational-wave interferometers. 


### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2410.17325" target="_blank" rel="noopener">2410.17325 [astro-ph.HE]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://doi.org/10.1103/PhysRevD.111.044048" target="_blank" rel="noopener">10.1103/PhysRevD.111.044048</a>