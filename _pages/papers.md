---
title: 
layout: single
classes: wide
permalink: /papers/
---
<br/> 

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNS829G"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

# <center> Working Papers </center>
- - -


**Design-Based Uncertainty for Quasi-Experiments** (with Ashesh Rambachan). 2022.<br/>
<small>[ <a href="#/" onclick="visib('design-based')">Abstract</a> | [Draft][design-based-arxiv] ] </small>

<div id="design-based" style="display: none; text-align: justify; line-height: 1.2" ><small>
Conventional standard errors reflect the fact that the observed data is sampled from an infinite super-population, but this approach to uncertainty may be unnatural in settings where all units in the population are observed (e.g. all 50 U.S. states). In such settings, it may be more natural to view the uncertainty as design-based, i.e. arising from the stochastic assignment of treatment. This paper develops a design-based framework for uncertainty that is suitable for analyzing "quasi-experimental" settings commonly studied in economics. A key feature of our framework is that each unit has an idiosyncratic probability of receiving treatment, but these idiosyncratic probabilities are unknown to the researcher. We derive conditions under which difference-in-differences (DiD) and related estimators are unbiased for an interpretable causal estimand. When the DiD estimator is unbiased, conventional confidence intervals are valid but potentially conservative in large populations. An interesting feature of our setting is that conventional standard errors tend to be more conservative when treatment probabilities differ across units, which helps to mitigate undercoverage from bias. As a result, conventional confidence intervals for DiD can potentially still have correct coverage even if the design-based analog to parallel trends does not hold exactly. Our results also have implications for the appropriate level to cluster standard errors and for the analysis of instrumental variables.
</small><br><br/></div>

[design-based-arxiv]: https://arxiv.org/pdf/2008.00602.pdf


**A More Credible Approach to Parallel Trends** 
[Previously titled "An Honest Approach to Parallel Trends"] (with Ashesh Rambachan). 2022.
*Conditionally accepted, Review of Economic Studies*
<br/>
<small>[ <a href="#/" onclick="visib('hpt')">Abstract</a> | [Draft][1] | [JMP Version (old)][3] | [R package][hpt-package] ] </small>

<div id="hpt" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper proposes tools for robust inference in difference-in-differences and event-study designs where the parallel trends assumption may be violated. Instead of requiring that parallel trends holds exactly, we impose restrictions on how different the post-treatment violations of parallel trends can be from the pre-treatment differences in trends ("pre-trends"). The causal parameter of interest is partially identified under these restrictions. We introduce two approaches that guarantee uniformly valid inference under the imposed restrictions, and we derive novel results showing that they have desirable power properties in our context. We illustrate how economic knowledge can inform the restrictions on the possible violations of parallel trends in two economic applications. We also highlight how our approach can be used to conduct sensitivity analyses showing what causal conclusions can be drawn under various restrictions on the possible violations of the parallel trends assumption.
</small><br><br/></div>

[1]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Main.pdf %}
[2]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Supp.pdf %}
[3]: {{ site.baseurl }}{% link assets/files/roth_jmp_honestparalleltrends_main_jmp_version.pdf %}
[hpt-package]: https://github.com/asheshrambachan/HonestDiD



**Efficient Estimation for Staggered Rollout Designs** (with Pedro Sant'Anna). 2022.<br/>
<small>[ <a href="#/" onclick="visib('staggeredefficient')">Abstract</a> | [Draft][staggeredefficient-arxiv] | [R package][staggeredefficient-package] | [Stata package][staggeredefficient-stata-package] ]</small>

<div id="staggeredefficient" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper studies efficient estimation of causal effects when treatment is (quasi-) randomly rolled out to units at different points in time. We solve for the most efficient estimator in a class of estimators that nests two-way fixed effects models and other popular generalized difference-in-differences methods. A feasible plug-in version of the efficient estimator is asymptotically unbiased with efficiency (weakly) dominating that of existing approaches. We provide both t-based and permutation-test based methods for inference. We illustrate the performance of the plug-in efficient estimator in simulations and in an application to Wood et al (2020)'s study of the staggered rollout of a procedural justice training program for police officers. We find that confidence intervals based on the plug-in efficient estimator have good coverage and can be as much as eight times shorter than confidence intervals based on existing state-of-the-art methods. As an empirical contribution of independent interest, our application provides the most precise estimates to date on the effectiveness of procedural justice training programs for police officers.
</small><br><br/></div>

[staggeredefficient-arxiv]: https://arxiv.org/pdf/2102.01291.pdf
[staggeredefficient-package]: https://github.com/jonathandroth/staggered
[staggeredefficient-stata-package]: https://github.com/jonathandroth/staggered_stata



**What's Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature** (with Pedro Sant'Anna, Alyssa Bilinski, and John Poe). 2022. *Conditionally accepted, Journal of Econometrics*
<br/>
<small>[ <a href="#/" onclick="visib('did-review')">Abstract</a> | [Draft][did-review-draft] ] </small>

