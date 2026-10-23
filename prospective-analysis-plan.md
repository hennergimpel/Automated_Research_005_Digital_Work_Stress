# Prospective analysis plan: monitoring when the means of doing the work are missing

Prepared 23 October 2026 for Project 005. Version T004.1, submitted for independent scientific review before posting or analysis. This is the complete posting payload, including the analysis specification, exact measurement decisions, precision calculations and contribution rationale below. No new-study tests have been performed.

## Posting destination and status

User-designated public repository: https://github.com/hennergimpel/Automated_Research_005_Digital_Work_Stress . R00 reports that this repository has been created; this producer did not create it, inspect its contents or upload anything. Suggested repository filename: `prospective-analysis-plan.md`. The GitHub publication receipt, exact commit ID, provider timestamp and content hash are not yet available. A local file or empty repository does not establish prospective posting.

The user's instruction, “Let us post that plan on GitHub prior to analysis”, replaces the inherited OSF step for this project. The later instruction is to create a repository in the user's GitHub account and use it for replication materials as well. No OSF login or OSF registration receipt is required for this route. We will describe the action as prospective public posting of an analysis plan on GitHub, not as an OSF registration, a Registered Report, an immutable registry guarantee, or a workshop mandate. No analysis precedes the accepted plan's actual public commit.

Before posting, R00 must link the independent review and resolve all major scientific findings. The posted commit must contain this complete accepted plan, including any explicitly versioned pre-analysis revisions. Record the provider time and immutable content identifiers in the separate receipt; do not invent those facts inside the prepared payload. Preserve the original plan commit when code and results are later added. Any later plan revision must state whether new-study analyses had already begun.

## Plain-language study summary

Digital technology may make professional performance visible while failing to supply the tools or access rights needed to accomplish the work. We propose a bounded test of whether perceived technology nonavailability amplifies the association of performance monitoring with later exhaustion more than it amplifies the association of privacy intrusion. The data can test an observed-score interaction signature, not identify accountability, sanctions or a causal mechanism.

We will use the existing German validation sample from Gimpel and colleagues' digital hindrance stressors study: source-documented n=1,560, stressors measured in March 2019, exhaustion in May 2020. There is no baseline exhaustion. We will not infer changes in exhaustion, causal effects, recovery processes or pandemic effects. The primary estimand is the difference between the nonavailability-by-monitoring and nonavailability-by-privacy interaction coefficients in a fully specified quadratic observed-score association model. Support requires a positive monitoring interaction and positive difference; null, contrary, unestimable and inconclusive outcomes will be reported.

## Existing-data and prior-knowledge disclosure

These data already existed, had been published, and were downloaded on 22 October 2026 for a technical data-accessibility and analytics-software test. The user has clarified that the new study was not developed or tested in that earlier exercise. We retain that distinction. The technical exercise nevertheless processed real data: schema/range/missingness/duplicate profiles, reliability/covariance diagnostics, two short-form CFAs, a validation SEM, and a five-composite OLS. An initial unadjusted diagnostic SEM was superseded after review of age/gender adjustment. The historical processing and correction remain disclosed; no new chat or random split erases them.

The present full-first-order interaction question and tests were not selected or executed in that technical exercise. Literature/design workers used documentation, published results and technical-exposure descriptions; the present design worker did not open participant observations or compute empirical associations. Its precision calculations use explicit analytic assumptions and published metadata only. We therefore describe future work as prospectively specified secondary analysis with prior technical processing, not an untouched independent holdout, data-naive study, retrospective preregistration of collection, or external replication. Any outcome-adaptive follow-up will be labeled exploratory.

## Data pin, rights and local-only handling

Source: Gimpel, H., Lanzl, J., Regal, C., Urbach, N., Becker, J., and Tegtmeier, P. (2025), *Stress from Digital Work: Toward a Unified View of Digital Hindrance Stressors*, Information Systems Research 36(2), 896–915, https://doi.org/10.1287/isre.2022.0691 . Repository: https://doi.org/10.17605/OSF.IO/7YJQ4 ; component https://osf.io/vf2gz/ . Required file: `3_Validation_Sample.csv`, version 1, https://osf.io/download/yur6x/?version=1 ; SHA-256 `5709b42c802e07e0eeeecc2e67aa642c31781ff96ec1700ecf1de69ef4d2186b`, 372,976 bytes, historically acquired 2026-10-22T20:11:27.027972+00:00.

The repository README and license state CC BY 4.0 for the data and scripts, permit further analyses and require attribution. License: https://creativecommons.org/licenses/by/4.0/ . The article itself carries a separate CC BY-NC notice. This project makes no claim of endorsement, new institutional approval, waiver or exemption. Exact original public-secondary-reuse consent and a new institution-specific determination are not supplied. This plan is limited to local secondary analysis without contact, intervention, identity linkage or reidentification. Copyright permission and privacy rights are distinct. No raw/derived participant rows, individual IDs, private credentials or signed delivery URLs will be uploaded; code, source access instructions and non-identifying aggregates will enable replication. The full scope and attribution obligations are specified in the analysis plan below.

## Frozen component integrity

The following SHA-256 values identify the local component texts embedded verbatim below. The final payload's own hash belongs in the posting receipt rather than inside itself. If review changes a component, regenerate this payload and all affected hashes before posting.

- `06_Concept/T004/contribution.md`: `9193635d7c226a0e6f4b3637a6af56aa1cf247f47ec9cd3d021c5f9973784218`
- `10_Analysis/T004/analysis_plan.md`: `d22f2b0d8509c826d61f522b78cb8fa2b51e5a2902c8e31299cb7d65f952aecb`
- `10_Analysis/T004/measurement_decisions.md`: `9b6aaa32d82ea60b4abd03b0f5f8e3863e420a68f8bc826f238e93735edc2f3e`
- `10_Analysis/T004/precision_feasibility.md`: `2c13ed592fb017b26f8c48092208e72cff4076f18dcd29a725b6793bb9036a0a`

Additional source documentation pins:

- Seed PDF SHA-256: `58e2e70f9eba55253f5084e93d6ff74dbdd435c043afeee525e7889b45db141d`.
- Supplement PDF SHA-256: `e64c3b168cb88bd7b8c38f383ebbbee0bcf81694ca8b85b025142110bbfbf6c5`.
- Validation R documentation v2 SHA-256: `54688dd4963e4b0962c9704f3e9aac484f2b7f98db068442b9ef07ec51d23964`.
- T003 measurement dictionary snapshot SHA-256: `5ae7946b378e12b3f076fffd22af68ccb3b35cd706fc6805e6b83d926099c78b`.
- The dictionary reconstructs the sample-3 extensive scales from the published supplement and script, with the parsimonious-script discrepancy explicitly documented. Original German wording is not supplied; published English wording is a translated representation.

## Full scientific specification

The following sections are the complete planned work, not empirical findings. Their production/review labels preserve chronology. Independent review and a public commit must precede the first new-study test.


---

# T004 prospective analysis plan

