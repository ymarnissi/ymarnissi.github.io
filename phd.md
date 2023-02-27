---
layout: page
title: Ph.D work
---

<p align="center">
My Ph.D. research aims to investigate the fascinating intersection between <strong>deterministic optimization</strong>  and the <strong>Bayesian framework</strong> , two fields that have traditionally followed separate paths. By incorporating deterministic optimization techniques, my research has contributed to enhancing Bayesian algorithms' efficiency, particularly in high-dimensional spaces.
</p>

---
<center>
<div style="width: 50%; text-align: center; font-size:15px; margin:10px;">
  <a href="#" class="btn">Ph.D manuscript.</a> <a href="#" class="btn">Defense's slides.</a>
</div>
</center>
---

<div style="width: 100%;">
  
  
<div style="float: left; width: 40%; text-align: justify; font-size:15px;">
<center> <h2>3MH sampler</h2></center>
  <p>This is the <em>Majorize-Minimize adapted Metropolis-Hasting algorithm</em>: a novel <strong>Markov Chain Monte Carlo</strong> (MCMC) sampling algorithm using derivatives informations about the target density. </p>
<!--more-->
<p>It is a <strong>Metropolis-Hastings</strong> algorithm inspired from <strong>Langevin dynamics</strong>, where the drift term is preconditioned
by an adaptive matrix constructed through a <strong>Majorization-Minimization</strong> strategy. </p>
<a href="3MH.md">Read More...</a>
</div>

<div style="float: right; width: 40%; text-align: justify; font-size:15px;">
<center> <h2>Auxiliary variables Gibbs sampler for high dimensional spaces</h2></center>
<p>This is a <strong>Gibbs</strong> sampler with a <strong>Data Augmentation</strong> approach.  It ddresses the problem of sampling from multivariable distributions when the variables of interest are strongly correlated with heterogeneous sources of dependencies preventing efficient sampling with standard algorithms.</p>
<!--more-->
<p> <strong>Auxliary variables</strong> are added to the model without changing the target marginal
distributions in such a way that simulation can be performed more efficiently
in the new larger space. </p>
<a href="3MH.md">Read More...</a>
</div>
  <p> \br </p>
</div>



<div style="float: left; width: 100%; text-align: justify; font-size:15px;">
<center> <h2>VBA algorithm for non-Gaussian models</h2></center>
  <p>This is a Bayesian algorithm with <em>Variational Bayesian Approximation</em> (VBA) for image recovery beyond additive Gaussian noise models. </p>
<!--more-->
<p>Unlike classical approaches often adopted in the literature, the regularization parameter is estimated throughout a VBA algorithm from
the observations. In order to address the problem of the intricate form of either the observation model or the prior distribution, we resort
to majorization techniques to construct a <strong>lower bound</strong> on the <strong>Kulback
divergence</strong> that we want to minimize. This is highly related to <strong>Half-Quadratic</strong> approaches used in deterministic optimization. 
 </p>
<a href="3MH.md">Read More...</a>
</div>

We address the
problem of image recovery beyond additive Gaussian noise models.
Unlike classical approaches often adopted in the literature, the regularization parameter is estimated throughout a VBA algorithm from
the observations. In order to address the problem of the intricate for