<div id="did-review" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper synthesizes recent advances in the econometrics of difference-in-differences (DiD) and provides concrete recommendations for practitioners. We begin by articulating a simple set of "canonical" assumptions under which the econometrics of DiD are well-understood. We then argue that recent advances in DiD methods can be broadly classified as relaxing some components of the canonical DiD setup, with a focus on (i) multiple periods and variation in treatment timing, (ii) potential violations of parallel trends, or (iii) alternative frameworks for inference. Our discussion highlights the different ways that the DiD literature has advanced beyond the canonical model, and helps to clarify when each of the papers will be relevant for empirical work. We conclude by discussing some promising areas for future research.
</small><br><br/></div>

[did-review-draft]:{{ site.baseurl }}{% link assets/files/DiD_Review_Paper.pdf %}


**Union Reform and Teacher Turnover: Evidence from Wisconsin's Act 10**. 2019.
<br/>
<small>[ <a href="#/" onclick="visib('act10')">Abstract</a> | [Draft][act10-draft] ] </small>

<div id="act10" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper studies teacher attrition in Wisconsin following Act 10, a policy change which severely weakened teachers’ unions and capped wage growth for teachers. I document a sharp short-run increase in teacher turnover after the Act was passed, driven almost entirely by teachers over the minimum retirement age of 55, whose turnover rate doubled from 17 to 35 percent. Such teachers faced strong incentives to retire before the end of pre-existing collective bargaining agreements in order to secure collectively-bargained retirement benefits (e.g. healthcare), which no longer fell under the scope of collective bargaining after the Act. I find much more modest long-run increases in teacher turnover, consistent with previous estimates of labor supply elasticities. I then attempt to evaluate the effect of the wave of retirements following Act 10 on education quality using grade-level value-added metrics. I find suggestive evidence that student academic performance increased in grades with teachers who retired following the reform, and I obtain similar results when instrumenting for retirement using the pre-existing age distribution of teachers. Differences in value-added between retirees and their replacements can potentially explain some, but not all, of the observed academic improvements.
</small><br><br/></div>

[act10-draft]:{{ site.baseurl }}{% link assets/files/roth_act10.pdf %}


# <center> Published and Forthcoming Papers </center>
- - -

**Inference for Linear Conditional Moment Inequalities** (with Isaiah Andrews and Ariel Pakes). 2022.
*Forthcoming, Review of Economic Studies*
<br/>
<small>[ <a href="#/" onclick="visib('arp')">Abstract</a> | [Draft][arp-draft] |  [Previous version][arp-arxiv-v1] | [Matlab package][arp-code]    ] </small>

<div id="arp" style="display: none; text-align: justify; line-height: 1.2" ><small>
We show that moment inequalities in a wide variety of economic applications have a particular linear conditional structure. We use this structure to construct uniformly valid confidence sets that remain computationally tractable even in settings with nuisance parameters. We first introduce least favorable critical values which deliver non-conservative tests if all moments are binding. Next, we introduce a novel conditional inference approach which ensures a strong form of insensitivity to slack moments. Our recommended approach is a hybrid technique which combines desirable aspects of the least favorable and conditional methods. The hybrid approach performs well in simulations calibrated to Wollmann (2018), with favorable power and computational time comparisons relative to existing alternatives.
</small><br><br/></div>

