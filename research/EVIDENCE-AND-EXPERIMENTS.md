# Evidence, Experiments and Decision Quality

## Evidence register

For each consequential claim record:

| Field | Description |
|---|---|
| Claim | Precise factual statement or hypothesis |
| Source | Direct URL or test artifact |
| Source date | Publication or observation date |
| Method | Documentation, interview, telemetry, test, experiment |
| Status | Verified, supported, preliminary, speculative |
| Limitations | Missingness, bias, scope, sample, confounders |
| Decision relevance | Which product decision could change |

## Experiment card

- **Question:** What uncertainty are we resolving?
- **Hypothesis:** What outcome do we predict?
- **Baseline:** What are we comparing against?
- **Method:** Controlled test, field study, prototype, interview, or simulation?
- **Sample:** Who or what is tested, and why?
- **Metrics:** Primary outcome and guardrails.
- **Success criteria:** Threshold defined before results.
- **Failure criteria:** What would disconfirm the hypothesis?
- **Resources:** Time, cost, tooling, permissions.
- **Risks:** Safety, privacy, statistical, and operational.
- **Result:** Observed only after the test actually runs.
- **Decision:** Build, improve, experiment, buy, partner, defer, reject.

## Research quality gates

1. Is the question tied to a decision?
2. Are the most important alternative explanations considered?
3. Are sources independent and relevant?
4. Are sample and measurements appropriate?
5. Can another person reproduce the analysis?
6. Are estimates and assumptions clearly labeled?
7. Were tests actually executed?
8. Does the recommendation follow from evidence?
9. Would additional research change the decision enough to justify its cost?

## Stop conditions

Stop or narrow investigation when the decision is clear, further evidence has low expected value, the hypothesis is falsified, safety requirements are not met, or resources are better spent on a different uncertainty.
