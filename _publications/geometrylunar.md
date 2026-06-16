---
title: "The geometry of lunar gravitational wave detection"
collection: publications
permalink: /publications/geometry_lunar
excerpt: "We show that inference for long-duration GW signals is a geometric problem"
date: 2026-06-03
venue: ''
authorlist: "J. Tissino, F. Santoliquido, F. Iacovelli, U. Dupletsa, T. Dal Canton, M. Ballelli, A. Chopra, L. E. Espinosa Castro, **L. Pezzella**, M. Schulz, I. Takimoto Schmiegelow and J. Harms"
classes: wide
pubtype: "arXiv"
---
<span class="__dimensions_badge_embed__" data-doi="10.48550/arXiv.2606.04918" data-style="small_circle" data-hide-zero-citations="true"></span><script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '3165058';
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

We show that the precision and efficiency of parameter estimation for long-duration GW signals in the deci-Hertz band are fundamentally linked to the geometry of the detection. We inject GW250114 as a case study and compare the results in LGWA with the Einstein Telescope in two of its proposed configurations. 


### Abstract
The Lunar Gravitational Wave Antenna (LGWA) is a planned gravitational wave detector on the Moon, targeting the deci-Hertz band and expected to deliver breakthrough discoveries across several science cases, including the Moon's interior structure and astrophysics. In this work, we show that adopting a frame comoving with the Solar System barycenter (SSB), but with its origin at a location that minimizes timing uncertainty, reduces the sampling time by an order of magnitude. We present a systematic post-processing procedure to identify the optimal origin within the Solar System for any given signal. We explore alternative timing parametrizations beyond the merger time, and find that they have only a minor impact on parameter uncertainties. Using the stellar-mass black hole binary GW250114 as a case study, we illustrate how these geometrical considerations translate into improved parameter constraints. Two minutes before its merger, the LGWA would have measured its chirp mass to a precision of 0.0002 solar masses (90% symmetric) and constrained its sky position to within 65 square degrees (90% HPD area); these constraints are tighter than those obtained by the LIGO-Virgo-KAGRA (LVK) detectors, despite a lower signal-to-noise ratio. We connect our results to an analytical approximation proposed by Wen and Chen, which relates the area spanned by the orbital motion of a detector to its efficacy in constraining the sky position of a source. We verify its qualitative validity for compact binary sources with a series of injections, identifying the regimes in which its underlying assumptions break down. Our results demonstrate that inference for long-duration GW signals with the LGWA must be treated as a geometrical problem, in which detector motion, reference-frame choice, and signal evolution jointly determine both parameter constraints and computational efficiency.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="arxiv.org/abs/2606.04918" target="_blank" rel="noopener">2606.04918 [gr-qc]</a>
