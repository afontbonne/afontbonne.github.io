---
permalink: /researchprojects/
title: "Research projects"
author_profile: true
redirect_from: 
  - "/researchprojects/"
  - "/researchprojects.html"
---

My research is in the field of optical design and joint optical/digital processing design. It can be separate into two global research projects. 

Joint optical/digital processing design 
======

Today, most imaging systems consist of an optical system and digital processing. For the imaging system to be optimal (while respecting weight and power constraints), these two elements must be optimized at the same time. However, for these two parts of the imaging system to be jointly optimized, it is necessary to develop and use dedicated software, such as a differentiable ray tracer. In this way, the imaging characteristics (point spread function) taken into account in the digital processing are linked to the derivatives of the optical parameters (radius of curvature, thickness...). This makes possible to consider different digital processing algorithms, ranging from linear deconvolution to learning approaches. 

For the next few years (in particular by proposing this theme as part of the [ANR 2024 call for generic projects](https://anr.fr/en/call-for-proposals-details/call/generic-call-for-proposals-aapg-2024/)), we propose to use the [ESCL-licensed FORMIDABLE](https://www.space-codev.org/communities-projects/) differentiable ray tracer, and to develop an environment specifically dedicated to joint optical/processing design. In the course of the project, we will be looking at imaging systems of increasing complexity (using phase masks in the pupil of the optical device to modify the wavefront, then modifying a larger number of surfaces, possibly freeform). We will propose specific design strategies for the different types of processing envisaged, in line with the size, weight and power consumption constraints of the imaging system. A demonstrator dedicated to car driving will enable us to validate experimentally one of the strategies we have put in place.

Freeform optics for compactness
======

Since joining ONERA, I've been part of [Clément Freslier](https://fr.linkedin.com/in/clementfreslier)'s supervision team (director: [Thierry Lépine](https://fr.linkedin.com/in/thierry-l%C3%A9pine-031307163), co-director: [Guillaume Druart](https://fr.linkedin.com/in/guillaume-druart-3b972a219)). His work focuses on compact imaging optical systems embedded into small satellites. Achieving good optical performance with exemplary compactness requires the use of freeform mirrors. We are studying the NURBS (Non Uniform Rational B-splines) surface representation, implemented in [FORMIDABLE](https://www.space-codev.org/communities-projects/), to describe and optimize such systems. 
