---
title: "*GWFAST*: A Fisher Information Matrix Python Code for third-generation gravitational-wave detectors"
collection: publications
permalink: /publications/publication4
excerpt: "We release, review, and validate the *GWFAST* code!"
date: 2022-10-21
venue: 'ApJS 263 2'
authorlist: "**F. Iacovelli**, M. Mancarella, S. Foffa, M. Maggiore"
classes: wide
pubtype: "published"
---

<span class="__dimensions_badge_embed__" data-doi="10.3847/1538-4365/ac9129" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2112457';
var recurl = 'https://inspirehep.net/api/literature/?q=recid%3A'+recid+'&size=10&page=1&fields=citation_count&format=json';

if (recid === "undefined") {
	document.getElementById("inspirecount").innerHTML='';
} else {
	$.getJSON(recurl, function(data){
    	var html =`<a href="https://inspirehep.net/literature/${recid}" target="_blank" rel="noopener"><button type="button inspire" class="btn btn-inspire">iNSPIRE </button></a><span class="badge inspcitations">${data.hits.hits[0].metadata.citation_count} citations</span>`    
    	document.getElementById("inspirecount").innerHTML= html
  });
}
</script>
</body>
</html>

### Summary
We release, review, and validate the *GWFAST* code, a tool to efficiently forecast the capabilities of third-generation gravitational-wave detectors to observe compact binary mergers. 

### Abstract
We introduce *GWFAST* <a href="https://github.com/CosmoStatGW/gwfast" target="_blank" rel="noopener">(https://github.com/CosmoStatGW/gwfast)</a>, a Fisher information matrix *Python* code that allows for easy and efficient estimation of signal-to-noise ratios and parameter measurement errors for large catalogs of resolved sources observed by networks of gravitational-wave (GW) detectors. In particular, *GWFAST* includes the effects of the Earth's motion during the evolution of the signal, supports parallel computation, and relies on automatic differentiation rather than on finite differences techniques, which makes possible the computation of derivatives with accuracy close to machine precision. We also release the library *WF4Py* <a href="https://github.com/CosmoStatGW/WF4Py" target="_blank" rel="noopener">(https://github.com/CosmoStatGW/WF4Py)</a> implementing state-of-the-art GW waveforms in *Python*. In this paper we provide a documentation of *GWFAST* and *WF4Py* with practical examples and tests of performance and reliability. In the companion paper [Iacovelli et al.]({{ site.baseurl }}{% link _publications/publication5.md %}) we present forecasts for the detection capabilities of the second and third generation of ground-based GW detectors, obtained with *GWFAST*.
<a href="https://github.com/CosmoStatGW/WF4Py". 

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2207.06910" target="_blank" rel="noopener">(https://github.com/CosmoStatGW/gwfast)</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://iopscience.iop.org/article/10.3847/1538-4365/ac9129" target="_blank" rel="noopener">10.3847/1538-4365/ac9129</a>