Version 1, 23 October 2026. Status: produced for independent review. No new-study tests have occurred. Freeze the accepted version and post it to GitHub before analysis, as explicitly requested by the user. A GitHub commit is a public time-stamped version of a plan, not an OSF registration or a guarantee that history can never be altered. Preserve exact repository URL, commit ID, file hashes and provider time in the later readiness record.

## 1. Question, population and inferential classification

Question: does perceived nonavailability of needed digital technologies amplify the association of performance monitoring with later exhaustion more than it amplifies the association of privacy intrusion? This tests the observable signature of a proposed accountability-under-constraint account against additive and undifferentiated-surveillance accounts.

Population directly described: complete measured respondents in the released German validation sample. Source documentation reports 1,560 people, DHS in March 2019 and exhaustion in May 2020. One row is one person. No new sampling, recruitment, pooling, weighting or holdout split. No organization key, baseline exhaustion, repeated DHS, baseline-only attriters, treatment assignment, or individual wave dates are established. The period crosses pandemic onset. The target is a between-person lagged conditional association; it is not an effect on change, a causal effect, a within-person process, an AI-use study, a COVID study, or an external replication.

Classification: **prospectively specified new analysis of existing data with disclosed prior technical processing**. The user clarified that earlier work checked accessibility and analytics software and did not develop or test this study. Historical processing nevertheless included data profiles, reliability/covariance diagnostics, two short-form CFAs, a validation SEM and a five-composite OLS. None tested the present full-first-order interaction contrast. Published results and technical-processing knowledge are prior information. The present author did not read rows or fit new-study models. Do not describe the source sample as data-naive or an untouched holdout. Any analyses changed after outcome inspection are exploratory deviations, irrespective of a new chat or random split.

## 2. Source, provenance and permitted reuse

Only `3_Validation_Sample.csv` v1 is eligible. Source repository DOI: 10.17605/OSF.IO/7YJQ4; component vf2gz; version URL https://osf.io/download/yur6x/?version=1. Historical acquisition: 2026-10-22T20:11:27.027972+00:00; 372,976 bytes; SHA-256 `5709b42c802e07e0eeeecc2e67aa642c31781ff96ec1700ecf1de69ef4d2186b`. Existing local source is package `09_Development/open_data_capability/source/3_Validation_Sample.csv`. No new download is needed or authorized by this worker.

After review and posting, R08/R09 must explicitly promote an unchanged local copy to project `09_Data/raw/T004/3_Validation_Sample.csv` (or record an immutable reference to the existing file if copying is unnecessary). The promotion receipt must state source and destination absolute/project-relative paths, byte sizes, SHA-256 values, copy/reference operation, UTC, actor, source version, and this accepted plan/hash. Source and destination hashes must equal the pinned hash; retain the development original. This is reconciliation of already obtained data, not a retroactive pre-acquisition gate or a fresh collection. A different version requires a new documented decision before use.

README and repository license explicitly permit further analysis under CC BY 4.0. Cite the seed paper/repository, preserve attribution/license/modification notices and do not imply endorsement. The article has its separate CC BY-NC notice. The minimal-data reuse scope is local statistical analysis of already published survey data, with no recruitment, contact, intervention, identity linkage, or reidentification. Published procedures describe anonymous collection with demographic exceptions; exact secondary-use consent text and an institution-specific determination are not supplied. No institutional approval, exemption, waiver or receipt is asserted, and no unsupported new approval requirement is invented. Copyright permission does not resolve every privacy right. Keep raw and derived rows local; publish source access instructions and non-identifying aggregates rather than redistributing respondents. This is the documented applicability decision for this narrowly defined activity, subject to any actual applicable institutional direction encountered later.

## 3. Eligibility and validation rules

1. Verify source hash before parsing. Treat the source R scripts as documentation; do not run their install/load/download directives or inherit their score calculations.
2. Require the documented sample-3 fields, 60 items, age, gender and label, and a unique nonmissing within-file ID. Expected source dimensions are 1,560 rows/71 fields. A discrepancy, duplicate ID, inconsistent numeric/label mapping, unexpected item code or failed hash stops dependent analysis for documented resolution; do not delete duplicates or force agreement. Additional irrelevant columns are not used.
3. Item validation, missingness, means and the full map are fixed in `measurement_decisions.md`. No item or person exclusion based on exhaustion level, residuals, multivariate outliers, response uniformity or later significance. Preserve valid extreme responses.
4. Primary cohort: all rows complete on 60 items plus valid age/gender. Age must be finite and in the physically plausible interval 0–120 years; values outside it are source errors to resolve rather than automatic exclusions. A value inconsistent with adult employment is flagged and resolved from source documentation before analysis, not silently corrected. Unknown demographics are missing, not guessed. Report a transparent flow from release rows through validation to eligible rows.
5. If a required score SD is zero, the primary contrast is undefined. If the model is rank-deficient for the target contrast, residual degrees of freedom are below 200, or a leverage value is at least 0.99, do not replace the primary estimator with a simpler significant model. Report primary nonestimability and the reason; any replan needs a fresh prospective version and is no longer the original test.

Complete-case results concern that cohort. No assertion of missing-at-random or correction for attrition follows. The prorating sensitivity is compulsory if incomplete item rows exist. Missingness or data-validation decisions are logged as actual post-posting exposure; they must not become unreported hypothesis changes.

## 4. Variables, estimand and theory restrictions

Use the 12 published first-order mean scores in this fixed order: INV, OVE, COM, INS, UNC, UNR, ROL, IOP, INT, PER, NON, LSA. Standardize the completed scale means to Z_j; standardize the mean of EMO01–09 to Y. Let A=Z_NON, M=Z_PER, P=Z_IOP. No other outcome is primary or secondary.

For the release population defined above, the estimand is the coefficient contrast in the least-squares projection of standardized later exhaustion onto the fixed quadratic feature basis and demographic adjustment. It is well-defined as an observed-score association even if the conditional mean is not exactly quadratic. A process interpretation additionally requires that the functional approximation is adequate and that alternative confounding/measurement explanations are sufficiently limited; the design cannot establish the latter.

Fit:

`Y = alpha + sum_j b_j Z_j + sum_j q_j Z_j^2 + sum_{j<k} g_jk Z_j Z_k + c1 Age10 + c2 Age10^2 + gender indicators + error`

where Age10=(age−sample mean age)/10. The model includes 12 first-order terms, 12 own-squares and **all 66 distinct pair products**, plus intercept/demographics. Typical male/female coding gives 94 fitted columns and 1,466 residual degrees of freedom if n=1,560 and full rank. All stressor terms stay regardless of their estimates or significance. This is a descriptive adjustment for co-occurrence, not a claim that simultaneous stressors are a valid causal control set.

Primary specificity contrast: `theta = g_NON,PER − g_NON,IOP`. Required companion: `gamma = g_NON,PER`. Let S=(M+P)/2 and D=(M−P)/2. Theta is the A×D coefficient: how the monitoring-versus-privacy profile contrast changes with nonavailability, keeping S and the other scores fixed. In the quadratic model it is also the difference between mixed partial derivatives with respect to A,M and A,P.

