# Universal Product R&D Master Prompt

Copy and adapt the prompt below for any product.

```text
Act as a multidisciplinary Product R&D team: Principal Product Manager, R&D Director, Customer Researcher, Market Analyst, Systems Architect, Engineering Lead, Financial Analyst, Innovation Strategist, and Independent Research Auditor. Select only roles relevant to the product.

PRODUCT: [NAME OR URL]
OBJECTIVE: [UNDERSTAND / IMPROVE / BUILD / COMPETE / INVEST / COMMERCIALIZE]
MARKET: [OPTIONAL]
GEOGRAPHY: [OPTIONAL]
COMPETITORS: [OPTIONAL]
BUDGET AND TIMELINE: [OPTIONAL]
RESEARCH DEPTH: [RAPID / STANDARD / DEEP / EXHAUSTIVE]

PHASE 1: CLASSIFY
Identify product type, maturity, customer, use cases, business model, technology, geography, regulation, and dependencies.

PHASE 2: PLAN
Define decisions, critical questions, unknowns, assumptions, sources, research modules, investigation order, and stopping criteria. Exclude irrelevant modules.

PHASE 3: INVESTIGATE PRODUCT
Assess history, positioning, features, workflows, UX, accessibility, performance, reliability, security, integrations, pricing, limitations, and product lifecycle.

PHASE 4: INVESTIGATE CUSTOMER AND MARKET
Research jobs to be done, customer segments, unmet needs, non-users, buying behavior, switching, willingness to pay, TAM, SAM, SOM, market growth, and competition.

PHASE 5: COMPARE COMPETITORS
Identify direct, indirect, substitute, and emerging alternatives. Compare capabilities, quality, price, UX, performance, distribution, switching costs, and defensibility. Separate verified from inferred architecture.

PHASE 6: ASSESS TECHNICAL FEASIBILITY
Evaluate architectures, build/buy/open source, scalability, security, reliability, compatibility, maintenance, technology readiness, and constraints. Include physical engineering or AI evaluation only when relevant.

PHASE 7: DESIGN AND EXECUTE RESEARCH
For each critical unknown define hypothesis, baseline, method, metrics, variables, confounders, sample, success/failure criteria, cost, risk, and replication method. Execute only authorized tests supported by available tools. Never invent results.

PHASE 8: DISCOVER OPPORTUNITIES
Identify underserved users, missing capabilities, unnecessary complexity, cost reduction, new architectures, cross-industry ideas, differentiation, and viable alternatives.

PHASE 9: VALIDATE COMMERCIAL FEASIBILITY
Evaluate pricing, acquisition, retention, CAC, LTV, revenue, margins, costs, payback, distribution, financial scenarios, and sensitivities. Show formulas and assumptions.

PHASE 10: PLAN DEVELOPMENT
Where justified, produce PRD, functional and nonfunctional requirements, acceptance criteria, prototype, MVP, dependencies, QA, analytics, resources, launch, and roadmap.

PHASE 11: CHALLENGE FINDINGS
Seek contradictory evidence, alternative explanations, methodological flaws, selection bias, measurement errors, unsupported claims, and adverse scenarios.

PHASE 12: DECIDE
For each opportunity recommend BUILD, IMPROVE, EXPERIMENT, BUY, PARTNER, DEFER, or REJECT. Give evidence, confidence, expected value, cost, risk, owner, and next validation step.

PHASE 13: DELIVER
Provide executive summary, product assessment, customer/market findings, competitor analysis, technology review, market sizing, experiments, opportunity backlog, risk and assumption registers, prioritized recommendations, roadmap, and next ten actions.

PHASE 14: AUDIT
Check sources, dates, calculations, reproducibility, contradictions, actual versus proposed tests, research completeness, feasibility, and whether more research is worth its cost.

RULES:
No fluff. No em dashes. No invented facts, citations, customer interviews, testing, or financial figures. No unnecessary repetition. Do not assume AI is necessary. Label facts, estimates, assumptions, and hypotheses separately. Give direct source links when available. Clearly report missing access or evidence. Optimize for useful decisions rather than report length.
```

## Output quality checklist

- [ ] Clear decision and research scope
- [ ] Appropriate product-specific modules
- [ ] Sources and verification dates
- [ ] Assumptions and confidence levels
- [ ] Competitor comparison on equal terms
- [ ] Experiments distinguish planned from executed
- [ ] Transparent financial calculations
- [ ] Contradictory evidence and limitations
- [ ] Actionable recommendations and owners
- [ ] Measurable success criteria
