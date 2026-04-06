---
title: "Comparison of global networks of third-generation gravitational-wave detectors"
collection: publications
permalink: /publications/publication20
excerpt: "We examine the scientific potential of different ET designs in combination with CE."
date: 2024-11-08
venue: "Class. Quantum Grav."
authorlist: "M. Maggiore, **F. Iacovelli**, E. Belgacem, M. Mancarella, N. Muttoni"
classes: wide
pubtype: "toAppear"
---

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2846772';
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
We compare on several sensible metrics the performance of ET, both as a triangle, 2 L-shaped instruments and a single L-shaped detector, in combination with CE.

### Contribution
I produced most of the numerical results and plots.

### Abstract
We study the performances of a world-wide network made by a European third-generation gravitational-wave (GW) detector, together with a 40-km Cosmic Explorer detector in the US, considering three scenarios for the European detector: (1) Einstein Telescope (ET) in its 10-km triangle configuration; (2) ET in its configuration featuring two 15-km L-shaped detectors in different sites, still taken to have all other ET characteristics (underground, and with each detector made of a high-frequency interferometer and a cryogenic low-frequency interferometer); (3) A single L-shaped underground interferometer with the ET amplitude spectral density, either with 15 km or with 20 km arm length. Overall, we find that, if a 2L configuration should be retained for ET, the network made by a single-L European underground detector together with CE-40km could already provide a very interesting intermediate step toward the construction of a full 2L+CE network, and is in any case superior to a 10-km triangle not inserted in an international network.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2411.05754" target="_blank" rel="noopener">2411.05754 [gr-qc]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://doi.org/10.1088/1361-6382/ae110b" target="_blank" rel="noopener"> 10.1088/1361-6382/ae110b</a>