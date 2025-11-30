# A. Revenue

## Complete Guide to Construction Company Revenue Recognition

---

## Table of Contents

1. [Contract Revenue](#1-contract-revenue)
2. [Revenue Recognition Methods](#2-revenue-recognition-methods)
3. [Types of Contracts](#3-types-of-contracts)
4. [Change Orders & Claims](#4-change-orders--claims)
5. [Loss Contracts](#5-loss-contracts)
6. [Other Revenue Sources](#6-other-revenue-sources)

---

## 1. Contract Revenue

### Definition

Revenue earned from construction contracts, recognized as work is performed.

Also called:
- Construction Revenue
- Contract Income
- Earned Revenue

---

### Revenue Recognition - Core Concept

**Revenue ≠ Cash Received**
**Revenue ≠ Billings Issued**
**Revenue = Work Performed and Earned**

---

### The Fundamental Calculation

```
                   Costs Incurred to Date
% Complete = ──────────────────────────────
             Total Estimated Contract Costs

Revenue Earned = % Complete × Total Contract Price

Current Period Revenue = Revenue Earned - Previously Recognized Revenue
```

---

### Complete Multi-Year Example

**Contract Details:**
- Contract Price: $5,000,000
- Total Estimated Costs: $4,000,000
- Project Duration: 3 years

**Year 1:**
| Item | Amount |
|------|--------|
| Costs Incurred | $1,200,000 |
| % Complete | 30% ($1.2M / $4M) |
| Revenue Earned | $1,500,000 (30% × $5M) |
| Gross Profit | $300,000 |

**Year 2:**
| Item | Amount |
|------|--------|
| Costs Incurred (Year 2) | $1,600,000 |
| Cumulative Costs | $2,800,000 |
| Revised Total Est. Costs | $4,200,000 (cost growth) |
| % Complete | 66.67% ($2.8M / $4.2M) |
| Cumulative Revenue | $3,333,333 |
| Year 2 Revenue | $1,833,333 ($3.33M - $1.5M) |
| Year 2 GP | $233,333 |

**Year 3:**
| Item | Amount |
|------|--------|
| Costs Incurred (Year 3) | $1,350,000 |
| Total Actual Costs | $4,150,000 |
| % Complete | 100% |
| Total Revenue | $5,000,000 |
| Year 3 Revenue | $1,666,667 |
| Year 3 GP | $316,667 |

**Summary:**
| Year | Revenue | Costs | GP | GP% |
|------|---------|-------|-----|-----|
| 1 | $1,500,000 | $1,200,000 | $300,000 | 20.0% |
| 2 | $1,833,333 | $1,600,000 | $233,333 | 12.7% |
| 3 | $1,666,667 | $1,350,000 | $316,667 | 19.0% |
| **Total** | **$5,000,000** | **$4,150,000** | **$850,000** | **17.0%** |

---

### Journal Entry for Revenue Recognition

**Monthly/Period-End Entry:**
```
Dr. Cost of Revenue                  XXX,XXX
Dr. Costs in Excess of Billings      XX,XXX  (if underbilled)
    Cr. Contract Revenue                     XXX,XXX
    Cr. Billings in Excess of Costs          XX,XXX  (if overbilled)
```

**Or through WIP adjustment:**
The WIP schedule drives the revenue calculation. The journal entry records the difference between calculated revenue earned and billings.

---

## 2. Revenue Recognition Methods

### Input Method (Cost-to-Cost)

**Most Common for Construction**

**Formula:**
```
% Complete = Costs Incurred / Total Estimated Costs
```

**Advantages:**
- Objective (based on actual costs)
- Easy to apply
- Widely accepted

**Disadvantages:**
- Cost inefficiencies inflate revenue
- Requires accurate cost estimates
- Uninstalled materials can distort

---

### Output Method

**Based on Results Achieved**

**Measures Include:**
- Units delivered/produced
- Milestones achieved
- Contract stages completed
- Surveys of work performed

**Formula:**
```
% Complete = Output Measure Achieved / Total Output Measure
```

**Example - Unit Price Contract:**
- Contract: Install 50,000 LF of pipe @ $50/LF = $2,500,000
- LF Installed: 30,000
- Revenue = 30,000 × $50 = $1,500,000 (60% complete)

---

### Milestone Method

**When Milestones Represent Progress**

**Example:**
| Milestone | Value | Revenue |
|-----------|-------|---------|
| Foundation Complete | 25% | $1,250,000 |
| Structure Complete | 50% | $2,500,000 |
| MEP Complete | 75% | $3,750,000 |
| Final Completion | 100% | $5,000,000 |

---

### When to Use Each Method

| Method | Best When |
|--------|-----------|
| Cost-to-Cost | Costs reliably measure progress |
| Units | Unit-price contract |
| Milestones | Clear, measurable stages |
| Time Elapsed | Straight-line effort over time |

---

## 3. Types of Contracts

### Fixed-Price (Lump Sum) Contracts

**Definition:** Single price for all work

**Revenue Recognition:**
- Use percentage of completion
- All risk/reward to contractor
- Fixed transaction price

**Example:**
- Contract: Build warehouse for $2,000,000
- Costs: Contractor's risk
- Revenue: $2,000,000 (total)

---

### Cost-Plus Contracts

**Definition:** Reimbursement of costs plus fee

**Types:**
| Type | Description |
|------|-------------|
| Cost + Fixed Fee | Costs + set dollar fee |
| Cost + % | Costs + percentage markup |
| Cost + Incentive | Costs + performance incentive |

**Revenue Recognition:**
- Revenue = Costs Incurred + Fee Earned
- Less risk than fixed-price
- Transaction price = costs + fee

**Example:**
- Estimated Costs: $1,800,000
- Fixed Fee: $200,000
- Total Estimated: $2,000,000
- If costs = $1,900,000, Revenue = $2,100,000

---

### Time and Materials (T&M) Contracts

**Definition:** Hourly rates + material cost markup

**Revenue Recognition:**
- Revenue = (Hours × Rate) + (Materials × Markup)
- Recognized as work performed
- Practical expedient: Right to invoice amount

**Example:**
- 100 hours @ $75/hour = $7,500
- Materials: $5,000 + 15% = $5,750
- Revenue = $13,250

---

### Unit Price Contracts

**Definition:** Price per unit of work

**Revenue Recognition:**
- Revenue = Units Complete × Unit Price
- Simple output method

**Example:**
- Earthwork: 50,000 CY @ $15/CY
- CY Moved: 35,000
- Revenue = 35,000 × $15 = $525,000

---

### Guaranteed Maximum Price (GMP)

**Definition:** Cost-plus with ceiling

**Revenue Recognition:**
- Similar to cost-plus
- Fee recognized over project
- Savings may be shared

**Example:**
- GMP: $5,000,000
- Fee: $400,000
- If costs = $4,400,000, full fee earned
- If costs = $4,800,000, reduced fee ($200,000)

---

## 4. Change Orders & Claims

### Approved Change Orders

**Definition:** Formal modifications to contract scope/price

**Accounting:**
- Add to contract price immediately
- Add estimated costs to total estimate
- Recalculate percentage complete

**Journal Entry:**
```
(No specific entry - adjusts contract price in WIP schedule)
```

**Example:**
Original Contract: $1,000,000
Change Order: $150,000
New Contract Price: $1,150,000

---

### Unapproved Change Orders

**Definition:** Work performed, not yet formally approved

**Accounting - Variable Consideration:**
1. Estimate expected amount
2. Apply constraint (highly probable no reversal)
3. Include or exclude from transaction price

**When to Include:**
- Similar COs historically approved
- Legal basis is strong
- Approval expected
- Amount reliably estimated

**Journal Entry (if included):**
```
Dr. Contract Receivable - Change Orders     XX,XXX
    Cr. Contract Revenue                          XX,XXX
```

---

### Claims

**Definition:** Amounts sought for customer-caused issues

**Examples:**
- Delay damages
- Acceleration costs
- Differing site conditions
- Design errors
- Third-party interference

**Recognition Criteria (Stringent):**
1. Contract or legal basis
2. Amount reliably determinable
3. Evidence supports claim
4. Collection highly probable

**Conservative Approach:**
Many contractors don't record claims until settled because of the constraint.

---

## 5. Loss Contracts

### When Estimated Costs > Contract Price

**Rule:** Recognize ENTIRE expected loss immediately

**Example:**
| Item | Amount |
|------|--------|
| Contract Price | $1,000,000 |
| Original Estimated Costs | $900,000 |
| **Revised** Estimated Costs | $1,150,000 |
| Expected Loss | ($150,000) |

At the point loss is identified:

**Journal Entry:**
```
Dr. Loss on Construction Contracts     150,000
    Cr. Provision for Loss on Contracts        150,000
```

---

### Continuing Recognition (After Loss)

After recording loss:
- Continue % complete calculation
- Revenue matches costs (zero margin)
- Loss provision absorbs excess

**Year-End Presentation:**

**Income Statement:**
```
Loss on Construction Contracts           $(150,000)
```

**Balance Sheet:**
```
CURRENT LIABILITIES:
  Provision for Loss on Uncompleted Contracts    $XX,XXX
```

---

## 6. Other Revenue Sources

### Equipment Rental Income

**When contractor rents equipment to others:**

**Journal Entry:**
```
Dr. Cash/Accounts Receivable            5,000
    Cr. Equipment Rental Income               5,000
```

**Presentation:**
- Other Income (below operating income)
- Or separate line if material

---

### Service Revenue

**Non-construction services:**
- Consulting
- Management services
- Maintenance

---

### Joint Venture Income

**Share of JV earnings:**

**Journal Entry (Equity Method):**
```
Dr. Investment in Joint Venture        50,000
    Cr. Equity in JV Earnings                 50,000
```

---

### Sale of Materials/Scrap

**Selling excess materials:**

**Journal Entry:**
```
Dr. Cash                                2,500
    Cr. Other Income (or reduce Cost of Revenue)   2,500
```

---

## Revenue Presentation on Income Statement

### Single Line (Simple)

```
CONTRACT REVENUE                               $10,000,000
```

### Multiple Lines (Detailed)

```
CONTRACT REVENUE:
  Fixed-Price Contracts                   $6,500,000
  Cost-Plus Contracts                      2,500,000
  Time & Materials                         1,000,000
                                         ───────────
    TOTAL CONTRACT REVENUE                $10,000,000
```

---

## Required Disclosures (ASC 606)

### Disaggregation of Revenue

Break down revenue by:
- Type of contract
- Geography
- Customer type
- Timing of recognition

### Contract Balances

| Item | Beginning | Ending | Change |
|------|-----------|--------|--------|
| Contract Receivables | $XXX | $XXX | $XXX |
| Contract Assets (Underbillings) | $XXX | $XXX | $XXX |
| Contract Liabilities (Overbillings) | $XXX | $XXX | $XXX |

### Remaining Performance Obligations

Revenue expected from remaining backlog:
- Within 1 year
- After 1 year

---

## Summary: Revenue Key Points

| Topic | Key Point |
|-------|-----------|
| Recognition | Over time, as work performed |
| Calculation | % complete × contract price |
| Method | Usually cost-to-cost (input) |
| Change Orders | Approved = add immediately; Unapproved = variable consideration |
| Claims | Conservative - stringent criteria |
| Losses | Recognize entire loss immediately |

---

## Next Section: [B. Cost of Revenue](../B-Cost-of-Revenue/)
