# MODULE 06 — PRICING & REVENUE ARCHITECTURE
## Price Is Not a Number — It's a Signal, a Strategy, and a Statement

> **Purpose:** Pricing is the most powerful and most neglected commercial decision. Pricing too low destroys margin and signals low quality. Pricing too high without proof of value kills conversion. This module builds a pricing architecture grounded in economics, competition, and customer psychology.

---

## 6.1 THE PRICING FOUNDATION

### The Four Pricing Traps to Avoid

**TRAP 1: "Cost + markup" as the only method**
Adding 30% to cost ignores what customers actually value and what competitors charge.

**TRAP 2: Race to zero**
Competing on price against larger, better-funded competitors is a losing strategy for everyone except the winner — and the winner often destroys the market.

**TRAP 3: Pricing by gut feeling**
"I think $29/month feels right" is not a pricing strategy. It is a guess.

**TRAP 4: Fixing price and never testing it**
Prices should be tested, iterated, and optimized like any other product feature.

---

## 6.2 PRICING METHODOLOGY SELECTION

### Method 1: Cost-Based Pricing
```
Formula: Price = Total Cost per Unit × (1 + Target Margin %)
Use when: You need a floor price. Never use as the ceiling.

Example:
Production cost: $20
Marketing cost per unit: $5
Support cost per unit: $3
Total cost: $28
Target margin 50%: Price ≥ $56
```

**Limitation:** Ignores competitive price levels and customer willingness to pay. Use as a minimum floor only.

### Method 2: Competitor-Based Pricing
```
Steps:
1. Map all competitor prices (verified, not assumed)
2. Identify the market price anchor (most common price point)
3. Position relative to competition:
   - Below anchor: Penetration / cost leadership
   - At anchor: Competing head-to-head
   - Above anchor: Premium (requires clear differentiation justification)
```

**Limitation:** Assumes competitors have priced correctly. Many haven't.

### Method 3: Value-Based Pricing (Recommended Primary Method)

```
Formula: Price ≤ Customer's Cost of NOT Having This Product

Steps:
1. Identify the specific, quantifiable value delivered
2. Calculate the economic benefit to the customer
3. Price at a fraction of that value (typically 10–30%)

Example:
If this tool saves a marketing team 10 hours/week
Average marketer hourly cost = $50/hour
Annual value delivered = 10h × 50 × 52 weeks = $26,000
Pricing at 15% of value = $3,900/year = $325/month
```

**This is the gold standard for B2B and professional tools.**

### Method 4: Competitive Anchoring + Value Layer

```
Step 1: Research competitor pricing (establish market anchor)
Step 2: Calculate value delivered (establish value ceiling)
Step 3: Set price within the range:
         [Competitor anchor] < [Your Price] < [Value ceiling]
Step 4: Justify price gap from competitor with specific value proof
```

---

## 6.3 PRICING ARCHITECTURE — TIER DESIGN

### Why Multiple Tiers?

1. **Capture more of the willingness-to-pay spectrum**
   Different customers have vastly different budgets and needs.
2. **Reduce friction for entry-level buyers**
   A lower entry tier brings customers in; upsell opportunities increase total revenue.
3. **Anchor the mid-tier as the "best value"**
   Psychological anchoring: the premium tier makes the standard tier look reasonable.

### Tier Design Template

| Tier | Price | Target Buyer | Core Value | Key Features | Limitation | CTA |
|------|------:|-------------|-----------|-------------|-----------|-----|
| **Starter** | $X | Individual, budget-conscious | Get started | Core features only | Usage limits | "Start Free" |
| **Growth** | $Y | Professional, growing team | Full power | All features | Soft limits | "Most Popular" |
| **Pro** | $Z | Business, power users | Maximum value | Everything + priority | None | "Best Value" |
| **Enterprise** | Custom | Large orgs | Custom solution | Custom + SLA | Custom | "Contact Sales" |

**Psychological Pricing Rules:**
- Price ending in 7 or 9 performs better for consumer products ($97, $29)
- Round numbers signal premium for enterprise ($1,000/month vs $999/month)
- Annual pricing: offer 20% discount for annual vs monthly (improves LTV, reduces churn)
- Enterprise pricing is ALWAYS "Contact us" — never publish it

### Freemium Design (if applicable)

The freemium model only works if:
1. The free tier delivers genuine value (users actually accomplish something)
2. There is a clear, natural upgrade trigger (feature or usage limit the user hits)
3. The upgrade converts at ≥2% of free users
4. The conversion is worth the infrastructure cost of free users

```
FREEMIUM DESIGN PRINCIPLE:
Free tier: Enough value to build habit, not enough to run a business
Paid tier: Exactly what a user needs once they are "hooked"
Upgrade trigger: Specific, natural, not artificial
```

---

## 6.4 PRICING PSYCHOLOGY

### Anchoring Effect
Present a higher-priced tier first. Everything that follows looks more affordable.

### The Decoy Effect (Good-Better-Best)
Three tiers: a low-value entry option, a high-value middle option, and a premium option that makes the middle look like the obvious choice.

### Social Proof Pricing
"Most popular" badge on the tier you want to sell most. It works.

### Free Trial vs Freemium
| Factor | Free Trial | Freemium |
|--------|-----------|---------|
| Credit card at signup | Optional | Never |
| Duration | 7–30 days | Unlimited |
| Feature access | Full | Restricted |
| Best for | Product-led SaaS | High-volume consumer |
| Conversion rate | Higher | Lower |
| CAC | Lower | Higher (more support) |