[arp-draft]:{{ site.baseurl }}{% link assets/files/arp-draft.pdf %}
[arp-draft-v1]:{{ site.baseurl }}{% link assets/files/arp-draft-v1.pdf %}
[arp-supp-v1]:{{ site.baseurl }}{% link assets/files/arp-supp-v1.pdf %}
[arp-code]: https://github.com/jonathandroth/LinearMomentInequalities
[arp-arxiv-v1]: https://arxiv.org/pdf/1909.10062v1.pdf




**When Is Parallel Trends Sensitive to Functional Form?** (with Pedro Sant'Anna). 2021.
*Forthcoming, Econometrica*
<br/>
<small>[ <a href="#/" onclick="visib('ptinvariance')">Abstract</a> | [Draft][pt-arxiv] | [Initial version (old)][pt-arxiv-v1] ] </small>

<div id="ptinvariance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper assesses when the validity of difference-in-differences depends on functional form. We provide a novel characterization: the parallel trends assumption holds under all strictly monotonic transformations of the outcome if and only if a stronger "parallel trends"-type condition holds for the cumulative distribution function of untreated potential outcomes. This condition for parallel trends to be insensitive to functional form is satisfied if and essentially only if the population can be partitioned into a subgroup for which treatment is effectively randomly assigned and a remaining subgroup for which the distribution of untreated potential outcomes is stable over time. These conditions have testable implications, and we introduce falsification tests for the null that parallel trends is insensitive to functional form.
</small><br><br/></div>

[pt-arxiv]:{{ site.baseurl }}{% link assets/files/2010.04814.pdf %}
[pt-arxiv-v1]:{{ site.baseurl }}{% link assets/files/2010.04814_v1.pdf %}



**[Pre-test with Caution: Event-study Estimates After Testing for Parallel Trends](https://pubs.aeaweb.org/doi/pdfplus/10.1257/aeri.20210236)**. 2022. *American Economic Review: Insights*
<br/>
<small>[ <a href="#/" onclick="visib('pretest')">Abstract</a> | [Paper][pretest-draft] | [Appendix][pretest-appendix] | [R package][pretrends-package] | [Shiny app][pretrends-shiny] | [Longer Version (old)][pretest-draft-longer] | [Replication][codeocean-link] ] </small>

<div id="pretest" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper discusses two important limitations of the common practice of testing for pre-existing differences in trends (''pre-trends'') when using difference-in-differences and related methods. First, conventional pre-trends tests may have low power. Second, conditioning the analysis on the result of a pre-test can distort estimation and inference, potentially exacerbating the bias of point estimates and undercoverage of confidence intervals. I analyze these issues both in theory and in simulations calibrated to a survey of recent papers in leading economics journals, which suggest that these limitations are important in practice.  I conclude with practical recommendations for mitigating these issues.
</small><br><br/></div>

[pretest-draft]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing.pdf %}
[pretest-appendix]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing_appendix.pdf %}
[pretest-draft-longer]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing_longer_version.pdf %}
[pretrends-package]:https://github.com/jonathandroth/pretrends#pretrends
[pretrends-shiny]:https://github.com/jonathandroth/PretrendsPower#pretrendspower
[codeocean-link]: https://codeocean.com/capsule/9953973/tree/v1


