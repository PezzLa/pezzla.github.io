---
title: "Forecasting the detection capabilities of third-generation gravitational-wave detectors using *GWFAST*"
collection: publications
permalink: /publications/publication5
excerpt: "Up-to-date forecasts of the capabilities of Einstein Telescope and Cosmic Explorer to observe compact binary mergers."
date: 2022-12-27
venue: 'ApJ 941 208'
authorlist: "**F. Iacovelli**, M. Mancarella, S. Foffa, M. Maggiore"
classes: wide
pubtype: "published"
---

<span class="__dimensions_badge_embed__" data-doi="10.3847/1538-4357/ac9cd4" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2106524';
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
We review the theoretical aspects behind the *GWFAST* code and produce state-of-the-art forecasts for the capabilities of ET and CE to observe BBH, BNS, and NSBH mergers.

### Abstract
We introduce *GWFAST*, a novel Fisher-matrix code for gravitational-wave studies, tuned toward third-generation gravitational-wave detectors such as Einstein Telescope (ET) and Cosmic Explorer (CE). We use it to perform a comprehensive study of the capabilities of ET alone, and of a network made by ET and two CE detectors, as well as to provide forecasts for the forthcoming O4 run of the LIGO-Virgo-KAGRA (LVK) collaboration. We consider binary neutron stars, binary black holes, and neutron star–black hole binaries, and compute basic metrics such as the distribution of signal-to-noise ratio (SNR), the accuracy in the reconstruction of various parameters (including distance, sky localization, masses, spins, and, for neutron stars, tidal deformabilities), and the redshift distribution of the detections for different thresholds in S/N and different levels of accuracy in localization and distance measurement. We examine the expected distribution and properties of golden events, with especially large values of the S/N. We also pay special attention to the dependence of the results on astrophysical uncertainties and on various technical details (such as choice of waveforms, or the threshold in SNR), and we compare with other Fisher codes in the literature. In the companion paper Iacovelli et al., we discuss the technical aspects of the code. Together with this paper, we publicly release the code *GWFAST*, <a href="https://github.com/CosmoStatGW/gwfast" target="_blank" rel="noopener">(https://github.com/CosmoStatGW/gwfast)</a> and the library *WF4Py* <a href="https://github.com/CosmoStatGW/WF4Py" target="_blank" rel="noopener">(https://github.com/CosmoStatGW/WF4Py)</a> implementing state-of-the-art gravitational-wave waveforms in pure *Python*.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2207.02771" target="_blank" rel="noopener">2207.02771 [gr-qc]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ac9cd4" target="_blank" rel="noopener">10.3847/1538-4357/ac9cd4</a>
