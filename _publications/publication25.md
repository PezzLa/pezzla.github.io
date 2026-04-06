---
title: "Efficient Bayesian Sampling with Langevin Birth-Death Dynamics"
collection: publications
permalink: /publications/publication25
excerpt: "We study how to speed-up sampling in GW parameter estimation."
date: 2025-09-02
venue: ""
authorlist: "A. Leviyev, **F. Iacovelli**, A. Zimmerman"
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
var recid = '2965908';
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
Sampling in GW parameter estimation can take a long time. We propose and apply to the GW150914 case a Langevin diffusion algorithm augmented with a birth-death process, finding a considerable improvement in the performance. 

### Contribution
I took care of the gravitational wave modeling aspects of the paper, writing the relative part and producing the needed code.

### Abstract
Bayesian inference plays a central role in scientific and engineering applications by enabling principled reasoning under uncertainty. However, sampling from generic probability distributions remains a computationally demanding task. This difficulty is compounded when the distributions are ill-conditioned, multi-modal, or supported on topologically non-Euclidean spaces. Motivated by challenges in gravitational wave parameter estimation, we propose simulating a Langevin diffusion augmented with a birth-death process. The dynamics are rescaled with a simple preconditioner, and generalized to apply to the product spaces of a hypercube and hypertorus. Our method is first-order and embarrassingly parallel with respect to model evaluations, making it well-suited for algorithmic differentiation and modern hardware accelerators. We validate the algorithm on a suite of toy problems and successfully apply it to recover the parameters of GW150914 - the first observed binary black hole merger. This approach addresses key limitations of traditional sampling methods, and introduces a template that can be used to design robust samplers in the future.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2503.00116" target="_blank" rel="noopener">2509.01942 [stat.AP]</a>