**[An Outcome Test of Discrimination for Ranked Lists](https://dl.acm.org/doi/10.1145/3531146.3533102)** (with Guillaume Saint-Jacques and YinYin Yu). 2022. *2022 ACM Conference on Fairness, Accountability, and Transparency (FAccT 2022)*
<br/>
<small>[ <a href="#/" onclick="visib('outcometest')">Abstract</a> | [Paper][outcometest-draft] ] </small>

<div id="outcometest" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper extends Becker (1957)'s outcome test of discrimination to settings where a (human or algorithmic) decision-maker produces a ranked list of candidates. Ranked lists are particularly relevant in the context of online platforms that produce search results or feeds, and also arise when human decisionmakers express ordinal preferences over a list of candidates. We show that non-discrimination implies a system of moment inequalities, which intuitively impose that one cannot permute the position of a lower-ranked candidate from one group with a higher-ranked candidate from a second group and systematically improve the objective. Moreover, we show that that these moment inequalities are the \textit{only} testable implications of non-discrimination when the auditor observes only outcomes and group membership by rank. We show how to statistically test the implied inequalities, and validate our approach in an application using data from LinkedIn.
</small><br><br/></div>

[outcometest-draft]: https://facctconference.org/static/pdfs_2022/facct22-29.pdf



**[Why Do Sectoral Employment Programs Work? Evidence from WorkAdvance](https://www.journals.uchicago.edu/doi/abs/10.1086/717932)** (with Lawrence F. Katz, Richard Hendra, and Kelsey Schaberg).  2022. *Journal of Labor Economics*
<br/>
<small>[ <a href="#/" onclick="visib('workadvance')">Abstract</a> | [Paper][workadvance-paper] ] </small>

<div id="workadvance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper examines the evidence from randomized evaluations of sector-focused training programs that target low-wage workers and combine upfront screening, occupational and soft skills training, and wraparound services.  The programs generate substantial and persistent earnings gains (12 to 34 percent) following training. Theoretical mechanisms for program impacts are explored for the WorkAdvance demonstration. Earnings gains are generated by getting participants into higher-wage jobs in higher-earning industries and occupations not just by raising employment. Training in transferable and certifiable skills (likely under-provided from poaching concerns) and reductions of employment barriers to high-wage sectors for non-traditional workers appear to play key roles.
</small><br><br/></div>

[workadvance-paper]:{{ site.baseurl }}{% link assets/files/krhs_sectoral_jole_final.pdf %}

**[Bias In, Bias Out? Evaluating the Folk Wisdom](https://drops.dagstuhl.de/opus/volltexte/2020/12022/pdf/LIPIcs-FORC-2020-6.pdf)** (with Ashesh Rambachan). 2020. *1st Symposium on the Foundations of Responsible Computing (FORC 2020)*
<br/>
<small>[ <a href="#/" onclick="visib('biasinbiasout')">Abstract</a> | [Paper][biasinbiasout-draft] ] </small>

<div id="biasinbiasout" style="display: none; text-align: justify; line-height: 1.2" ><small>
We evaluate the folk wisdom that algorithmic decision rules trained on data produced by biased human decision-makers necessarily reflect this bias. We consider a setting where training labels are only generated if a biased decision-maker takes a particular action, and so "biased" training data arise due to discriminatory selection into the training data. In our baseline model, the more biased the decision-maker is against a group, the more the algorithmic decision rule favors that group. We refer to this phenomenon as bias reversal. We then clarify the conditions that give rise to bias reversal. Whether a prediction algorithm reverses or inherits bias depends critically on how the decision-maker affects the training data as well as the label used in training. We illustrate our main theoretical results in a simulation study applied to the New York City Stop, Question and Frisk dataset.
</small><br><br/></div>

[biasinbiasout-draft]:{{ site.baseurl }}{% link assets/files/bias-in-bias-out-final.pdf %}


# <center> Comments </center>
- - -
**Comments and Revised Findings for "Procedural justice training reduces police use of force and complaints against officers"** (with Pedro Sant'Anna, George Wood, Andrew Papachristos, and Tom Tyler). 2020.
<br/>
<small>[ <a href="#/" onclick="visib('woodetal')">Abstract</a> | [Initial Letter][woodetal-letter] | [Reanalysis][woodetal-reanalysis] ] </small>

<div id="woodetal" style="display: none; text-align: justify; line-height: 1.2" ><small>
Pedro Sant'Anna and I discovered a statistical error in a recent PNAS paper by Wood, Papachristos, and Tyler that led to spuriously large estimates of the effect of a procedural justice training for police officers. Below are links to our initial letter to the authors detailing the problem and to a re-analysis co-authored with the original authors that corrects the statistical error.
</small><br><br/></div>

[woodetal-letter]:{{ site.baseurl }}{% link assets/files/Wood-et-al-comment-20200714.pdf %}
[woodetal-reanalysis]:{{ site.baseurl }}{% link assets/files/wood-et-al-revisited.pdf %}


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
