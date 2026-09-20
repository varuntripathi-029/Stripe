# ASSUMPTIONS

**Companion to:** `README.md`
**Author:** Varun Tripathi
**Research date:** 8 August 2026
**Purpose:** Document what is evidenced, what is inferred, and what is invented — so a reader can independently assess how much weight any claim bears.

---

## 1. Why this file exists

Stripe is a private company that discloses selectively. It publishes total payment volume and customer counts, but nothing about margin, loss rates, take rate, or per-product revenue. Every profitability and revenue figure in public circulation is a third-party estimate.

**The short version.** The case study's central thesis rests on four claims:

| Claim | Standing |
|---|---|
| Stripe is deliberately building open, non-exclusive protocol positions (ACP under Apache 2.0, Shared Payment Tokens, Tempo) | 🟢 **Well-evidenced** — all first-party and verifiable |
| Agentic checkout has not yet converted; the flagship implementation was retired in March 2026 | 🟢 **Well-evidenced** — multiple independent sources |
| Stripe's merchant-side trust surface is its weakest asset, and this matters *strategically* | 🟠 **Interpretation** — underlying complaints are real, but the strategic weight is the author's argument |
| Risk trajectory is predictive far enough in advance to make pre-emptive warnings actionable | 🔴 **Unverifiable from outside.** The pre-emptive half of the proposal (§14) depends on this and is stated as an open question |

---

## 2. Evidence grades by claim

### 🟢 High — official Stripe disclosure or first-party announcement

| Claim | Value | Where used |
|---|---|---|
| Total payment volume, 2025 | $1.9T, +34% YoY | §1, §2 |
| Share of global GDP | ~1.6% | §1 |
| Businesses powered | 5M+ | §1, §6 |
| Dow Jones Industrial Average coverage | 90% | §1 |
| Nasdaq 100 coverage | 80% | §1 |
| New Delaware corporations via Atlas | 25% | §1 |
| Revenue suite ARR | $1B run rate | §3 |
| Product updates shipped, 2025 | 350+ | §1 |
| Valuation | $159B (Feb 2026); $91.5B (Feb 2025) | §1 |
| Published US pricing | 2.9% + 30¢ | §2 |
| ACP licence | Apache 2.0, with OpenAI | §1, §4, §6 |
| Terms permit holds up to 120 days | Stripe terms of service | §7 |

### 🟡 Medium — credible secondary reporting, or company-reported without independent verification

| Claim | Value | Note |
|---|---|---|
| Radar fraud reduction | ~38% average | Vendor-reported |
| Instant Checkout retirement | 4 March 2026; fewer than ~15 Shopify merchants | Multiple independent secondary sources |
| Adyen 2025 figures | €1.4T volume; €2.4B net revenue | Public company; secondary reporting |
| Stablecoin volume | ~$400B, ~60% B2B | Stripe repeating a third-party estimate |

### 🟠 Low — third-party trackers and estimates

| Claim | Value | Why it is weak |
|---|---|---|
| Net revenue, 2025 | ~$5.84B | Estimate; methodology not published |
| Implied net take rate | ~0.31% | Author's derivation from estimate ÷ disclosure |
| Market share | ~21–29% | Methodology-dependent |
| Authorization-rate advantage | 2–5pp (Europe) | Vendor and consultancy material; load-bearing for §6 |
| Complaint volumes | ~540 trailing 12 mo (BBB) | Self-selected sample |

---

## 3. Key source conflicts

| Data point | Conflict | Resolution |
|---|---|---|
| **Revenue** | ~$5.84B net vs ~$19.4B gross | Definitional. Both reported; Adyen comparisons use net only |
| **Market share** | 21–29% | Range reported with methodology stated |
| **Agentic commerce** | Stripe letter (24 Feb) vs OpenAI retirement (4 Mar) | Timeline sequence. Both reported with dates |

---

## 4. Author-constructed content

None of the following is a reported fact about Stripe:

- All three personas (§5) — composites from documented segments and complaint patterns.
- The journey satisfaction curve (§8) — inferred from complaint patterns, not instrumentation.
- The root-cause hypothesis (§10) — if an internal standing object exists but is not exposed, the diagnosis is correct from the merchant's perspective but wrong about the cause.
- All RICE inputs (§13), particularly the 12-person-month effort estimate.
- The implied ~0.31% net take rate.
- The entire Stripe Standing proposal (§14–§19).
- All metric targets in §17 — illustrative; baselines are not disclosed.

---

## 5. Known weaknesses

1. **Complaint data cannot support a prevalence claim.** ~540 complaints against 5M+ businesses. The argument rests on severity, not frequency.
2. **Authorization-rate claim is load-bearing and weakly sourced.** The 2–5pp figure is widely repeated but originates from vendor material.
3. **Pre-emptive warnings depend on an unanswerable question.** Whether risk trajectory is predictive enough is knowable only inside Stripe. Variant C in the experiment (§18) ensures a shippable product even if the answer is no.
4. **No primary research.** No merchant interviews, no usability testing, no telemetry.

---

## 6. What would materially improve this analysis

1. Five structured interviews with merchants who experienced a Stripe hold.
2. Two or three conversations with Connect platform operators.
3. Independent authorization-rate benchmarking between Stripe and a direct acquirer.
4. Moderated usability test of the standing-detail screen with non-technical founders.
5. Adyen's actual filings for like-for-like comparison.

---

## 7. Methodology

**Research date:** 8 August 2026. Sources: Stripe's newsroom and 2025 annual letter, tier-one business press, payments trade press, analyst comparisons, technographic trackers, and public complaint aggregations. Every financial figure cross-checked against at least two independent sources where available. No primary-source interviews, product telemetry, or non-public documents were used.
