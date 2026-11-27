# Opportunity Scoring Model

## Weighted score

Rate each dimension from 0 to 10. Calculate:

`Weighted score = Σ(dimension score × weight) / 100`

| Dimension | Weight | What a high score means |
|---|---:|---|
| Problem severity | 15% | Frequent, urgent, costly pain |
| Market demand evidence | 15% | Multiple credible signals of active demand |
| Willingness to pay | 15% | Existing spend, budget or paid commitment |
| Differentiation | 10% | Clear reason to choose and keep this solution |
| Market expansion | 10% | Attractive reachable segment with expansion paths |
| Technical feasibility | 10% | MVP can be delivered reliably by a small team |
| Customer acquisition | 10% | Buyer is identifiable and reachable at plausible cost |
| Recurring revenue | 10% | Repeated use and renewal are structurally plausible |
| MVP speed | 5% | Small testable product can be delivered quickly |
| **Total** | **100%** | |

## Score interpretation

- 8.5–10: exceptional candidate for further validation.
- 7.5–8.49: strong candidate.
- 6.5–7.49: worth investigating.
- 5.0–6.49: weak or uncertain.
- Below 5: reject or redesign.

These are prioritization bands, not probabilities of success.

## Evidence confidence

Assign separately:
- **High:** multiple independent, credible sources or direct behavioral evidence.
- **Medium:** some credible evidence, but material uncertainty remains.
- **Low:** mainly assumptions, indirect signals or incomplete research.

Do not infer high confidence from search snippets alone.

## Mandatory commercial gates

A high weighted score cannot justify BUILD if any of these remain materially unproven:

1. Identifiable buyer and budget owner.
2. Meaningful customer pain.
3. Credible willingness to pay.
4. Reachable initial customer segment.
5. Plausible contribution economics.

Record each gate as PASS, UNCERTAIN or FAIL, with evidence.

## $1M ARR calculations

`ARR = MRR × 12`

`Required customers = target ARR / annual revenue per customer`

For a $1,000,000 ARR target:

| Monthly price | Approx. customers required |
|---:|---:|
| $49 | 1,701 |
| $99 | 843 |
| $199 | 419 |
| $499 | 168 |
| $999 | 84 |
| $2,000 | 42 |
| $5,000 | 17 |

Round customer counts up in calculations. This is simple revenue math, not a forecast. Excludes churn, discounts, refunds, taxes, bad debt and costs.

## Unit economics

Where data permits, model:
- ARPA / annual contract value.
- Gross margin.
- CAC by channel.
- CAC payback.
- Logo and revenue churn.
- Expansion revenue and NRR.
- AI, hosting and support costs.
- Contribution margin.

Label each input as measured, sourced benchmark, estimate or hypothesis. Do not use generic benchmarks as if they were facts about this business.

## Scenario discipline

Build conservative, base and optimistic cases. For every scenario disclose:
- Price and customer count.
- Acquisition rate and channel.
- Conversion assumptions.
- Churn/retention assumptions.
- Gross margin and operating cost assumptions.
- Sensitivity to the two or three most important variables.

## Verdict

- BUILD: commercial gates sufficiently supported for a controlled MVP.
- VALIDATE: promising but material assumptions need experiments.
- PIVOT: pain exists, current solution or buyer is wrong.
- REJECT: insufficient pain, buyer, economics or distribution.

Explain what evidence would change the verdict.
