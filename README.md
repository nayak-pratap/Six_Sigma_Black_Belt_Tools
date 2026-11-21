# Six Sigma Black Belt Toolkit

Interactive calculators and tools for Six Sigma Black Belt projects. Each page opens with worked example values from one running case (chipped carbide inserts across three lines), recalculates as you type, and has a **Reset to example values** button. Everything runs in the browser: no build step, no server, no data leaves the page.

## Calculators

| Page | What it does |
|---|---|
| [One-Way ANOVA](calculators/anova-one-way.html) | Compare the means of three or more groups with an F-test, effect size, pairwise comparisons and a means chart. |
| [t-Tests: One-Sample, Paired, Two-Sample](calculators/t-tests.html) | Run a one-sample, paired or two-sample (Welch) t-test directly from raw data, with confidence interval and a plain-language verdict. |
| [Chi-Square and Proportion Tests](calculators/chi-square-proportions.html) | Test independence in a contingency table, or compare two defect proportions, with expected counts, effect size and a verdict. |
| [Multiple Linear Regression](calculators/multiple-regression.html) | Fit Y on up to five X variables from pasted columns: coefficients, p-values, R², adjusted R², VIF and residual check. |
| [Binary Logistic Regression](calculators/logistic-regression.html) | Model a pass/fail outcome from one to three predictors: odds ratios, p-values and predicted probability for chosen settings. |
| [Power and Sample Size](calculators/power-sample-size.html) | How many samples to detect a difference in means or proportions, and what power a given sample really gives. |
| [Normality Test and Descriptive Statistics](calculators/normality-test.html) | Anderson-Darling normality test, normal probability plot, histogram, skewness, kurtosis and a plain recommendation for what to do next. |
| [Mann-Whitney and Kruskal-Wallis](calculators/nonparametric-tests.html) | Rank-based tests for two groups or for three or more groups when data are not normal, with medians and a verdict. |
| [Variance Tests: F, Bartlett and Levene](calculators/variance-tests.html) | Test whether group spreads differ, with the right test for normal and non-normal data, and the ratio of standard deviations. |
| [Capability Study: Cp, Cpk, Pp, Ppk](calculators/capability-study.html) | Separate short-term and long-term capability from subgrouped data, with Cp, Cpk, Pp, Ppk, Cpm, expected PPM and a histogram against the specification. |
| [Gage R&R (ANOVA Method)](calculators/gage-rr-anova.html) | Analyse a crossed gage study from raw readings: ANOVA with interaction, variance components, %contribution, %study variation and distinct categories. |
| [Attribute Agreement (Cohen’s Kappa)](calculators/attribute-agreement.html) | Check whether appraisers agree with each other and with the known standard when judging pass/fail or grades. |
| [Two-Level Factorial DOE Analysis](calculators/doe-factorial-analysis.html) | Analyse a 2², 2³ or 2⁴ full factorial: effects, interactions, ANOVA with replicates, Pareto of effects, model equation and best settings. |
| [Variable Control Charts with Run Rules](calculators/control-charts-variable.html) | X-bar and R chart (or individuals and moving range) from your data, with limits, capability σ and the Western Electric signals flagged. |
| [Attribute Control Charts: p, np, c, u](calculators/control-charts-attribute.html) | Control charts for defectives and defects with varying sample sizes: limits for every point and out-of-control flags. |
| [EWMA and CUSUM Charts](calculators/ewma-cusum.html) | Detect small, sustained shifts that Shewhart charts miss, with an EWMA chart and a tabular CUSUM. |
| [Acceptance Sampling and OC Curve](calculators/acceptance-sampling.html) | Evaluate a single sampling plan (n, c): operating characteristic curve, producer’s and consumer’s risk, and average outgoing quality. |
| [Weibull Reliability Analysis](calculators/weibull-reliability.html) | Fit a Weibull distribution to failure times: shape and scale, B10 life, mean life and reliability at a mission time. |
| [Project Financials: NPV, IRR, Payback, ROI](calculators/financial-analysis.html) | Turn project savings and costs into NPV, IRR, payback and return on investment, with hard and soft savings kept apart. |
| [Tolerance Stack-Up and Monte Carlo](calculators/tolerance-stackup.html) | Combine component tolerances into an assembly gap with worst-case, root-sum-square and simulated results, and the share of gap variation from each part. |
| [Takt, Little’s Law, Kanban and Queue Calculator](calculators/flow-queue-lean.html) | Lean flow arithmetic in one page: takt time, process cycle efficiency, Little’s Law, kanban card count and a single-server queue. |
| [OEE and the Six Big Losses](calculators/oee-losses.html) | Overall equipment effectiveness from time and count data, split into availability, performance and quality losses. |
| [Rolled Throughput Yield](calculators/rolled-throughput-yield.html) | Combine first-pass yields of each process step into RTY, normalised yield, DPMO and sigma level, and find the weakest step. |
| [Taguchi Loss Function and S/N Ratio](calculators/taguchi-loss-sn.html) | Put a cost on being off target and variable: quadratic loss per part, and signal-to-noise ratio to compare settings. |
| [Multi-Vari Analysis](calculators/multi-vari.html) | Find the family of variation that matters most: within a piece, between pieces, or over time, from labelled readings. |

