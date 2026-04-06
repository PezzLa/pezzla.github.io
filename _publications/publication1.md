---
title: "Cosmology with LIGO/Virgo dark sirens: Hubble parameter and modified gravitational wave propagation"
collection: publications
permalink: /publications/publication1
excerpt: "We exploit gravitational-wave detections and a galaxy catalog to obtain constraints on the expansion rate of the Universe and possible deviations from GR at cosmological scales. A public code is also released!"
date: 2021-08-12
venue: 'JCAP08(2021)026'
authorlist: "A. Finke, S. Foffa, **F. Iacovelli**, M. Maggiore, and M. Mancarella"
classes: wide
pubtype: "published"
---
<span class="__dimensions_badge_embed__" data-doi="10.1088/1475-7516/2021/08/026" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '1843987';
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

We correlate the gravitational-wave data in the GWTC-2 catalog and the GLADE galaxy catalog to constrain the Hubble parameter and a parameter quantifying deviations from GR at cosmological scale due to the effect of modified GW propagation. Different methodological aspects are reviewed and extended, and we released a public code. 

### Contribution
This work is part of my Master's thesis, and I contributed to writing parts of the accompanying code, studying in depth and handling the problem of the completeness of galaxy catalogs, as well as producing most of the figures and results.

### Abstract
We present a detailed study of the methodology for correlating `dark sirens' (compact binaries coalescences without electromagnetic counterpart) with galaxy catalogs. We propose several improvements on the current state of the art, and we apply them to the GWTC-2 catalog of LIGO/Virgo gravitational wave (GW) detections, and the GLADE galaxy catalog, performing a detailed study of several sources of systematic errors that, with the expected increase in statistics, will eventually become the dominant limitation. We provide a measurement of H<sub>0</sub> from dark sirens alone, finding as the best result H<sub>0</sub> = 67.3<sup>+27.6</sup><sub>-17.9</sub> km s<sup>-1</sup> Mpc<sup>-1</sup> (68% c.l.) which is, currently, the most stringent constraint obtained using only dark sirens. Combining dark sirens with the counterpart for GW170817 we find H<sub>0</sub> = 72.2<sup>+13.9</sup><sub>-7.5</sub> km s<sup>-1</sup> Mpc<sup>-1</sup>. We also study modified GW propagation, which is a smoking gun of dark energy and modifications of gravity at cosmological scales, and we show that current observations of dark sirens already start to provide interesting limits. From dark sirens alone, our best result for the parameter &Xi;<sub>0</sub> that measures deviations from GR (with &Xi;<sub>0</sub> = 1 in GR) is &Xi;<sub>0</sub> = 2.1<sup>+3.2</sup><sub>-1.2</sub>. We finally discuss limits on modified GW propagation under the tentative identification of the flare ZTF19abanrhr as the electromagnetic counterpart of the binary black hole coalescence GW190521, in which case our most stringent result is &Xi;<sub>0</sub> = 1.8<sup>+0.9</sup><sub>-0.6</sub>. We release the publicly available code *DarkSirensStat*, which is available under open source license at
<a href="https://github.com/CosmoStatGW/DarkSirensStat" target="_blank" rel="noopener">https://github.com/CosmoStatGW/DarkSirensStat</a>.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2101.12660" target="_blank" rel="noopener">2101.12660 [astro-ph.CO]</a>

<i class="ai ai-doi ai-fw"></i> Publisher DOI: <a href="https://iopscience.iop.org/article/10.1088/1475-7516/2021/08/026" target="_blank" rel="noopener">10.1088/1475-7516/2021/08/026</a>
