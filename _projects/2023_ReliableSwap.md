---
layout: paper
title: 'ReliableSwap'
description: 'Under reviewed'
img: assets/img/reliable_swap/fr_weakness.png
importance: 1
category: paper

date: 2023-06-06

authors:
  - name: Ge Yuan
    url: "https://ygtxr1997.github.io"
    affiliations: '1,2'
    equal: True
  - name: Maomao Li
    url: "https://scholar.google.com/citations?hl=en&user=ym_t6QYAAAAJ"
    affiliations: '2'
    equal: True
  - name: Yong Zhang
    url: "https://yzhang2016.github.io/yongnorriszhang.github.io/"
    affiliations: '2'
    corresponding: True
  - name: Huicheng Zheng
    url: "https://cse.sysu.edu.cn/content/2481"
    affiliations: '1'
    corresponding: True

affiliations:
  - name: "Sun Yat-sen University"
    idx: '1'
  - name: "Tencent AI Lab"
    idx: '2'

links:
  - name: "ArXiv"
    url: "https://arxiv.com"
  - name: "Code"
    url: "https://github.com"
  - name: "Demo"
    url: "https://huggingface.com"

bibliography: 2023-02-03-.bib
---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/reliable_swap/fr_weakness.png" title="example image" class="img-fluid" zoomable=true %}
  </div>
</div>

**TL;DR: A general face swapping training framework that:**

✅ solves no-guidance problems <br>
✅ enhances source identity preservation <br>
✅ is orthogonal and compatiable with existing methods <br>


<h1>Image Face Swapping</h1>

<div class="col-sm mt-3 mt-md-0 centered">
    {% include figure.html path="assets/img/reliable_swap/web_results.png" title="example image" class="img-fluid" zoomable=true%}
</div>
<div class="caption">
    Results on images collected from the web.
</div>

<div class="col-sm mt-3 mt-md-0 centered">
    {% include figure.html path="assets/img/reliable_swap/celebahq.png" title="example image" class="img-fluid" zoomable=true%}
</div>
<div class="caption">
    Results on CelebA-HQ.
</div>

<div class="col-sm mt-3 mt-md-0 centered" style="max-width:80%">
    {% include figure.html path="assets/img/reliable_swap/ffplus.png" title="example image" class="img-fluid" zoomable=true%}
</div>
<div class="caption">
    Results on FF+.
</div>


<h1>Video Face Swapping</h1>

<div class="centered container">
  <iframe class="video" width="100%" src="https://www.youtube.com/embed/uqe4pD-XpGE"></iframe> 
</div>


<h1>What Problems We Solve</h1>

<div class="col-sm mt-3 mt-md-0 centered">
    {% include figure.html path="assets/img/reliable_swap/celebahq.png" title="example image" class="img-fluid" zoomable=true%}
</div>
During face swapping training, the re-construction task (used when $X_{\rm{t}}=X_{\rm{s}}$) cannot be used as the proxy anymore when $X_{\rm{t}} \neq X_{\rm{s}}$, lacking pixel-wise supervison $\Gamma$.


<h1>Method</h1>

<div class="col-sm mt-3 mt-md-0 centered">
    {% include figure.html path="assets/img/reliable_swap/celebahq.png" title="example image" class="img-fluid" zoomable=true%}
</div>
<div class="caption">
    Results on CelebA-HQ.
</div>

<div class="col-sm mt-3 mt-md-0 centered">
    {% include figure.html path="assets/img/reliable_swap/celebahq.png" title="example image" class="img-fluid" zoomable=true%}
</div>
<div class="caption">
    Results on CelebA-HQ.
</div>

<h1>Reference</h1>

Coming soon.


<h1>Acknowledgements</h1>

Coming soon.