For an interpretable illustration, consider A=−0.5 versus +0.5 and two surveillance profiles `(M,P)=(+0.5,−0.5)` versus `(−0.5,+0.5)`, with other Z values at zero and common demographics. The difference in the two profiles' exhaustion difference between the two A levels equals theta outcome SD. The separate four-corner A×M difference with P and other scores fixed equals gamma. These are modeled between-person profile contrasts, not intervention predictions.

**H1 (conjunctive signature): gamma>0 and theta>0.** Both must be supported. Positive theta alone is insufficient if it arises only from a negative A×P association. **Practical target:** delta=0.20 outcome SD for theta's declared profile contrast. This margin is an explicitly chosen research threshold for consequential diagnostic differentiation, not a validated clinical minimum. Continuous intervals remain central; smaller effects may still be interesting but cannot be called consequential at this margin.

Rival R1: all pair interactions zero (additive heterogeneous demands, allowing own-curvature); it predicts gamma=theta=0. Rival R2: A interacts with S but not D (undifferentiated surveillance complementarity); it allows gamma>0 but predicts theta=0. Equal-weight quadratic total standardized burden also predicts equal pair cross-coefficients and theta=0. These restrictions are not attributed to the seed. Unequally weighted latent burden, differential measurement error or unmeasured common causes need not obey theta=0 and remain alternatives even if H1 is supported.

## 5. Estimation, uncertainty and multiplicity

**Estimator choice.** A five-domain regression cannot separate performance monitoring from privacy intrusion; a purely additive twelve-score model cannot test the proposed contingency. A reduced three-score interaction model would be more precise but could assign omitted cross-curvature from other demands to the focal pair. The full quadratic is selected before outcomes to allow every such second-order term. A latent moderated structural model could address measurement error under additional distributional and measurement assumptions, but would target a different latent estimand, require a substantially more complex interaction measurement model, and still would not identify accountability or remove prior-exhaustion confounding. We therefore deliberately target transparent observed-score contrasts, retain full scales and prespecified measurement sensitivities, and bound conclusions accordingly. No data-driven estimator competition, penalized variable selection, factor-score substitution, or automatic migration to a latent model is planned. Failure of the observed-score design is a failure/replan, not permission to switch estimands.

Fit ordinary least squares using stable QR/SVD numerical linear algebra. Estimate a heteroskedasticity-robust HC3 covariance and report gamma, theta, their covariance, standard errors and two-sided 95% t intervals with n−rank degrees of freedom. HC3 is a diagnostic cross-check; **the prespecified primary intervals are respondent-pairs bootstrap percentile intervals**, which re-estimate standardization and the model in each resample.

Bootstrap: exactly 1,999 resamples of n persons with replacement; deterministic seed 2026102305; no cluster resampling because no cluster key is available. Within each replicate recompute all sample means/SDs, age centering, all polynomial terms and the fit; retain a replicate only if required score SDs are positive and gamma/theta are estimable. Gender factor levels are fixed to the original eligible set; an absent category's all-zero nuisance column may be omitted within a replicate. Do not replace failed draws with extra draws. At least 1,900 valid draws are required for primary bootstrap intervals; otherwise report failure and HC3 results as sensitivity only. Use the empirical quantile definition equivalent to R type=7 / NumPy linear. Report invalid draw counts and reasons, seeds and software versions. Record all raw-data processing locally; do not publish sampled rows.

Primary 95% intervals use percentiles 2.5 and 97.5; the equivalence interval for theta uses percentiles 5 and 95. The latter is the interval form of two one-sided tests at alpha .05, with the usual bootstrap approximation. H1 support requires both 95% lower limits greater than zero. This is an intersection–union claim: both component conditions must pass; no family of 66 discovered interactions is tested. Requiring two 95% intervals is conservative for the directional conjunction. Do not treat nuisance pair coefficients as a discovery family, rank significant ones, or promote them to hypotheses.

A consequential specificity claim requires theta's 95% lower limit >0.20 **and** gamma's 95% lower limit >0. Report as positive but not established consequential when H1 passes but this stronger rule fails. Evidence against materially positive specificity is theta's 95% upper limit <0.20. Equivalence at the declared margin requires the entire 90% interval inside [−0.20,+0.20]; it does not establish literal equality or equivalence of latent constructs. A 95% upper limit <0 contradicts the predicted ordering. Wide intervals mean inconclusive. All classification rules are reported, not selected post hoc. No p-value is required to report the interval-based primary decision.

All robustness analyses concern this same prespecified contrast, are reported jointly, and cannot replace a failed primary result. No separate confirmatory claim is drawn from their nominal intervals. Any other outcome, subgroup, selected pair interaction, new item subset, new latent profile or adaptive prediction analysis is explicitly exploratory and outside the planned primary article.

## 6. Support, diagnostics and compulsory sensitivity analyses

**Support before interpretation.** Report sample size, scale distributions, PER–IOP correlation, focal three-dimensional support, standardized design condition number, rank, residualized contrast information, leverage and robust/bootstrapped interval widths. For the illustrative theta profiles, count observations in each of four disjoint cubes: A in [−1,0) or [0,1], and either M in [0,1], P in [−1,0) or M in [−1,0), P in [0,1]. Counts refer only to the three focal scores, so they do not prove overlap in all 12 dimensions. Require at least 25 respondents in each cube before labeling the illustrated moderate profiles empirically supported. Otherwise retain the projection estimate but label the profile interpretation support-limited; do not relocate the profiles to prettier quantiles. Also give background-score ranges/standardized differences across cubes without claiming exchangeability. Suppress public subgroup tables if they permit identifying combinations; these focal counts need contain no demographic linkage.

**Numerical diagnostics.** Report a condition number after scaling every nonconstant model column to unit SD; >1e8 is a numerical-instability flag requiring independently checked linear algebra before any inferential conclusion. A large but estimable SE is substantive weak information, not justification to remove covariates/interactions. Plot residual-versus-fitted and observed-versus-fitted distributions; record predictions outside the possible exhaustion range after back-transformation. These plots diagnose model limitations, not a model-selection tournament.

Perform these fixed sensitivities regardless of primary significance, unless explicitly conditional below:

