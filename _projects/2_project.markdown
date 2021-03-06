---
layout: page
title: Euphony
description: Machine learning-guided program synthesis
img: /assets/img/12.jpg
---

### Euphony
<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/euphony1.jpg" alt="" title="System architecture" style='height: 100%; width: 100%; object-fit: contain'/>
</div>
<div class="col three caption">
    System architecture of Euphony
</div>

<!--
<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/euphony2.jpg" alt="" title="Example reduced version of tar-1.14" style='height: 100%; width: 100%; object-fit: contain'/>
</div>
<div class="col three caption">
    example reduced version of tar-1.14 generated by Chisel
</div>
-->

Description: The goal of program synthesis is to automatically synthesize a program that satisfies a given high-level specification.
A central challenge in program synthesis concerns how to efficiently search for the desired program in the space of possible programs.
It is well known that desired programs contain repetitive and predictable patterns.
We have proposed a new approach to accelerate search-based program synthesis based on this observation.
Our key insight is to learn a probabilistic model of programs and use it to guide the search.


Links: [PLDI 2018 paper](https://www.cis.upenn.edu/~mhnaik/papers/pldi18b.pdf) [Euphony tool](https://github.com/wslee/euphony)  

