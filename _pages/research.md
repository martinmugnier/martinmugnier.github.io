---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


## Published Papers
<ul>
 <li>A Simple and Computationally Trivial Estimator for Grouped Fixed Effects Models, <em>forthcoming at <b>Journal of Econometrics</b></em>
<details><summary>[Abstract] [<a href="https://arxiv.org/abs/2203.08879">Paper (version: Sep. 2024)</a>][<a href="https://github.com/martinmugnier/TPWD-Estimators">Replication Code</a>][<a href="https://martinmugnier.github.io/files/a_simple_and_computationally_trivial_estimator_supplemental_material.pdf">Supplementary Material</a>]</summary>
<p>
<em> This paper introduces a new fixed effects estimator for linear panel data models with clustered time patterns of unobserved heterogeneity. The method avoids non-convex and combinatorial optimization by combining a preliminary consistent estimator of the slope coefficient, an agglomerative pairwise-differencing clustering of cross-sectional units, and a pooled ordinary least squares regression. Asymptotic guarantees are established in a framework where $T$ can grow at any power of $N$, as both $N$ and $T$ approach infinity. Unlike most existing approaches, the proposed estimator is computationally straightforward and does not require a known upper bound on the number of groups. As existing approaches, this method leads to a consistent estimation of well-separated groups and an estimator of common parameters asymptotically equivalent to the infeasible regression controlling for the true groups. An application revisits the statistical association between income and democracy.
 </em>
