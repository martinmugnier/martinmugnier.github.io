---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## Job Market Paper ##
[Link to the paper](https://drive.google.com/file/d/1KhmV8tOcoGdIMMpQ4aaw0ddvyeL5tG4V/view?usp=sharing)

*Abstract:* In studies based on longitudinal data, researchers often assume time-invariant unobserved heterogeneity or linear-in-parameters conditional expectations. Violation of these assumptions may lead to poor counterfactuals. I study the identification and estimation of a large class of nonlinear grouped fixed effects (NGFE) models where the relationship between observed covariates and cross-sectional unobserved heterogeneity is left unrestricted but the latter only takes a restricted number of paths over time. I show that the corresponding ``clusters'' and the nonparametrically specified link function can be point-identified when both dimensions of the panel are large. I propose a semiparametric NGFE estimator whose implementation is feasible, and establish its large sample  properties in popular binary and count outcome models. Distinctive features of the NGFE estimator are that it is asymptotically normal unbiased at parametric rates, and it allows for the number of periods to grow slowly with the number of cross-sectional units. Monte Carlo simulations suggest good finite sample performance. I apply this new method to revisit the so-called inverted-U relationship between product market competition and innovation. Allowing for clustered patterns of time-varying unobserved heterogeneity leads to a much flatter estimated curve.


## Working Papers

<ul>
 <li>Fixed Effects Binary Choice Models with Three or More Periods (with <a href="https://faculty.crest.fr/xdhaultfoeuille/">Xavier D'Haultfœuille</a> and <a href="http://www.crest.fr/ses.php?user=2986)">Laurent Davezies</a>),  <em>Revised and Resubmitted to <b>Quantitative Economics</b></em>.
<details><summary>[Abstract] [<a href="https://arxiv.org/pdf/2009.08108v4.pdf">Paper (version: Sep. 2022)</a>]</summary>
<p>
<em>We consider fixed effects binary choice models with a fixed number of periods $T$ and without a large support condition on the regressors. If the time-varying unobserved terms are i.i.d. with known distribution $F$, Chamberlain (2010) shows that the common slope parameter is point identified if and only if $F$ is logistic. However, he only considers in his proof $T=2$. We show that actually, the result does not generalize to $T\geq 3$: the common slope parameter can be identified when $F$ belongs to a family including the logit distribution. Identification is based on a conditional moment restriction. Under restrictions on the covariates, these moment conditions lead to point identification of relative effects. Finally, if $T=3$ and mild conditions hold, GMM estimators based on these conditional moment restrictions reach the semiparametric efficiency bound.
 </em>
</p>
</details>
 </li>
 <li>A Simple and Computationally Trivial Estimator for Grouped Fixed Effects Models, <em>Submitted</em>.
<details><summary>[Abstract] [<a href="https://github.com/martinmugnier/martinmugnier.github.io/blob/239ffc3b96cb71226731c376880ddd20cca33e44/files/a_simple_and_computationally_trivial_estimator_for_grouped_fixed_effects_models.pdf">Paper (version: Sep. 2022)</a>][<a href="https://github.com/martinmugnier/PWD-Estimators">Replication Code</a>][<a href="https://github.com/martinmugnier/martinmugnier.github.io/blob/deb3e2135c00d71e5c3ea11dc2ac16e9347ed8a2/files/a_simple_and_computationally_trivial_estimator_for_grouped_fixed_effects_models_SUPP_MAT.pdf">Supplemental Material</a>]</summary>
<p>
<em>This paper provides a new fixed effects estimator for linear panel data models with clustered time patterns of unobserved heterogeneity. The method combines smooth and convex nuclear norm regularization with a pairwise differencing argument that takes at most $O(N^3)$ elementary operations to agglomeratively cluster cross-sectional units. Asymptotic guarantees are established in a framework where $T$ can grow at any power of $N$, as both $N$ and $T$ diverge to infinity. In contrast to existing approaches, the proposed estimator (i) is computationally straightforward, (ii) does not require a known upper bound on the number of groups, (iii) consistently estimates the number of groups, (iv) correctly classifies units into groups with probability tending to one uniformly across units, (v) is asymptotically equivalent to the infeasible least squares estimator that controls for the true group indicators, (vi) is asymptotically normal at parametric rates, (vii) and is free of the incidental parameters problem.
 </em>
</p>
</details>
 </li>
 <li>Identification and (Fast) Estimation of Large Nonlinear Panel Models with Two-Way Fixed Effects (with <a href="https://sites.google.com/view/aowang-economics/home">Ao Wang</a>)
 <details><summary>[Abstract][<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4186349">Paper</a>][<a href="https://github.com/martinmugnier/nlmfe">Python package</a>]</summary>
  <p>
   <em>We study a nonlinear two-way fixed effects panel model that allows for unobserved individual heterogeneity in slopes (interacting with covariates) and (unknown) flexibly specified link function. The former is particularly relevant when the researcher is interested in the distributional causal effects of covariates, and the latter mitigates potential misspecification errors due to imposing a known link function. We show that the fixed effects parameters and the (nonparametrically specified) link function can be identified when both individual and time dimensions are large. We propose a novel iterative Gauss-Seidel estimation procedure that overcomes the practical challenge of dimensionality in the number of fixed effects when the dataset is large. We revisit two empirical studies in trade (Helpman et al., 2008) and innovation (Aghion et al., 2013), and find non-negligible unobserved dispersion in trade elasticity (across countries) and the effect of institutional ownership on innovation (across firms). These exercises emphasize the usefulness of our method in capturing flexible (and unobserved) heterogeneity in the causal relationship of interest that may have important implications for the subsequent policy analysis.
   </em>
  </p>
  </details>
  </li>
 </ul>



## Work in Progress

<ul>
 <li> Unobserved Clusters of Time-Varying Heterogeneity in Nonlinear Panel Data Models </li>
 <li> Asymptotic  Properties  of  Empirical  Quantile-Based Estimators (with <a href="https://faculty.crest.fr/xdhaultfoeuille/">Xavier D'Haultfœuille</a> and <a href="https://sites.google.com/site/jeremylhour/">Jérémy L'Hour</a>)</li>
</ul>

## Unpublished work

<ul>
  <li> A Note on the Existence of Conditional Maximum Likelihood Estimates of the Binary Logit Model with Fixed Effects [<a href="https://arxiv.org/abs/2009.09998">arXiv</a>][<a href="https://github.com/martinmugnier/BinLogitCMLE">Package</a>]  </li>
 </ul>
 