## Tools

| Page | What it does |
|---|---|
| [Black Belt Project Charter](tools/project-charter-bb.html) | Draft a full charter with business case, savings, scope, risks and tollgate dates, and get a checklist of what is still weak. |
| [Which Methodology? Project Type Selector](tools/methodology-selector.html) | Answer five questions to choose between a quick fix, project management, Lean, DMAIC or DFSS, with the reason and first move. |
| [Hard and Soft Savings Worksheet](tools/savings-worksheet.html) | Classify project benefits as hard savings, cost avoidance or soft benefits, apply confidence, and see the number finance will accept. |
| [Stakeholder Engagement and Communication Plan](tools/stakeholder-engagement.html) | Map influence and support, spot gaps between where people are and where you need them, and get an engagement action per stakeholder. |
| [Tollgate Review Checklist](tools/tollgate-review.html) | Score readiness at each DMAIC tollgate, see the weakest phase, and decide pass, conditional pass or rework. |
| [Team Health and Coaching Audit](tools/team-health-audit.html) | Diagnose team effectiveness across purpose, roles, communication and decision-making, and get a coaching focus. |
| [QFD House of Quality (Core Matrix)](tools/qfd-house-of-quality.html) | Weight customer needs against technical requirements to rank which design or process characteristics matter most. |
| [Cause and Effect (C&E) Matrix](tools/cause-effect-matrix.html) | Rank process inputs by how strongly they affect the outputs customers care about, to focus the vital few for FMEA and data collection. |
| [Operational Definitions and Data Collection Plan](tools/data-collection-plan-bb.html) | Write each measure so two people would collect it identically, and check the plan for the gaps that ruin data. |
| [FMEA with RPN and Priority](tools/fmea-rpn.html) | Score failure modes by severity, occurrence and detection, rank by RPN, and flag high-severity items regardless of RPN. |
| [Root Cause Hypothesis Tracker](tools/root-cause-tracker.html) | Track each suspected cause through test, evidence and verdict so nothing is assumed, and see how many are verified. |
| [Hypothesis Test Chooser (Black Belt)](tools/hypothesis-test-chooser-bb.html) | Choose among t-tests, ANOVA, non-parametric, regression, chi-square and logistic tests from the data type and your question, with the fallback and assumptions. |
| [Pugh Concept Selection Matrix](tools/pugh-matrix.html) | Compare solution or design concepts against a baseline on weighted criteria and see which concept wins and where it is weak. |
| [DFSS Roadmap Navigator](tools/dfss-roadmap-navigator.html) | Compare DMADV, IDOV, DMEDI and DCOV phase by phase and see which suits a product, process or service design. |
| [DOE Run Table Planner](tools/doe-planner.html) | Build a randomised run table for a 2-level full or half-fraction factorial, with replicates and centre points, and see what is aliased. |
| [Change Readiness Audit (ADKAR)](tools/change-readiness-audit.html) | Score awareness, desire, knowledge, ability and reinforcement for a change, and find where people are stuck. |
| [Control Plan Builder](tools/control-plan-builder.html) | List each key process characteristic with its spec, measurement, sampling, control method and reaction plan, and flag the missing pieces. |
| [Benefits Tracker](tools/benefits-tracker.html) | Compare planned and actual monthly savings after closure, with cumulative variance and a sustain check. |
| [Lean Six Sigma Maturity Audit](tools/lean-maturity-audit.html) | Score an operation on flow, quality, standard work, visual management and problem solving to find where to invest next. |
| [Control Chart Chooser (Black Belt)](tools/control-chart-chooser-bb.html) | Select a Shewhart, EWMA, CUSUM or attribute chart from the data type and the shift you need to catch. |

## Run it

Open `index.html` in a browser. To publish with GitHub Pages: repository **Settings, Pages, Build and deployment, Deploy from a branch, main, / (root)**. The site then appears at `https://<your-user>.github.io/SixSigma_BlackBelt_Tools/`.

## Structure

```
index.html            landing page
calculators/          one self-contained page per calculator
tools/                one self-contained page per tool
assets/style.css      shared styles (light and dark themes)
assets/lib.js         shared statistics and page helpers
```

## Method notes

- Normal CDF, inverse normal, t and incomplete-beta functions are implemented in `assets/lib.js` and were checked against known values.
- Sigma level uses the conventional 1.5σ shift (switchable in the DPMO calculator).
- Control chart constants cover subgroup sizes 2 to 10. F, chi-square and incomplete-gamma functions, least-squares and logistic regression, Anderson-Darling and rank tests are implemented in `assets/lib.js` and checked against published values. Tukey tests are replaced by Bonferroni-adjusted comparisons, and power uses a normal approximation of the non-central t.
- Worked examples are invented for illustration. Check your own data, standards and customer requirements before acting on a result.

Not affiliated with or endorsed by ASQ, IASSC or any certifying body.