</p>
</details>
 </li>
 <li>Fixed Effects Binary Choice Models with Three or More Periods (with <a href="https://sites.google.com/view/laurentdavezies/about-me">Laurent Davezies</a> and <a href="https://faculty.crest.fr/xdhaultfoeuille/">Xavier D'Haultfœuille</a>), <em><b>Quantitative Economics</b></em>, 14 (3): 1105-1132 (2023). 
<details><summary>[Abstract] [<a href="https://www.econometricsociety.org/publications/quantitative-economics/2023/07/01/Fixed-effects-binary-choice-models-with-three-or-more-periods">Publisher</a>] [<a href="https://arxiv.org/pdf/2009.08108v4.pdf">arXiv</a>]</summary>
<p>
<em>We consider fixed effects binary choice models with a fixed number of periods $T$ and without a large support condition on the regressors. If the time-varying unobserved terms are i.i.d. with known distribution $F$, Chamberlain (2010) shows that the common slope parameter is point identified if and only if $F$ is logistic. However, he only considers in his proof $T=2$. We show that actually, the result does not generalize to $T\geq 3$: the common slope parameter can be identified when $F$ belongs to a family including the logit distribution. Identification is based on a conditional moment restriction. Under restrictions on the covariates, these moment conditions lead to point identification of relative effects. Finally, if $T=3$ and mild conditions hold, GMM estimators based on these conditional moment restrictions reach the semiparametric efficiency bound.
 </em>
</p>
</details>
 </li>
 </ul>

## Working Papers

<ul>

 <li>Fixed Effects Nonlinear Panel Models with Heterogeneous Slopes: Identification and Consistency (with <a href="https://sites.google.com/view/aowang-economics/home">Ao Wang</a>), <em>Revision requested at <b>Journal of Econometrics</b></em> 
  <details><summary>[Abstract][<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4186349">Paper (version: Dec. 2024)</a>][<a href="https://github.com/martinmugnier/nlmfe">Python package</a>]</summary>
  <p>
   <em> We study a class of two-way fixed effects index function models with a nonparametric link function and individual- (or time-) specific slopes. Our model alleviates potential misspecification errors due to the common practice of specifying a known link function such as Gaussian and its tail behavior. It also enables to incorporate richer unobserved heterogeneity in the marginal effects of covariates via heterogeneous slopes across individuals.  We show the identification of the link function as well as the slopes and fixed effects parameters when both individual and time dimensions are large. We propose a nonparametric consistency result for the fixed effects sieve maximum likelihood estimators. Finally, we apply our method to the study of establishing exportation and illustrate the consequences of imposing Gaussian link function and homogeneity on the slope of distance. 
   </em>
  </p>
  <sub> This paper supersedes "Identification and (Fast) Estimation of Large Nonlinear Panel Models with Two-Way Fixed Effects". </sub>
  </details>
  </li>
 
  <li>Inference After Discretizing Unobserved Heterogeneity (with <a href="https://sites.google.com/view/jad-beyhum">Jad Beyhum</a>)
  <details><summary>[Abstract][<a href="https://arxiv.org/abs/2412.07352">Paper</a>][<a href="https://www.cemmap.ac.uk/publication/inference-after-discretizing-unobserved-heterogeneity/">Cemmap working paper</a>]</summary>
  <p>
   <em> We consider a linear panel data model with nonseparable two-way unobserved heterogeneity corresponding to a linear version of the model studied in Bonhomme et al. (2022). We show that inference is possible in this setting using a straightforward two-step estimation procedure inspired by existing discretization approaches. In the first step, we construct a discrete approximation of the unobserved heterogeneity by (k-means) clustering observations separately across the individual ($i$) and time ($t$) dimensions. In the second step, we estimate a linear model with two-way group fixed effects specific to each cluster. Our approach shares similarities with methods from the double machine learning literature, as the underlying moment conditions exhibit the same type of bias-reducing properties. We provide a theoretical analysis of a cross-fitted version of our estimator, establishing its asymptotic normality at parametric rate under the condition $\max(N,T)=o(\min(N,T)^3)$. Simulation studies demonstrate that our methodology achieves excellent finite-sample performance, even when $T$ is negligible with respect to $N$.
   </em>
  </p>
  </details>
 </li>
   
  <li>Unobserved Clusters of Time-Varying Heterogeneity in Nonlinear Panel Data Models
   <details><summary>[Abstract][<a href="https://drive.google.com/file/d/1KhmV8tOcoGdIMMpQ4aaw0ddvyeL5tG4V/view?usp=sharing">Paper</a>]</summary>
  <p>
   <em>In studies based on longitudinal data, researchers often assume time-invariant unobserved heterogeneity or linear-in-parameters conditional expectations. Violation of these assumptions may lead to poor counterfactuals. I study the identification and estimation of a large class of nonlinear grouped fixed effects (NGFE) models where the relationship between observed covariates and cross-sectional unobserved heterogeneity is left unrestricted but the latter only takes a restricted number of paths over time. I show that the corresponding ``clusters'' and the nonparametrically specified link function can be point-identified when both dimensions of the panel are large. I propose a semiparametric NGFE estimator and establish its large sample  properties in popular binary and count outcome models. Distinctive features of the NGFE estimator are that it is asymptotically normal unbiased at parametric rates, and it allows for the number of periods to grow slowly with the number of cross-sectional units. Monte Carlo simulations suggest good finite sample performance. I apply this new method to revisit the so-called inverted-U relationship between product market competition and innovation. Allowing for clustered patterns of time-varying unobserved heterogeneity leads to a less pronounced inverted-U relationship.
   </em>
  </p>
  </details>
  </li>

 <li>R. A. Fisher's Exact Test Revisited
<details><summary>[Abstract] [<a href="https://arxiv.org/abs/2407.07251">Paper</a>]</summary>
<p>
<em> This note provides a conceptual clarification of Ronald Aylmer Fisher's (1935) pioneering exact test in the context of the Lady Testing Tea experiment. It unveils a critical implicit assumption in Fisher's calibration: the taster minimizes expected misclassification given fixed probabilistic information. Without similar assumptions or an explicit alternative hypothesis, the rationale behind Fisher's specification of the rejection region remains unclear.
 </em>
</p>
</details>
 </li>
  
 </ul>



## Work in Progress

<ul>
 <li> Asymptotic  Properties  of  Empirical  Quantile-Based Estimators (with <a href="https://julienchhor.github.io"> Julien Chhor </a>, <a href="https://faculty.crest.fr/xdhaultfoeuille/">Xavier D'Haultfœuille</a>, and <a href="https://sites.google.com/site/jeremylhour/">Jérémy L'Hour</a>)</li>
</ul>

## Unpublished Work

<ul>
  <li> A Note on the Existence of Conditional Maximum Likelihood Estimates of the Binary Logit Model with Fixed Effects [<a href="https://arxiv.org/abs/2009.09998">arXiv</a>][<a href="https://github.com/martinmugnier/BinLogitCMLE">Package</a>]  </li>
 </ul>
 
