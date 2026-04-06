---
title: "Systematic biases from the exclusion of higher harmonics in parameter estimation on LISA binaries"
collection: publications
permalink: /publications/publication21
excerpt: "We assess the impact of an insufficient higher-order mode content in waveform templates on the parameter estimation of LISA massive BH binary systems."
date: 2025-02-17
venue: "Phys. Rev. D"
authorlist: "S. Yi, **F. Iacovelli**,  S. Marsat, D. Wadekar, E. Berti"
classes: wide
pubtype: "arXiv"
---

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '2890902';
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
We characterize the impact of a limited number of higher-order modes in waveform templates on the parameter estimation of massive black hole binaries observed by LISA. We perform both Bayesian analyses and introduce a novel methodology to infer biases via a cheap direct likelihood optimization. We find that biases can be severe even for binaries at high redshift.

### Contribution
I contributed to the conceptual development of the paper, the writing and the production and validation of the novel analysis tools.

### Abstract
The remarkable sensitivity achieved by the planned Laser Interferometer Space Antenna (LISA) will allow us to observe gravitational-wave signals from the mergers of massive black hole binaries (MBHBs) with signal-to-noise ratio (SNR) in the hundreds, or even thousands. At such high SNR, our ability to precisely infer the parameters of an MBHB from the detected signal will be limited by the accuracy of the waveform templates we use. In this paper, we explore the systematic biases that arise in parameter estimation if we use waveform templates that do not model radiation in higher-order multipoles. This is an important consideration for the large fraction of high-mass events expected to be observed with LISA. We examine how the biases change for MBHB events with different total masses, mass ratios, and inclination angles. We find that systematic biases due to insufficient mode content are severe for events with total redshifted mass &gtrsim;10<sup>6</sup> M<sub>&odot;</sub>. We then compare several methods of predicting such systematic biases without performing a full Bayesian parameter estimation. In particular, we show that through direct likelihood optimization it is possible to predict systematic biases with remarkable computational efficiency and accuracy. Finally, we devise a method to construct approximate waveforms including angular multipoles with &ell; &geq; 5 to better understand how many additional modes (beyond the ones available in current approximants) might be required to perform unbiased parameter estimation on the MBHB signals detected by LISA.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2502.12237" target="_blank" rel="noopener">2502.12237 [gr-qc]</a>