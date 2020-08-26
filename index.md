---
<!-- layout: home -->
layout: single
author_profile: true
permalink: /index.html
title: Welcome.
feature_row:
  - image_path: http://asic.ethz.ch/2019/Baikonur_www.png
    alt: "Baikonur die photograph"
    title: "Baikonur (GF22FDX)"
    excerpt: "Baikonur is the successor of Kosmodrom featuring two Ariane cores and 25 Snitch cores."
    url: http://asic.ethz.ch/2019/Baikonur.html
  - image_path: http://asic.ethz.ch/2018/DMS10666_corr.JPG
    alt: "Kosmodrom die photograph"
    title: "Kosmodrom (GF22FDX)"
    excerpt: "Kosmodrom features two Ariane cores and a neural network accelerator (NTX)."
    url: http://asic.ethz.ch/2018/Kosmodrom.html
  - image_path: http://asic.ethz.ch/2019/Billywig_www.png
    alt: "Billywig die photograph"
    title: "Billywig (UMCL65)"
    excerpt: "Billywig is the first ASIC implementation of a Snitch cluster."
    url: http://asic.ethz.ch/2019/Billywig.html
  - image_path: http://asic.ethz.ch/2018/Poseidon_www.png
    alt: "Poseidon die photograph"
    title: "Poseidon (GF22FDX)"
    excerpt: "Poseidon features one Ariane cores coupled to a PULP-based SoC."
    url: http://asic.ethz.ch/2018/Poseidon.html
  - image_path: http://asic.ethz.ch/2018/Scarabaeus_www.png
    alt: "Scarabeus die photograph"
    title: "Scarabeus (UMCL65)"
    excerpt: "Designed by students partially under my supervision. Features one Ariane core and a tensor DMA."
    url: http://asic.ethz.ch/2018/Scarabaeus.html
  - image_path: http://asic.ethz.ch/2018/Atomario_www.png
    alt: "Atomario die photograph"
    title: "Atomario (UMCL65)"
    excerpt: "Multi-cluster PULP implementation w/ atomic adapter."
    url: http://asic.ethz.ch/2018/Atomario.html
  - image_path: http://asic.ethz.ch/2018/Drift_www.png
    alt: "Drift die photograph"
    title: "Drift (UMCL65)"
    excerpt: "Different integer divider implementations."
    url: http://asic.ethz.ch/2018/Drift.html
  - image_path: http://asic.ethz.ch/2015/Imperio_www.png
    alt: "Imperio die photograph"
    title: "Imperio (UMCL65)"
    excerpt: "My first chip as a Master student. A PULPino system in 65nm."
    url: http://asic.ethz.ch/2015/Imperio.html
---

My name is Florian and I am currently a PhD student with the [Integrated Systems Laboratory](https://iis.ee.ethz.ch/) of [ETH Zurich](https://www.ethz.ch/en). My research interest include the design of very large scale integration circuits with particular focus on application specific integrated circuits and their applications in high performance computing. Please don't hesitate to get in contact with me!

## Chips.

As part of my PhD program I have designed and contributed to the following chips:

{% include feature_row %}

## Talks.

(Recorded) Talks:

{% include video id="8HpvRNh0ux4" provider="youtube" %}

{% include video id="a939OYZolmk" provider="youtube" %}

## Publications.

Here is a curated list of publications.

**Manticore: A 4096-core RISC-V Chiplet Architecture for Ultra-efficient Floating-point Computing**<br/>
_Florian Zaruba_, Fabian Schuiki and Luca Benini<br/>
[HotChips 2020](https://arxiv.org/pdf/2008.06502)

**FPnew: An Open-Source Multi-Format Floating-Point Unit Architecture for Energy-Proportional Transprecision Computing**<br/>
Stefan Mach, Fabian Schuiki, _Florian Zaruba_ and Luca Benini<br/>
[Preprint arXiv (IEEE Transactions on Very Large Scale Integration)](https://arxiv.org/pdf/2007.01530)

**Snitch: A 10 kGE Pseudo Dual-Issue Processor for Area and Energy Efficient Execution of Floating-Point Intensive Workloads**<br/>
_Florian Zaruba_, Fabian Schuiki, Torsten Hoefler and Luca Benini<br/>
[Preprint arXiv (IEEE Transactions on Computers)](https://arxiv.org/pdf/2002.10143)

**Stream Semantic Registers: A Lightweight RISC-V ISA Extension Achieving Full Compute Utilization in Single-Issue Cores**<br/>
Fabian Schuiki, _Florian Zaruba_, Torsten Hoefler and Luca Benini<br/>
[IEEE Transactions on Computers](https://arxiv.org/pdf/1911.08356)

**The Floating Point Trinity: A Multi-modal Approach to Extreme Energy-Efficiency and Performance**<br/>
_Florian Zaruba_, Fabian Schuiki, Stefan Mach and Luca Benini<br/>
[2019 26th IEEE International Conference on Electronics, Circuits and Systems (ICECS)](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/399888/IEEE_ICECS_2019%281%29.pdf?sequence=1)

**Ara: A 1-GHz+ Scalable and Energy-Efficient RISC-V Vector Processor With Multiprecision Floating-Point Support in 22-nm FD-SOI**<br/>
Matheus Cavalcante, Fabian Schuiki, _Florian Zaruba_, Michael Schaffner and Luca Benini<br/>
[IEEE Transactions on Very Large Scale Integration (VLSI) Systems](https://arxiv.org/pdf/1906.00478)

**The Cost of Application-class Processing: Energy and Performance Analysis of a Linux-ready 1.7-GHz 64-bit RISC-V Core in 22-nm FDSOI Technology**<br/>
_Florian Zaruba_ and Luca Benini<br/>
[IEEE Transactions on Very Large Scale Integration (VLSI) Systems 27.11 (2019): 2629-2640](https://ieeexplore.ieee.org/abstract/document/8777130?casa_token=d1B7sZ9ntPkAAAAA:OcMbyz4glipP4g7rkjj14B_Pl02YvhGU1CINcbgIBL2SPqHPd0-WtmeXTeOtZPSZnGytwRBnp6E)

**OpenPiton+ Ariane: The First Open-Source, SMP Linux-booting RISC-V System Scaling From One to Many Cores**<br/>
Jonathan Balkind, Katie Lim, Fei Gao, Jinzheng Tu, David Wentzlaff, Michael Schaffner, _Florian Zaruba_ and Luca Benini<br/>
[Third Workshop on Computer Architecture Research with RISC-V, CARRV](https://parallel.princeton.edu/papers/balkind_carrv2019.pdf)

**BYOC: A "bring your own core" framework for heterogeneous-ISA research**<br/>
Jonathan Balkind, Katie Lim, Michael Schaffner, Fei Gao, Grigory Chirkov, Ang Li, Alexey Lavrov, Tri M Nguyen, Yaosheng Fu, _Florian Zaruba_, Kunal Gulati, Luca Benini and David Wentzlaff<br/>
[Proceedings of the Twenty-Fifth International Conference on Architectural Support for Programming Languages and Operating Systems](http://www.parallel.princeton.edu/papers/aspl20-balkind.pdf)

<!-- <h2>Publications</h2> -->

<!-- <h2>Talks</h2> -->

<!-- <h2>Professional Experience</h2> -->

<!-- <h2>Education</h2> -->