---

## 6.5 REVENUE SIMULATION MODEL

### Core Assumptions Required

Before running any simulation, define:
- **Starting customer base:** [0 / existing users / existing sales]
- **Monthly new customer acquisition:** [conservative estimate]
- **Monthly churn rate:** [% of customers who cancel or stop buying]
- **Average Sale Price / MRR per customer:** [by tier]
- **Tier distribution:** [% of customers on each tier]
- **Variable cost per customer:** [COGS]
- **Fixed monthly costs:** [team, infrastructure, tools]

### Revenue Simulation Table

| Customers | MRR / Revenue | Variable Costs | Gross Profit | Fixed Costs | Operating Profit | Cumulative |
|----------:|-------------:|---------------|-------------|------------|-----------------|-----------|
| 10 | | | | | | |
| 25 | | | | | | |
| 50 | | | | | | |
| 100 | | | | | | |
| 250 | | | | | | |
| 500 | | | | | | |
| 1,000 | | | | | | |
| 5,000 | | | | | | |
| 10,000 | | | | | | |

### Break-Even Analysis

```
Monthly Fixed Costs: $[X]
Gross Margin per Customer: $[Y]
Break-Even Customers: X ÷ Y = [Z] customers

Time to Break-Even (at [N] new customers/month):
[Z] ÷ [N] = [months]
```

---

## 6.6 UNIT ECONOMICS DASHBOARD

### Critical Metrics for Any Revenue Model

**Customer Acquisition Cost (CAC)**
```
CAC = Total Sales & Marketing Spend ÷ New Customers Acquired
Target: CAC < LTV × 0.33
```

**Customer Lifetime Value (LTV)**
```
For subscription:   LTV = MRR ÷ Monthly Churn Rate
For transactional:  LTV = AOV × Purchase Frequency × Customer Lifespan
Target: LTV > CAC × 3
```

**Payback Period**
```
Payback Period = CAC ÷ Monthly Gross Profit per Customer
Target: < 12 months (ideally < 6 months)
```

**Gross Margin**
```
Gross Margin = (Revenue - COGS) ÷ Revenue × 100
Target: >70% for SaaS, >50% for software, >40% for marketplace
```

**Net Revenue Retention (NRR)** — for subscription only
```
NRR = (MRR at end of period from existing customers) ÷ (MRR at start of period) × 100
Target: >100% (expansion revenue exceeds churn)
```

---

## 6.7 PRICING EXPERIMENT FRAMEWORK

Never lock in permanent pricing without testing. Run these experiments:

### Experiment 1: Price Sensitivity Survey
Before launch, survey target customers:
> "If this product were priced at [$X], would you buy? What about [$Y]? [$Z]?"

Use the Van Westendorp Price Sensitivity Meter:
- Too cheap (suspicious of quality): [price point]
- Cheap (good deal): [price point]
- Expensive (must think about it): [price point]
- Too expensive (not buying): [price point]

Optimal price range: between "cheap" and "expensive" thresholds.

### Experiment 2: A/B Price Test (post-launch)
Split traffic 50/50 between two price points. Measure:
- Conversion rate
- Revenue per visitor
- Customer quality (churn, support load, LTV)

### Experiment 3: Tier Optimization
Track which tier most customers choose. If >80% choose the entry tier:
- Entry tier is too good or premium tier is overpriced
- Add more differentiation to premium, or reduce entry feature set

### Experiment 4: Annual vs Monthly
Test "Save 20% with annual" messaging. Measure:
- % of new customers choosing annual
- 12-month revenue per customer comparison
- Churn rate difference

---

## 6.8 REVENUE SCENARIO ANALYSIS

### Three-Scenario Framework

**CONSERVATIVE SCENARIO**
- Lower conversion rates than expected
- Higher churn than expected
- Slower growth
- Higher costs
- Realistic if: Product is early stage, market is unproven, team is small

**REALISTIC SCENARIO**
- Based on comparable company benchmarks
- Reasonable assumptions with supporting data
- Mid-point between conservative and aggressive

**AGGRESSIVE SCENARIO**
- Assumes strong product-market fit
- Viral or partner-driven growth
- Lower churn due to strong retention
- Requires: Significant marketing investment, strong execution, some luck

| Scenario | Month 3 Revenue | Month 6 Revenue | Month 12 Revenue | Break-Even Month |
|---------|----------------|----------------|-----------------|-----------------|
| Conservative | | | | |
| Realistic | | | | |
| Aggressive | | | | |

**All scenarios must have explicit assumptions listed beneath the table.**

---

## OUTPUT DELIVERABLE

After completing Module 06, produce:

1. **Pricing Architecture** — Tiered pricing table with justification
2. **Pricing Rationale** — Which methodology was used and why
3. **Value-Based Pricing Calculation** — Quantified customer value and price as % of value
4. **Revenue Simulation** — Full table from 10 to 10,000 customers
5. **Unit Economics Dashboard** — CAC, LTV, payback period, gross margin targets
6. **Pricing Experiment Roadmap** — What to test in the first 90 days
7. **Break-Even Analysis** — Specific number of customers and estimated timeline

Feed outputs into Module 07 (Go-To-Market) and Module 10 (Financial Intelligence).
