# TAM, SAM, SOM and Market Sizing

## Definitions

- **TAM (Total Addressable Market):** Total annual demand for the product category in the defined market, assuming complete capture.
- **SAM (Serviceable Addressable Market):** The TAM portion reachable with the product's geography, capabilities, customer segment, and delivery model.
- **SOM (Serviceable Obtainable Market):** Realistically obtainable share of SAM within a stated time horizon, based on competition, distribution, resources, and capacity.

**Relationship:** SOM is within SAM, which is within TAM. Keep units, geography, customer definition, and year consistent.

## Worked example: SEO SaaS

Illustrative assumptions, not verified market data:

| Layer | Assumption | Annual value |
|---|---|---:|
| TAM | 100,000 eligible organizations × ₹100,000/year | ₹1,000 crore |
| SAM | 20,000 reachable organizations × ₹100,000/year | ₹200 crore |
| SOM | 1,000 customers × ₹100,000/year within five years | ₹10 crore |

A five-year SOM revenue target is not equivalent to the present market size. State the horizon and acquisition assumptions.

## Sizing methods

### Bottom-up
`Number of potential buyers × realistic annual spend per buyer`

Segment buyers by size, location, need, and willingness to pay. Avoid double counting.

### Top-down
Start from a credible market estimate and filter to the addressable geography, customer segments, product use cases, and channels.

### Value-based
Estimate economic value created per customer, the share that can reasonably be monetized, and number of eligible customers.

Triangulate methods. Explain differences instead of averaging incompatible estimates.

## Additional metrics

- **CAGR:** `(Ending / Beginning)^(1 / Years) - 1`
- **Market share:** `Your comparable market revenue / Total comparable market revenue × 100`
- **Penetration:** `Customers using product / Eligible customers × 100`
- **Price elasticity:** `% change in quantity demanded / % change in price`
- **CAC:** `Acquisition costs / New customers acquired`
- **LTV:** Discounted expected contribution from a customer over their lifetime, using explicit retention and margin assumptions.
- **CAC payback:** Acquisition cost divided by monthly contribution margin from the acquired customer, with consistent cohorts.

## Research checklist

1. Define product category and market boundary.
2. Fix currency, geography, period, and customer segments.
3. Identify primary and independent sources.
4. Estimate potential buyers and spend.
5. Filter to serviceable demand.
6. Model realistically obtainable customers and revenue.
7. Account for competition, capacity, and distribution.
8. Run conservative, base, and optimistic scenarios.
9. Test sensitivity to price, adoption, and retention.
10. Record sources, calculations, and uncertainty.

## Reusable market sizing prompt

```text
Estimate TAM, SAM, and SOM for [PRODUCT] in [GEOGRAPHY] for [YEAR/HORIZON].
Use top-down and bottom-up methods where evidence permits.
Show definitions, customer segments, assumptions, formulas, source URLs, dates, and confidence.
Do not invent market numbers. If data is missing, provide a transparent assumption-driven scenario.
Include CAGR, competition, realistic obtainable market share, sensitivity, and experiments to validate uncertain assumptions.
```
