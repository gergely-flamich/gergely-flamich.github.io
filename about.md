---
layout: about
title: about
permalink: /
subtitle: >
  <a href='https://www.cbl-cambridge.org/people/gf332'>PhD Student</a> in Machine Learning, CBL, University of Cambridge. 
cv_pdf: 'cv_minimal.pdf'

profile:
  align: right
  image: profile_pic_3_cropped.jpeg
  image_circular: false # crops the image to make it circular
  address: >
    <p>Computational and Biological Learning Lab</p>
    <p>Dept. of Engineering</p>
    <p>University of Cambridge</p>
    <p>Trumpington Street, Cambridge CB2 1PZ, UK</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hello there! I'm Gergely Flamich (pronounced <span style="font-family:sans-serif;">[[gɛrˈgɛj flɒmih]](https://en.wikipedia.org/wiki/Help:IPA/Hungarian)</span>, but in English, I usually go by Greg), and I'm originally from Vác, Hungary. 
I am a PhD student in Advanced Machine Learning at the [Computational and Biological Learning Lab](https://www.cbl-cambridge.org/) (since Oct 2020), supervised by [José Miguel Hernández Lobato](https://jmhl.org/). 
I hold an MPhil degree in [Machine Learning and Machine Intelligence](https://www.mlmi.eng.cam.ac.uk/) from the University of Cambridge and a Joint BSc Honours degree in Mathematics and Computer Science from the University of St Andrews.

My research focuses on the theory of [relative entropy coding/channel simulation](https://arxiv.org/abs/2305.15313) and its application to [neural data compression](https://arxiv.org/abs/2202.06533). 
Relative entropy coding algorithms allow us to efficiently encode a random sample from both discrete and continuous distributions, and they are a natural alternative to quantization and entropy coding in lossy compression codecs.
Furthermore, they bring unique advantages to lossy compression once we go beyond the standard rate-distortion framework: they allow us to design optimally efficient [artefact-free/perfectly realistic lossy compression](https://arxiv.org/abs/2206.08889) codecs using generative models and perform [differentially private federated learning](https://arxiv.org/abs/2111.00092) with optimal communication cost.
Unfortunately, relative entropy coding hasn't seen widespread adoption, as all current algorithms are either too slow or have limited applicability.

Hence, I am focusing on addressing this issue by developing fast, general-purpose coding algorithms, such as [A* coding](https://arxiv.org/abs/2201.12857) and [greedy Poisson rejection sampling](https://arxiv.org/abs/2305.15313), and providing mathematical guarantees on their coding efficiency and runtime.
In addition to my theoretical work, I am also interested in applying relative entropy coding algorithms to neural compression, utilizing generative models such as [variational autoencoders](https://arxiv.org/abs/2010.01185) and [implicit neural representations](https://arxiv.org/abs/2305.19185).

From July 2022 until Dec 2022, I worked with [Lucas Theis](http://theis.io/) as a Student Researcher at Google Brain, during which time we developed [adaptive greedy rejection sampling and bits-back quantization](https://arxiv.org/abs/2304.10407).