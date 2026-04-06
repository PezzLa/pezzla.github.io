---
title: "Confusion noise from astrophysical backgrounds at third-generation gravitational-wave detector networks"
collection: publications
permalink: /publications/publication19
excerpt: "We compute the impact of astrophysical “confusion noise” in the search for cosmological gravitational-wave backgrounds."
date: 2024-11-06
venue: "Phys. Rev. D 112, 083007"
authorlist: "E. Belgacem, **F. Iacovelli**, M. Maggiore, M. Mancarella, N. Muttoni"
classes: wide
pubtype: "published"
---

<span class="__dimensions_badge_embed__" data-doi="10.1103/mr25-ftqd" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2846160';
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
We show how to characterize the “confusion noise” due to astrophysical CBC sources in the search for cosmological GW backgrounds. We obtain search-independent upper bounds on its effect, and evaluate its impact on given cosmological searches, at a 3G network comprising ET and CE.

### Contribution
I contributed to the theoretical development of the paper, the writing and produced most of the numerical results.

### Abstract
At third-generation (3G) gravitational-wave detector networks, compact binaries coalescences produce a “confusion noise” due to unresolved sources and to the error in the reconstruction of resolved sources, that can degrade the sensitivity to cosmological backgrounds. We show how to characterize from first-principles this astrophysical confusion noise by reconstructing the resolved sources at a detector network, subtracting them from the data stream of each detector of the network, and then computing the correlation among detector pairs of these “partially cleaned” data streams that, beside instrumental noise, contain the unresolved sources and the error on the resolved sources. In a two-detector correlation, this residual astrophysical background then acts as an effective correlated noise. We point out that its effect, in the search for a cosmological background, must be evaluated by correlating two detectors with the filter function that optimizes the given cosmological search (and not the search for the astrophysical background itself) and therefore depends on the specific cosmological signal that we want to extract from the data. We show how to obtain search-independent upper bounds on the effect of this astrophysical confusion noise, and how to characterize its actual effect on a given cosmological search. We then apply this methodology to an example of a 3G network and, for a realistic population of mergers, we evaluate explicitly the upper bound on the effect of the astrophysical confusion noise, as well as its actual effect in the search of selected examples of power-law cosmological backgrounds and of backgrounds featuring broad peaks, as in phase transitions.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2411.04029" target="_blank" rel="noopener">2411.04029 [gr-qc]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://doi.org/10.1103/mr25-ftqd" target="_blank" rel="noopener">10.1103/mr25-ftqd</a>