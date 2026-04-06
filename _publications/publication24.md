---
title: "The Science of the Einstein Telescope"
collection: publications
permalink: /publications/publication24
excerpt: "We present an exhaustive discussion of the scientific propsects of ET."
date: 2025-03-15
venue: 'JCAP'
authorlist: "A. Abac, et al. (incl. **F. Iacovelli**)"
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
var recid = '2901213';
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
ET has the potential of triggering revolutions in Astrophysics, Fundamental Physics and Cosmology. We here present a comprehensive discussion of its science objectives and highlight outstanding potential.

### Contribution
I took part in the development of various sections of the work, producing several results. In particular, I contribute to the Cosmology, Multi-messenger Astrophysics, Synergies with other observatories, and Common Tools sections.

### Abstract
Einstein Telescope (ET) is the European project for a gravitational-wave (GW) observatory of third-generation. In this paper we present a comprehensive discussion of its science objectives, providing state-of-the-art predictions for the capabilities of ET in both geometries currently under consideration, a single-site triangular configuration or two L-shaped detectors. We discuss the impact that ET will have on domains as broad and diverse as fundamental physics, cosmology, early Universe, astrophysics of compact objects, physics of matter in extreme conditions, and dynamics of stellar collapse. We discuss how the study of extreme astrophysical events will be enhanced by multi-messenger observations. We highlight the ET synergies with ground-based and space-borne GW observatories, including multi-band investigations of the same sources, improved parameter estimation, and complementary information on astrophysical or cosmological mechanisms obtained combining observations from different frequency bands. We present advancements in waveform modeling dedicated to third-generation observatories, along with open tools developed within the ET Collaboration for assessing the scientific potentials of different detector configurations. We finally discuss the data analysis challenges posed by third-generation observatories, which will enable access to large populations of sources and provide unprecedented precision.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2303.15923" target="_blank" rel="noopener">2503.12263 [gr-qc]</a>