1. **Units.** Refit using all 12 unstandardized 0–4 scale means centered at their primary means, with the same outcome standardization and full quadratic specification. Report the corresponding theta/gamma per one response-unit changes. It addresses whether the primary ordering depends on different SD units. Do not apply the standardized 0.20 margin to this different unit. A sign reversal limits the claim to the original standardized comparison.
2. **Published item-loadings.** Replace the mean for each of the three focal scales with the sum of item×published standardized loading divided by the sum of loadings, then standardize and refit the full model; keep background and outcome means unchanged. Weights from Supplement Table 22 are NON=(.83,.83,.82,.90,.84,.84), PER=(.78,.80,.88,.83,.87,.79), IOP=(.93,.95,.92), in their stated code order. This is a prespecified measurement sensitivity, not an error-free factor estimate; the loadings come from the already published same source sample and are not independent validation. No weights are refitted to exhaustion.
3. **Functional form.** Add all ten distinct total-degree-three monomials in (A,M,P), plus T^3 and T^4 where T is the mean of the 12 standardized scores. Keep every primary term. Evaluate the **same four-profile finite contrast** for theta, and the A×M four-corner contrast at ±0.5 with P=0 for gamma, using predictions and recomputing these contrasts in the bootstrap. This preserves the interpretive target when curvature is no longer constant. T is a transparent equal-weight burden summary, not the original DHS latent score. It challenges cubic focal and higher total-burden curvature but cannot eliminate every functional-form rival.
4. **Influence.** Refit the primary specification after excluding rows with primary leverage h_i>3p/n, where p is fitted rank, then recompute scaling. Report the number removed and both contrasts. This deterministic influence sensitivity does not replace the inclusive primary cohort; genuine extreme observations remain in the primary estimate. Do not identify individual cases in released outputs.
5. **Demographic specification.** Refit without age/gender. This shows dependence on their uncertain variable-specific timing and on descriptive adjustment; it does not establish causal robustness.
6. **Incomplete-item scoring.** If any item-incomplete respondents exist, run the fixed 80% per-scale prorating sensitivity from the measurement decisions. No outcome-dependent missing-data model or imputation search.

Use the same 1,999-draw bootstrap algorithm/seed for sensitivities, with each analysis cohort's size and scaling, and report their valid-draw counts. A robust-score variant failing estimation is reported as failed, not silently omitted. For all analyses, if resampling demonstrates expensive computation, retain the specified draw count; report interruption rather than reduce it after seeing results.

The theoretical interpretation is **fragile** if theta or gamma changes sign in any required estimable sensitivity, if the primary H1 classification fails under the functional-form sensitivity, or if support requirements fail. Loss of nominal significance in smaller sensitivity samples alone is not a sign reversal and is reported with interval widths. Agreement does not resolve prior exhaustion, differential measurement error, common reporting dispositions, occupation, job control or pandemic-related change. There is no validated negative control or instrument in these data.

## 7. Missingness, dependence, selection and generalization

Missing-item/covariate losses, release selection and follow-up attrition are distinct. Report known denominators and unknown baseline attrition explicitly; do not infer a response rate from the released complete sample. Complete-case and prorating estimands are different, so differences may reflect selection as well as scoring. There is no released basis for inverse-probability correction of baseline attrition. Bootstrap/HC3 assume independent people; recruitment through a panel does not establish organization-level independence. No cluster IDs or weights will be invented. Hidden clustering can make intervals too narrow and remains an explicit limitation.

Standardized mean scores are fallible ordinal-item summaries. Arithmetic means are fixed operationalizations, not proof of interval latent measurement. The same questionnaire wave measures the 12 stressors, and stable negative affect or prior exhaustion can generate both main and interaction associations. A 14-month lag does not remove these alternatives. A result pertains to the sampled German digital workers and historical period; no prevalence or policy-benefit estimate for today's workforce follows.

## 8. Fixed-data precision and stopping

Sample size is fixed by the pinned release; no optional stopping or addition of another source sample. `precision_feasibility.md` contains analytic, metadata-only scenario calculations, including a covariance constructed from published hierarchy/loadings under explicit normality and reliability assumptions. They are not new empirical estimates or observed power. At documented n=1,560 they indicate reasonable resolution for some moderate specificity contrasts and poor resolution under high collinearity. Neither a detectable-effect calculation nor the known aggregate DHS–exhaustion association guarantees H1 power. No sample split is created to simulate independence or to make an unexposed holdout claim.

Proceed to the registered test only after independent review accepts this contribution/precision tradeoff. If the reviewer concludes that moderate observed-score discrimination cannot justify the theory claim, reject/replan before accessing outcomes. After posting, failed support, nonestimability, wide intervals and null results remain reportable outcomes of the frozen plan. Do not search other pairs to rescue publishability.

## 9. Reproducibility, outputs and deviations

The analysis worker must record plan/source/dictionary/code hashes; source promotion receipt; data validation/flow; package/runtime versions; run UTC; random seed; warnings; execution failures; actual invocation/model/usage where exposed; and all primary/sensitivity outputs. Central output keys should include n_release, n_primary, n_missing_excluded, model_rank, theta, gamma, HC3 covariance, bootstrap interval limits/valid draws, support counts, practical/equivalence classification and sensitivity statuses. Derived rows, IDs and case diagnostics remain local.

Public replication materials later comprise readable code, environment/run instructions, pinned source URL/hash/version, dictionary attribution, frozen plan commit and deviations, non-identifying result tables and manuscript claim mapping. Do not copy access tokens, signed download URLs, credentials, raw rows or private workflow paths into GitHub. A later code/results commit must retain a link to the earlier plan commit. Plan edits after the initial post require new commits and explicit chronology; edits after any new-study analysis cannot be represented as prospectively fixed.

## 10. Readiness prerequisites

Current readiness is false. Required before tests: independent accepted contribution/design review; review resolutions in a frozen accepted version; truthful minimal-data applicability record (this plan's bounded determination, accepted in review); exact GitHub-hosted plan/attachment commit with matching local hashes and provider time; source promotion/integrity receipt; R00's documented existing-data analysis-stage readiness decision. No OSF login, OSF registration receipt or new acquisition-stage gate is required for the user-selected GitHub route. The destination choice is a documented project-specific user override of the inherited workflow, not an assertion that GitHub is an immutable registration provider or that the workshop requires registration.


---

# T004 frozen-for-review measurement decisions

Version 1, 23 October 2026. Proposed specification; independent acceptance and prospective GitHub posting must precede new-study tests. No participant observations were opened or scored in this task.

## Instrument and exact maps

Use the established **extensive sample-3 first-order scales**, expressed as manifest arithmetic means. These are transparent observed scores, not estimated latent factor scores, the seed's third-order DHS parameter, or a newly validated psychometric scale. Use all original items within every scale; no outcome-based item selection or reliability-based deletion.

| Symbol/code | Items | Role |
|---|---|---|
| INV | INV01, INV02, INV03 | Background first-order demand |
| OVE | OVE01, OVE02, OVE03, OVE04 | Background demand |
| COM | COM01, COM02, COM03, COM04, COM05 | Background demand |
| INS | INS01, INS02, INS03, INS04 | Background demand |
| UNC | UNC01, UNC02, UNC03, UNC04 | Background demand |
| UNR | UNR01, UNR02, UNR03 | Background demand |
| ROL | ROL01, ROL02, ROL03, ROL04 | Background demand |
| IOP / P | IOP02, IOP03, IOP04 | Focal privacy intrusion comparator |
| INT | INT01, INT02, INT03 | Background demand |
| PER / M | PER01, PER02, PER03, PER04, PER05, PER06 | Focal performance monitoring |
| NON / A | NON01, NON02, NON03, NON04, NON05, NON06 | Focal nonavailability |
| LSA | LSA01, LSA02, LSA03, LSA04, LSA05, LSA06 | Background demand |
| EMO / Y | EMO01 through EMO09 inclusive | Sole outcome: later exhaustion |

Evidence: T003 dictionary, Supplement Tables 14 (pp. 26–27), 21 (p. 32), 22/24 (pp. 33–34), and validation R v2 lines 146–167 and 322–324. Published English wording is in the dictionary; the actual German item text is not supplied. Source-described translation/back-translation is not a fresh validation here.

NON concerns necessary technologies, adequate technologies, and rights to technologies needed for work. PER concerns professional performance/achievements being observed, compared and assessed, including discoverability of mistakes. IOP explicitly concerns privacy compromise through tracking and tracing. These meanings justify the contrast; PER is not objective punitive monitoring, IOP is not a direct measure of job control, and NON is not an inventory of actual equipment. Their conjunction does not directly measure evaluative vulnerability.

Stressor items use 0–4 agreement coding; all items retain the published direction. Exhaustion also has documented 0–4 coding in validation code, but its exact anchors/recall period are unspecified. Therefore Y is a mean endorsement score for the nine published exhaustion items. Do not import the original MBI 0–6 frequency scale, diagnostic categories, or a clinical interpretation. Do not reverse UNR, NON or LSA merely because wording includes negation.

## MAP-01 resolved without using outcomes

The parsimonious source descriptive block substitutes five codes relative to Supplement Table 17 and the validation CFA/SEM. Table 17, Table 21 and Table 26 plus repeated CFA/SEM strings support the published short definition. The present full-scale decision uses all extensive items, so it neither adopts the erroneous descriptive subset nor chooses the better-fitting short subset. No short-scale result is part of the focal analysis. Splitting the two-item short surveillance scale into single-item PER and IOP would change reliability and construct coverage and is not an equivalent replication.

XW-01 remains applicable: sample-3 IOP02–04 are renumbered in benchmarking; no other sample is used. IDs are only within-file keys. Neither code similarity nor common parent study authorizes pooling.

## Scoring, scaling and missingness

Primary eligibility requires every one of the 60 items above, age, and a usable gender category. Each scale score is the mean of all its items. Z-standardize each of the 12 stressor means and the exhaustion mean in this eligible sample using the sample mean and sample SD (denominator n−1). Do not standardize individual items before averaging. Use the same means/SDs in all fixed-sample primary comparisons. In the prespecified paired bootstrap, resample people and recompute scale standardization to account for estimated scaling. Original 0–4 means and SDs will also be reported.

No score imputation is used in the primary analysis. This defines an association among complete measured follow-up respondents, not a claim about all originally recruited workers. If missingness exists, report its patterns and losses and execute the prespecified prorating sensitivity: at least ceiling(0.8×item count) observed items in **each** scale, averaging observed items, with complete age/gender. This means 3/3 for IOP, 5/6 for NON and PER, and 8/9 for EMO. Apply the same rule to all background scales. Repeat all model/scaling steps in that sensitivity cohort. It is a scoring/selection sensitivity, not proof of missing-at-random validity. No claims recover baseline attriters; their data are not established in the release.

Only empty fields and the exact token `NA` are recognized as missing at initial import. Any other nonnumeric item code, noninteger observed item value, or value outside 0–4 is an unresolved source discrepancy: stop dependent scoring and document it. Do not guess a sentinel or recode to zero. A zero is a valid response. A missing item is not evidence of careless responding.

## Demographics and validity limits

Age is in years; model (age−sample mean)/10 and its square. Gender uses the released label field and its verified one-to-one numeric/label mapping, never guessed binary numeric coding. Male is the reference if present; otherwise use lexicographic first nonmissing label. Keep other documented categories distinct in the model. Unknown or contradictory mappings require source resolution before a primary run. Gender categories with no observations create no model columns. Education, work hours, digital-use frequency and their labels are not analysis covariates; variable-specific timing is not established and they add no necessary definition to the selected contrast. Demographics are descriptive adjustment, not a claimed sufficient causal adjustment set.

Report full-scale alpha and interscale correlations descriptively after authorization, including PER–IOP separation. Do not use arbitrary alpha thresholds or fit indices to select a different scale/model. Differential reliability and construct overlap are conclusion-changing limitations. The source reports high internal consistency for these three full scales (Supplement Table 24), which supports their use over single short-form items but does not establish error-free or equal measurement. A planned loading-weighted score sensitivity and raw-unit sensitivity are defined in the analysis plan. They do not identify an error-free latent causal effect.

Privacy: keep person IDs only in local validation/lineage, omit them from analysis tables and public files. No raw/derived rows, sparse demographic cross-tabulations, individual residuals, or case-level bootstrap records go to GitHub. Public outputs are code, source access/hash instructions, plans, and non-identifying aggregate results. No external linkage, reidentification, contact or fresh participant consent collection occurs.


---

# T004 fixed-data precision feasibility

Version 1, 23 October 2026. **Analytic planning calculations only. No participant observations, empirical covariance matrix, regression, hypothesis test, or new-study outcome was read or computed.** This document contains the executed algorithm and its numerical outputs, so the calculations can be reproduced without access to the data.

## Purpose and assumptions

The release's documented maximum is n=1,560. The proposed full quadratic model uses 12 stressor means, all 12 own-squares and all 66 pair products, plus age, age-squared and gender. Typical primary rank is 94. The main contrast is theta=g_NON,PER−g_NON,IOP. Precision depends on conditional variation in these products, not merely the total number of respondents. The procedure does not claim post-hoc observed power or treat the seed's aggregate association as an effect size for this new contrast.

Let Z be a hypothetical mean-zero multivariate normal 12-vector with covariance S and unit marginal variances. For product features Q_ij=Z_i Z_j, i<=j, their covariance is

`V[(i,j),(k,l)] = S[i,k] S[j,l] + S[i,l] S[j,k]`.

This follows by subtracting E[Z_i Z_j]E[Z_k Z_l] from the normal fourth moment. Centered product features are orthogonal to the linear features under this assumption. With homoskedastic residual SD sigma and independent observations, the large-sample variance of a coefficient contrast c is approximately `sigma^2 * c' inverse(V) c / n`. Here c selects NON×PER with +1 and NON×IOP with −1. The formula includes the projection against **all** other quadratic terms. Age/gender are treated as independent of these products for planning; actual dependence, ordinal bounds, skew, leverage, conditional heteroskedasticity and estimated standardization can make the approximation inaccurate. The eventual bootstrap rather than this working covariance supplies empirical uncertainty.

Two scenario families were computed:

1. Equicorrelation rho=.30,.60,.80,.90 for all 12 stressor scores, sigma=1, n=1,560/1,200/900. These are stress tests, not estimated correlations.
2. A source-informed **hypothetical** covariance. Published Supplement Table 22 supplies first-order-to-domain loadings a and domain-to-DHS loadings b. For two first-order constructs in the same domain, hypothesize latent correlation a_i a_j; for different domains, hypothesize a_i a_j b_g b_h. Then multiply off-diagonal entries by sqrt(r_i r_j), treating Table 24 alpha values r as if they were true classical score reliabilities. Diagonal entries are one. This is a transparent illustrative assumption; alpha is not known true reliability, raw means are not factor scores, and the resulting matrix is not the observed sample covariance. The published tables use this same historical sample and provide planning metadata, not new independent validation.

## Executed output

Equicorrelation scenarios, sigma=1, full n=1,560:

| Assumed rho | SE(theta) | 95% half-width | Approx. 80% two-sided MDE for theta alone | SE(gamma) |
|---|---:|---:|---:|---:|
| .30 | .0493 | .0967 | .1382 | .0337 |
| .60 | .0859 | .1684 | .2407 | .0585 |
| .80 | .1716 | .3363 | .4807 | .1167 |
| .90 | .3430 | .6722 | .9608 | .2332 |

At rho=.60, reducing n to 1,200 gives SE=.0980, half-width=.1920 and MDE=.2744; n=900 gives SE=.1131, half-width=.2217 and MDE=.3169. These are not achievable precision guarantees. MDE uses (1.959964+0.841621)SE, so it is for a scalar two-sided zero test at alpha .05 and approximate power .80. It is not joint power for the conjunction gamma>0 and theta>0, nor power for theta>.20.

Source-informed hypothetical covariance: S_NON,PER=.453747; S_NON,IOP=.421272; S_PER,IOP=.638600.

| n | Hypothetical residual SD | SE(theta) | 95% half-width | Approx. MDE | Approx. probability of equivalence at true theta=0, margin .20 |
|---|---:|---:|---:|---:|---:|
| 1,560 | 1.00 | .08381 | .16426 | .23479 | .542 |
| 1,560 | .85 | .07124 | .13962 | .19957 | .755 |
| 1,200 | 1.00 | .09555 | .18728 | .26770 | .346 |
| 1,200 | .85 | .08122 | .15919 | .22755 | .586 |
| 900 | 1.00 | .11034 | .21626 | .30912 | .133 |
| 900 | .85 | .09379 | .18382 | .26275 | .374 |

The .85 residual SD is a declared optimistic scenario, not a fitted new-model residual SD. Approximate equivalence probability is max(0, 2 Phi(.20/SE−1.644854)−1). It uses a known-SE normal approximation, not the finite-sample bootstrap actually planned. Using n rather than n−rank is asymptotic and slightly optimistic at this parameter count. The working tables omit confidence-width uncertainty and potential clustering. No Monte Carlo observations were simulated and no simulation Monte Carlo error applies; approximation error remains substantial.

## Decision implications

A moderate specificity contrast might be estimated informatively under moderate source-plausible correlations; resolving a .10-SD contrast is not assured. Even at n=1,560, equivalence within ±.20 has only about .54 probability in the conservative source-informed zero-effect scenario. With stronger collinearity or attrition, null findings will often be inconclusive. The study must not promise detection, equivalence, an adequate-power certificate or a positive contribution from the sample size alone.

The .20 margin is an investigator-declared substantive interpretation boundary for the particular 1-SD nonavailability and 2-SD monitoring-versus-privacy swap contrast, not a cutoff optimized against any empirical result. Its choice permits a bounded statement about meaningful diagnostic differentiation, not clinical importance. Reporting full intervals is compulsory. A reviewer may reject the tradeoff before analysis; after posting, wide intervals cannot justify deleting nuisance terms, changing the contrast, shrinking the margin, switching to another pair or adding another source sample.

No new money, API call or sample is needed. The main model is an ordinary quadratic regression with approximately 94 parameters; 1,999 respondent bootstraps plus six fixed sensitivities are finite, local computations. Runtime for the eventual real-data implementation has not been benchmarked here. Analytic feasibility is not a software-execution or empirical-data readiness receipt.

## Reproducible metadata-only Python

Executed with the configured bundled Python and NumPy on 23 October 2026. The code contains only declared scenarios and published constants. It reads no files and makes no network calls. Both the equicorrelation and source-informed calculations were executed locally; the consolidated code below reproduces them.

```python
import numpy as np
from math import sqrt, erf

names = ['INV','OVE','COM','INS','UNC','UNR','ROL','IOP','INT','PER','NON','LSA']
groups = ['R','O','E','R','R','B','E','S','B','S','B','E']
a = np.array([.81,1,.81,.90,.66,.70,.90,.79,.84,.86,.76,.82])
b = {'O':.85,'B':.99,'E':.97,'S':.75,'R':.89}
reliability = np.array([.82,.90,.91,.84,.89,.93,.91,.95,.91,.93,.94,.96])
pairs = [(i,j) for i in range(12) for j in range(i,12)]
idx_np = pairs.index((9,10))  # PER, NON
idx_ni = pairs.index((7,10))  # IOP, NON
c = np.zeros(len(pairs)); c[idx_np]=1; c[idx_ni]=-1
Phi = lambda z: .5*(1+erf(z/sqrt(2)))

def report(S, n, sigma=1):
    V = np.array([[S[i,k]*S[j,l]+S[i,l]*S[j,k]
                   for k,l in pairs] for i,j in pairs])
    Vinv = np.linalg.inv(V)
    se = sigma*sqrt(float(c @ Vinv @ c)/n)
    se_gamma = sigma*sqrt(Vinv[idx_np,idx_np]/n)
    return dict(n=n, sigma=sigma, se_theta=se,
                half95=1.959964*se, MDE80=2.801585*se,
                se_gamma=se_gamma,
                equivalence_at_zero=max(0,2*Phi(.20/se-1.644854)-1))

for rho in [.30,.60,.80,.90]:
    S=np.full((12,12),rho); np.fill_diagonal(S,1)
    for n in [1560,1200,900]:
        print('equicorrelation', rho, report(S,n))

S=np.eye(12)
for i in range(12):
    for j in range(i+1,12):
        latent=a[i]*a[j]*(1 if groups[i]==groups[j]
                          else b[groups[i]]*b[groups[j]])
        S[i,j]=S[j,i]=sqrt(reliability[i]*reliability[j])*latent
print('ASSUMED covariance', S[10,9], S[10,7], S[9,7])
for n in [1560,1200,900]:
    for sigma in [1,.85]:
        print('source-informed hypothetical', report(S,n,sigma))
```

The analyst must not substitute these planning numbers for observed data/results in the manuscript. The analytic formula and source-informed covariance assumption are central methodological decisions for fresh independent review.


---

# T004 contribution decision: monitoring when the means of doing the work are missing

Version 1, 23 October 2026. Producer proposal for fresh independent contribution/design review; not an accepted contribution or an empirical result. All new-study analyses below remain unperformed. The user has now requested prospective posting of the reviewed plan on GitHub before analysis, replacing this project's OSF step. That changes the posting destination, not the prospective-analysis or disclosure requirements.

## Decision and research question

Select a **bounded test of performance-specific complementarity between digital monitoring and technology nonavailability**, rather than another aggregate-versus-disaggregate comparison. The question is: **Does the association between perceived technology nonavailability and later exhaustion become stronger as performance monitoring replaces privacy intrusion within a fixed overall surveillance profile?** The proposed answer is a falsifiable theoretical prediction, not a result.

Digital systems can make work observable without giving workers the technologies or permissions needed to perform that work. We propose that this conjunction creates evaluative vulnerability: failure to deliver is visible while the means of delivery are constrained. Privacy intrusion also threatens workers, but its defining concern does not depend on accomplishing the monitored task. The proposed extension therefore predicts that nonavailability amplifies the association of performance monitoring with later exhaustion more than it amplifies the association of privacy intrusion. It also requires positive monitoring–nonavailability complementarity in its own right; a difference generated solely by a negative privacy interaction will not count as support.

This is a proposed relation among established constructs, not a newly validated scale called evaluative vulnerability. The data measure perceived monitoring, perceived privacy intrusion, perceived nonavailability, and later exhaustion. They do not measure the posited evaluation threat, sanctions, objective missing equipment, organizational accountability policy, actual job control, or coping. The analysis tests a necessary observable signature under a bounded associational model. It cannot identify the proposed causal process.

## Why this changes the theoretical question

The seed's surveillance factor combines performance monitoring and privacy intrusion. Its obstruction factor combines nonavailability, unreliability, and interruptions. The proposed relation crosses those two broad domains while distinguishing two routes within surveillance. It asks whether **the meaning of observability for exhaustion depends on the means of accomplishing observable work**, not which individual stressor has the largest main effect. A common surveillance score can summarize covariance while obscuring this contingency. That is a conditional boundary on summary use, not a rejection of the hierarchy.

At equal standardized surveillance burden, a monitoring-heavy and a privacy-heavy profile can have different exhaustion associations as nonavailability changes. Under the proposed account that difference grows with nonavailability. Under an additive account the difference may be nonzero but does not grow. Under an undifferentiated surveillance-complementarity account both surveillance components interact equally with nonavailability, so the difference again does not grow. A quadratic total-burden account with equal standardized component weights likewise produces equal cross-curvature and no such difference. The primary contrast is designed to distinguish these observable restrictions.

This does **not** distinguish the proposed process from every possible common-factor account. Unequal latent weights, differential measurement error, negative affectivity, prior exhaustion, unmeasured occupations or job control, selection, and higher-order nonlinearities can produce apparent specificity. Those alternatives must remain in the conclusions, even if the prespecified signature is found. We will not claim that significance proves accountability, mediation, or causal damage from monitoring.

## Source-grounded construction and closest-work delta

Source IDs and published versions refer to the immutable T002 registry and reading snapshots. These are substantive comparisons, not an exhaustive novelty claim.

| Evidence | What is already established | Proposed delta and remaining limit |
|---|---|---|
| S01 Gimpel et al. (2025), ISR, print pp. 904–906 and 910–912; S02 Tables 14, 21 | Broad hierarchy; obstruction concerns tasks being impeded; surveillance includes evaluation and autonomy; privacy can be stressful irrespective of work performance; dimensions are expressly noninterchangeable. | Derive a performance-versus-privacy difference in **nonavailability moderation**, retaining the hierarchy as a measurement organization. This extends the seed's own theoretical distinction; it is not a claim that the seed assumed equal effects. |
| S03 Ayyagari et al. (2011), MISQ, PDF pp. 15–18 | Technological characteristics and person–environment misfit; separate stressor–strain paths. | A conditional contrast between two surveillance components at different levels of missing technological means. Main-path differences or generic misfit alone are not the contribution. |
| S12 Nastjuk et al. (2024), EJIS, PDF pp. 11–16 | Disaggregation can reveal meaningful differences; individual roles need theoretical motivation. | Commit to one content-based interaction difference, with an additive and an equal-complementarity rival, before new tests. Not the first differentiated-stressor study. |
| S06 Maier et al. (2021), JAIS, theoretical and discussion sections | Challenge/hindrance appraisal distinctions and configurational accounts. | No claim to invent configurations; no conversion of hindrance items into measured appraisal. The focal conditional contrast and its two surveillance components are the proposed boundary. |
| S09 Day et al. (2012), JOHP, PDF pp. 12–15 | Different ICT demands and organizational supports have distinct associations/buffering relations. | Nonavailability is an established perceived demand, not a measured organizational support intervention. The account concerns observability when means are missing. |
| S07 Tarafdar et al. (2019), ISJ, PDF pp. 19–21 | IS design, distress and eustress need differentiated explanation. | Connect digital observation and task-enabling capacity in one proposition; do not infer that a particular redesign would reduce exhaustion. |
| S11 Benlian (2020), MISQ, PDF pp. 18–20; S13 Ingwersen et al. (2026), BISE, PDF pp. 12–13 | Daily spillovers, affect, recovery, and within-person mechanisms are already studied with appropriate measurements. | No recovery or within-person claim. The released sample supports a between-person lagged association only. |
| S10 Ford et al. (2014), Work & Stress, PDF pp. 2, 16 | Lagged and reciprocal stressor–strain processes depend on timing and baseline adjustment. | No baseline exhaustion is available; do not call the result change, accumulation, persistence or a lagged causal effect. |

The exact literature-dependent premises are the seed's task-enabling/monitoring/privacy definitions and the prior establishment of heterogeneous paths/configurations. The novel inferential step is our proposed conditional ordering of monitoring versus privacy complementarity. It is explicitly marked as a new conjecture rather than attributed to a source.

The later Sevic et al. (2025) lead remains abstract/metadata only in T002. Its existence already rules out a first stressor-specific exhaustion-predictor claim, which we do not make. This proposal does not depend on asserting that paper lacks a particular interaction: it makes no detailed assertion about its unread methods. The bounded contribution is assessed against the read sources above. If the independent reviewer considers a specific Sevic overlap decisive, one targeted lawful fulltext resolution is the appropriate next action; broad searching is not justified merely for reassurance. No new search or download occurred in T004.

## Candidate comparison and rejection decisions

| Candidate | Scientific assessment | Decision |
|---|---|---|
| Overall DHS predicts exhaustion, or five domains have unequal slopes | Reproduction or established disaggregation; historical technical OLS also already used five composites. | Reject as a new study. |
| Relative insecurity/uncertainty/invasion versus obstruction at equal overall burden | Feasible association, but the proposed recovery explanation is not measured and unequal slopes alone do not supply a new theory. | Reject as standalone contribution; no opportunistic fallback if the selected contrast is null. |
| Overload × surveillance | The seed already explicitly invokes demands–control and workload/control interaction for surveillance (print p. 905). Job control is unmeasured. | Reject as insufficiently distinctive here. |
| Short versus extensive instrument preserves a selected contrast | Important measurement sensitivity, but generic parsimony comparison is already in the seed. A one-item PER/IOP split cannot replace their full scales. | Reject as standalone contribution and do not use the short form for the focal analysis. |
| Performance monitoring × nonavailability exceeds privacy intrusion × nonavailability | Specific relational proposition; all three established full scales are available; an additive rival and equal surveillance-complementarity rival predict different observable restrictions. | Select for independent critical review, with the measured-signature limitations above. |
| Recovery mechanism, latent profiles, new scale, causal COVID effect | Missing process measures, established configuration ideas, project exclusions, or no identification. | Reject. |

Selection was based on construct content and theoretical discrimination, not any new correlation, model fit, p-value or prediction score. No participant rows were read. The full quadratic model deliberately permits unequal main effects, unequal own-curvature, and all other pair interactions, so support cannot be obtained merely by omitting well-known heterogeneity.

## Falsifiable claim and meaningful negative results

Let A, M and P be standardized full-scale means for nonavailability, performance monitoring and privacy intrusion. Let S=(M+P)/2 and D=(M−P)/2. In the prespecified quadratic exhaustion surface, define b_AM as the A×M coefficient and theta=b_AM−b_AP as the A×D coefficient. An increase of D by one moves M up one SD and P down one SD at fixed S. Thus theta is the difference between two one-SD-by-one-SD interaction contrasts, not the effect of intervening on a person.

The proposed signature requires **b_AM>0 and theta>0**. The practical specificity margin is delta=0.20 outcome SD for the stated contrast. This is an investigator-declared research interpretation threshold, not a clinical cutoff or a value extracted from this dataset. Report the continuous interval so readers can apply smaller margins. Evidence of a positive but smaller contrast does not establish consequential differentiation at this declared margin. A sufficiently precise interval around zero is an informative limit on this proposed use of differentiated surveillance scores. A negative theta contradicts the predicted ordering. A positive theta with nonpositive b_AM fails the proposed conjunction. Wide intervals or poor overlap are inconclusive, not evidence that all stressors are interchangeable.

## Feasibility and scope

Sample 3 contains a documented 1,560 respondents, DHS in March 2019 and exhaustion in May 2020. The complete published scales are available. The source hierarchy yields plausible scenario precision for moderate interactions, but not guaranteed small-effect resolution; strong collinearity can make the proposal uninformative. See `10_Analysis/T004/precision_feasibility.md` for executed analytic calculations using only published loadings, declared covariance assumptions and hypothetical residual variation.

No extra sample is recruited; no external service receives rows. Existing data remain local. The article can fit eight main pages: question/theory 2.5, design 1.5, results 1.5, discussion/limitations 2, abstract/space 0.5; details and workflow provenance go in supplements/repository/required appendix. These allocations are planning estimates, not a finished manuscript.

Fresh review must decide whether this particular theoretical extension is meaningful enough, whether its observed-score rival is adequately bounded, whether the full quadratic adjustment/precision tradeoff is defensible, and whether the unavoidable measurement/confounding limits leave a worthwhile prospective test. Production does not certify these points. If rejected, retain this candidate and replan before tests; do not replace its primary contrast after looking at outcomes.


---

## Bibliographic key for the substantive source comparisons

- **S01** Henner Gimpel, Julia Lanzl, Christian Regal, Nils Urbach, Julia Becker, Patricia Tegtmeier (2025). Stress from Digital Work: Toward a Unified View of Digital Hindrance Stressors. Information Systems Research, 36(2), 896–915. https://doi.org/10.1287/isre.2022.0691 .
- **S02** Henner Gimpel, Julia Lanzl, Christian Regal, Nils Urbach, Julia Becker, Patricia Tegtmeier (2025). Online Appendix to Stress from Digital Work: Toward a Unified View of Digital Hindrance Stressors. Supplement to Information Systems Research, 52 PDF pages. https://doi.org/10.1287/isre.2022.0691 .
- **S03** Ramakrishna Ayyagari, Varun Grover, Russell Purvis (2011). Technostress: Technological Antecedents and Implications. MIS Quarterly, 35(4), 831–858. https://doi.org/10.2307/41409963 .
- **S06** Christian Maier, Sven Laumer, Monideepa Tarafdar, Jens Mattke, Lea Reis, Tim Weitzel (2021). Challenge and Hindrance IS Use Stressors and Appraisals: Explaining Contrarian Associations in Post-Acceptance IS Use Behavior. Journal of the Association for Information Systems, 22(6), 1590–1624. https://doi.org/10.17705/1jais.00709 .
- **S07** Monideepa Tarafdar, Cary L. Cooper, Jean-François Stich (2019). The technostress trifecta – techno eustress, techno distress and design: Theoretical directions and an agenda for research. Information Systems Journal, 29(1), 6–42. https://doi.org/10.1111/isj.12169 .
- **S09** Arla Day, Stephanie Paquet, Natasha Scott, Laura Hambley (2012). Perceived Information and Communication Technology (ICT) Demands on Employee Outcomes: The Moderating Effect of Organizational ICT Support. Journal of Occupational Health Psychology, 17(4), 473–491. https://doi.org/10.1037/a0029837 .
- **S10** Michael T. Ford, Russell A. Matthews, Jessica D. Wooldridge, Vipanchi Mishra, Urszula M. Kakar, Sarah R. Strahan (2014). How do occupational stressor-strain effects vary with time? A review and meta-analysis of the relevance of time lags in longitudinal studies. Work & Stress, 28(1), 9–30. https://doi.org/10.1080/02678373.2013.877096 .
- **S11** Alexander Benlian (2020). A Daily Field Investigation of Technology-Driven Spillovers from Work to Home. MIS Quarterly, 44(3), 1259–1300. https://doi.org/10.25300/MISQ/2020/14911 .
- **S12** Ilja Nastjuk, Simon Trang, Julius-Viktor Grummeck-Braamt, Marc T. P. Adam, Monideepa Tarafdar (2024). Integrating and synthesising technostress research: a meta-analysis on technostress creators, outcomes, and IS usage contexts. European Journal of Information Systems, 33(3), 361–382. https://doi.org/10.1080/0960085X.2022.2154712 .
- **S13** Britta Ingwersen, Julia Zeller-Lanzl, Kathrin Endres, Henner Gimpel (2026). Recovery from Technology-Driven Stress: A Daily Diary Study. Business & Information Systems Engineering, 68(5), 1049–1071; online 23 December 2025. https://doi.org/10.1007/s12599-025-00979-7 .

The later Sevic et al. (2025) work mentioned in the contribution note remains a discovery lead, not a read fulltext or a source for detailed scientific claims. The source comparison is bounded, not an exhaustive novelty guarantee. The source-specific page locators in the contribution note refer to the archived reading versions; issue-year successors are used in citations.

## Operator record to be retained outside this prepared payload

The posting task must retain: accepted scientific-review receipt; exact repository and filename; accepted local payload SHA-256; exact commit ID and provider timestamp; readable verification of the posted content against the accepted payload; the fact that no new-study test preceded this commit; and the separate source-promotion/readiness receipt. Later implementation/results commits must point back to the plan commit and document deviations. These are required future evidence, not completed actions claimed by this document.
