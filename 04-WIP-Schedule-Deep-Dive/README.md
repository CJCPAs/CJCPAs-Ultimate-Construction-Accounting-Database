# Section 04: The WIP Schedule Deep Dive

## The Heart of Construction Accounting

---

## The Work-in-Progress Schedule: What Every Construction Accountant Must Know

*"In construction accounting, the WIP schedule is not just a schedule—it's the financial heartbeat of the company."*

---

## Table of Contents

1. [What is the WIP Schedule?](#1-what-is-the-wip-schedule)
2. [Anatomy of a WIP Schedule](#2-anatomy-of-a-wip-schedule)
3. [The Calculations Explained](#3-the-calculations-explained)
4. [Reading the WIP Schedule](#4-reading-the-wip-schedule)
5. [WIP Schedule Formats](#5-wip-schedule-formats)
6. [Common Problems and Red Flags](#6-common-problems-and-red-flags)
7. [Creating a WIP Schedule](#7-creating-a-wip-schedule)
8. [Management Uses of the WIP](#8-management-uses-of-the-wip)
9. [Complete Examples](#9-complete-examples)

---

## 1. What is the WIP Schedule?

### Definition

The Work-in-Progress (WIP) Schedule is a comprehensive report showing the status of all active construction contracts, including:
- Contract values
- Costs incurred
- Estimated costs to complete
- Revenue earned
- Billings issued
- Over/under billing positions

---

### Why It's Called the "Heart" of Construction Accounting

| Function | Why It's Critical |
|----------|------------------|
| Revenue Recognition | Drives the percentage-of-completion calculation |
| Balance Sheet | Determines asset (underbilling) or liability (overbilling) |
| Profitability | Shows gross profit by job |
| Forecasting | Projects future revenue and costs |
| Cash Flow | Identifies over/under billing positions |
| Bonding | Required by sureties for bonding decisions |

---

### Who Uses the WIP Schedule?

| User | Purpose |
|------|---------|
| **Management** | Monitor job profitability, make decisions |
| **Project Managers** | Track budgets, identify problems |
| **Accountants** | Calculate revenue, prepare financials |
| **Auditors** | Test revenue recognition accuracy |
| **Bankers** | Assess creditworthiness |
| **Sureties** | Determine bonding capacity |
| **Owners** | Understand company performance |

---

## 2. Anatomy of a WIP Schedule

### Standard WIP Schedule Columns

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    WORK IN PROGRESS SCHEDULE                                             │
│                                      As of December 31, 2024                                             │
├────────┬───────────┬──────────┬───────────┬───────────┬──────────┬──────────┬───────────┬──────────────┤
│        │ Contract  │ Costs    │ Est. Cost │ Total     │ Percent  │ Revenue  │ Billings  │ Over/(Under) │
│ Job    │ Amount    │ to Date  │ to Compl. │ Est. Cost │ Complete │ Earned   │ to Date   │ Billing      │
├────────┼───────────┼──────────┼───────────┼───────────┼──────────┼──────────┼───────────┼──────────────┤
│ 101    │ 1,000,000 │ 400,000  │ 350,000   │ 750,000   │ 53.33%   │ 533,333  │ 450,000   │ (83,333)     │
│ 102    │ 2,500,000 │ 1,200,000│ 900,000   │ 2,100,000 │ 57.14%   │ 1,428,571│ 1,600,000 │ 171,429      │
│ 103    │ 750,000   │ 500,000  │ 100,000   │ 600,000   │ 83.33%   │ 625,000  │ 580,000   │ (45,000)     │
├────────┼───────────┼──────────┼───────────┼───────────┼──────────┼──────────┼───────────┼──────────────┤
│ Total  │ 4,250,000 │ 2,100,000│ 1,350,000 │ 3,450,000 │          │ 2,586,904│ 2,630,000 │ 43,096       │
└────────┴───────────┴──────────┴───────────┴───────────┴──────────┴──────────┴───────────┴──────────────┘

Net Position:
  Costs in Excess of Billings (Underbillings)........... $ 128,333  (Jobs 101 + 103)
  Billings in Excess of Costs (Overbillings)............ $(171,429) (Job 102)
                                                         ─────────
  Net Over/(Under) Billing.............................. $ (43,096)
```

---

### Column Definitions

| Column | Definition | Source |
|--------|------------|--------|
| **Job Number** | Unique identifier | Job setup |
| **Contract Amount** | Total contract price incl. approved COs | Contract docs |
| **Costs to Date** | Cumulative costs incurred | Job cost system |
| **Est. Cost to Complete** | Remaining costs to finish | PM estimate |
| **Total Estimated Cost** | Costs to Date + Est. to Complete | Calculation |
| **Percent Complete** | Costs to Date ÷ Total Est. Cost | Calculation |
| **Revenue Earned** | % Complete × Contract Amount | Calculation |
| **Billings to Date** | Cumulative amounts billed | Billing system |
| **Over/(Under) Billing** | Billings - Revenue Earned | Calculation |

---

## 3. The Calculations Explained

### The Core Formulas

**Formula 1: Total Estimated Cost**
```
Total Estimated Cost = Costs to Date + Estimated Cost to Complete
```

**Formula 2: Percent Complete**
```
                       Costs to Date
Percent Complete = ─────────────────────
                   Total Estimated Cost
```

**Formula 3: Revenue Earned**
```
Revenue Earned = Percent Complete × Contract Amount
```

**Formula 4: Over/(Under) Billing**
```
Over/(Under) Billing = Billings to Date - Revenue Earned

If Positive: Overbilled (Liability)
If Negative: Underbilled (Asset)
```

**Formula 5: Gross Profit**
```
Gross Profit Earned = Revenue Earned - Costs to Date
```

**Formula 6: Projected Total Gross Profit**
```
Projected GP = Contract Amount - Total Estimated Cost
```

**Formula 7: GP Percentage**
```
                   Projected GP
GP Percentage = ──────────────── × 100
                Contract Amount
```

---

### Complete Calculation Example

**Contract Details:**
- Contract Amount: $1,000,000
- Costs to Date: $400,000
- Estimated Cost to Complete: $350,000

**Calculations:**

| Step | Formula | Calculation | Result |
|------|---------|-------------|--------|
| 1 | Total Est. Cost | $400,000 + $350,000 | $750,000 |
| 2 | % Complete | $400,000 ÷ $750,000 | 53.33% |
| 3 | Revenue Earned | 53.33% × $1,000,000 | $533,333 |
| 4 | Gross Profit Earned | $533,333 - $400,000 | $133,333 |
| 5 | Projected Total GP | $1,000,000 - $750,000 | $250,000 |
| 6 | GP % | $250,000 ÷ $1,000,000 | 25.0% |

If Billings = $450,000:
| Step | Formula | Calculation | Result |
|------|---------|-------------|--------|
| 7 | Over/Under | $450,000 - $533,333 | ($83,333) |

**Result:** Underbilled by $83,333 (Asset)

---

## 4. Reading the WIP Schedule

### What the Numbers Tell You

#### Job 101 Analysis:
```
Contract: $1,000,000  |  Costs: $400,000  |  ETC: $350,000  |  Billed: $450,000
```

| Metric | Value | Interpretation |
|--------|-------|----------------|
| % Complete | 53.33% | Job is about half done |
| Projected GP | $250,000 | Expecting 25% margin |
| Over/Under | ($83,333) | Underbilled - owed money |
| GP Earned | $133,333 | Profit recognized so far |

---

### Warning Signs to Look For

| Warning Sign | What It Might Mean |
|--------------|-------------------|
| ETC = $0 on incomplete job | Estimates not updated |
| Very high underbillings | Billing behind schedule, cash flow issues |
| Very high overbillings | Customer financing you, potential reversal |
| GP% declining | Cost overruns, estimate changes |
| Large ETC changes | Estimate instability |
| Negative GP% | Loss contract - immediate recognition |

---

### Key Performance Indicators from WIP

**Fade Analysis:**
Compare original budget GP% to current projected GP%.

| Job | Original GP% | Current GP% | Fade |
|-----|--------------|-------------|------|
| 101 | 30% | 25% | (5%) |
| 102 | 22% | 19% | (3%) |
| 103 | 28% | 25% | (3%) |

Negative fade = declining profitability

---

## 5. WIP Schedule Formats

### Format 1: Standard 8-Column

```
Job | Contract | Costs TD | ETC | Total Est | % Comp | Rev Earned | Billed | O/(U)
```

Most common format. Good for basic analysis.

---

### Format 2: Extended with Gross Profit

```
Job | Contract | Costs TD | ETC | Total Est | % Comp | Rev Earned | GP Earned | GP% | Billed | O/(U)
```

Adds gross profit columns for profitability analysis.

---

### Format 3: With Original vs. Revised

```
Job | Orig Contract | COs | Rev Contract | Orig Est Cost | Rev Est Cost | % Comp | Rev Earned | Billed | O/(U)
```

Shows contract evolution through change orders.

---

### Format 4: Detailed Project View

```
═══════════════════════════════════════════════════════════════════════════════
JOB 101 - MAIN STREET OFFICE BUILDING
═══════════════════════════════════════════════════════════════════════════════
Contract Information:
  Original Contract Amount                          $  950,000
  Approved Change Orders                               50,000
                                                    ──────────
  Current Contract Amount                           $1,000,000

Cost Information:
  Costs Incurred to Date:
    Labor                           $  85,000
    Materials                         120,000
    Subcontractors                    165,000
    Equipment                          20,000
    Other                              10,000
                                    ──────────
    Total Costs to Date             $ 400,000

  Estimated Cost to Complete:
    Labor                           $  65,000
    Materials                          80,000
    Subcontractors                    175,000
    Equipment                          20,000
    Other                              10,000
                                    ──────────
    Total Est. Cost to Complete     $ 350,000
                                    ──────────
    Total Estimated Cost            $ 750,000

Progress:
  Percent Complete                      53.33%
  Revenue Earned                    $ 533,333
  Gross Profit Earned               $ 133,333
  Gross Profit Percentage               25.0%

Billing Status:
  Billings to Date                  $ 450,000
  Over/(Under) Billing              $ (83,333)  UNDERBILLED
═══════════════════════════════════════════════════════════════════════════════
```

---

### Format 5: Summary with Balance Sheet Presentation

```
WORK IN PROGRESS SCHEDULE SUMMARY
December 31, 2024
═══════════════════════════════════════════════════════════════════════════════

                                           Costs      Estimated    Billings
Job          Contract      to Date        Earnings    to Date     Over/(Under)
─────────────────────────────────────────────────────────────────────────────
Underbilled Jobs:
  101       $1,000,000    $  400,000    $  533,333   $  450,000   $ (83,333)
  103          750,000       500,000       625,000      580,000     (45,000)
             ──────────    ──────────    ──────────   ──────────   ──────────
             $1,750,000    $  900,000   $1,158,333   $1,030,000   $(128,333)

Overbilled Jobs:
  102       $2,500,000    $1,200,000   $1,428,571   $1,600,000   $ 171,429
             ──────────    ──────────    ──────────   ──────────   ──────────
             $2,500,000    $1,200,000   $1,428,571   $1,600,000   $ 171,429

Total:      $4,250,000    $2,100,000   $2,586,904   $2,630,000   $  43,096
═══════════════════════════════════════════════════════════════════════════════

BALANCE SHEET PRESENTATION:
  Costs and Estimated Earnings in Excess of Billings        $128,333 (Asset)
  Billings in Excess of Costs and Estimated Earnings       ($171,429)(Liability)
```

---

## 6. Common Problems and Red Flags

### Problem 1: Stale Estimates

**Symptom:** ETC hasn't changed in months

**Risk:** Revenue and GP may be misstated

**Solution:** Require monthly ETC updates from PMs

---

### Problem 2: "Plug" Estimates

**Symptom:** ETC exactly equals budgeted remaining costs

**Risk:** Not reflecting actual project status

**Example:**
```
Original Budget:    $800,000
Costs to Date:      $400,000
ETC per PM:         $400,000  ← Suspicious!
```

**Solution:** Require detailed ETC breakdown and justification

---

### Problem 3: Large Underbillings

**Symptom:** Underbillings > 20% of revenue

**Risk:** Cash flow problems, disputes, aggressive revenue

**Questions to Ask:**
- Why hasn't this been billed?
- Is the customer disputing?
- Are the estimates accurate?

---

### Problem 4: Excessive Overbillings

**Symptom:** Overbillings > 30% of revenue

**Risk:** Future cash shortfall, funding other jobs

**Questions to Ask:**
- Is billing schedule appropriate?
- Are costs accurate?
- Can company deliver remaining work?

---

### Problem 5: Declining Gross Profit Percentages

**Symptom:** GP% declining over project life

**Risk:** Hidden cost overruns

**Analysis:**
```
Month    GP%     Change
────────────────────────
Jan      30%       -
Feb      28%      -2%
Mar      25%      -3%
Apr      22%      -3%
May      18%      -4%  ← Accelerating fade!
```

---

### Problem 6: "Held" Revenue

**Symptom:** Revenue earned but not billed for extended period

**Risk:** May indicate disputes, may not be realizable

---

### Problem 7: 95%+ Complete with Significant ETC

**Symptom:** Job shows 95% complete but 20% of costs remaining

**Risk:** Punch list items, warranty work, disputes

---

## 7. Creating a WIP Schedule

### Step-by-Step Process

#### Step 1: Gather Contract Information
- Original contract amount
- All approved change orders
- Current contract amount

#### Step 2: Compile Costs to Date
- Run job cost report
- Include all cost categories
- Verify completeness (cutoff)

#### Step 3: Obtain Estimates to Complete
- Get from project managers
- By cost category preferred
- Document assumptions

#### Step 4: Calculate Totals
- Total estimated cost
- Percentage complete
- Revenue earned

#### Step 5: Compile Billings
- Run billing report
- Include all progress billings
- Note retention held

#### Step 6: Calculate Over/Under
- Revenue earned - Billings
- Separate into asset/liability

#### Step 7: Review and Analyze
- Compare to prior periods
- Identify anomalies
- Document conclusions

---

### Monthly WIP Process Timeline

```
Day 1-5:   Close job cost system
Day 5-7:   PMs review and update ETCs
Day 7-10:  Accounting compiles WIP
Day 10-12: Review meeting with management
Day 12-15: Finalize and prepare reports
```

---

## 8. Management Uses of the WIP

### Job Profitability Analysis

| Job | Revenue | GP Earned | GP% | Status |
|-----|---------|-----------|-----|--------|
| 101 | $533,333 | $133,333 | 25.0% | On track |
| 102 | $1,428,571 | $228,571 | 16.0% | Below bid |
| 103 | $625,000 | $125,000 | 20.0% | On track |

---

### Cash Flow Forecasting

```
Current Position:
  Underbillings            $128,333  (Will be billed)
  Overbillings            ($171,429) (Already billed)

Next Month Projection:
  Expected Revenue         $500,000
  Expected Billings        $550,000
  Expected Collections     $480,000
```

---

### Backlog Analysis

```
Total Contract Value:           $4,250,000
Less: Revenue Earned           (2,586,904)
                               ──────────
Remaining Backlog:             $1,663,096
```

---

### Performance Trending

```
Quarter  Revenue   GP      GP%
────────────────────────────────
Q1       $2.5M    $400K   16.0%
Q2       $3.2M    $560K   17.5%
Q3       $2.8M    $476K   17.0%
Q4       $2.6M    $390K   15.0%  ← Declining!
```

---

## 9. Complete Examples

### Example A: Simple Three-Job WIP

**ABC Construction Company - WIP Schedule as of December 31, 2024**

```
┌────────────────────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                             WORK IN PROGRESS SCHEDULE                                           │
├──────┬────────────┬───────────┬───────────┬───────────┬────────┬───────────┬───────────┬──────────┬───────────┤
│      │  Contract  │  Costs    │   Est.    │   Total   │   %    │  Revenue  │   Gross   │ Billings │  Over/    │
│ Job  │  Amount    │ to Date   │ to Compl. │ Est. Cost │ Compl. │  Earned   │  Profit   │ to Date  │ (Under)   │
├──────┼────────────┼───────────┼───────────┼───────────┼────────┼───────────┼───────────┼──────────┼───────────┤
│ 2401 │$1,500,000  │$  720,000 │$  480,000 │$1,200,000 │ 60.00% │$  900,000 │$  180,000 │$  850,000│$ (50,000) │
│ 2402 │ 2,000,000  │   950,000 │   700,000 │ 1,650,000 │ 57.58% │ 1,151,515 │   201,515 │ 1,200,000│   48,485  │
│ 2403 │   800,000  │   600,000 │    80,000 │   680,000 │ 88.24% │   705,882 │   105,882 │   680,000│  (25,882) │
├──────┼────────────┼───────────┼───────────┼───────────┼────────┼───────────┼───────────┼──────────┼───────────┤
│TOTAL │$4,300,000  │$2,270,000 │$1,260,000 │$3,530,000 │        │$2,757,397 │$  487,397 │$2,730,000│$ (27,397) │
└──────┴────────────┴───────────┴───────────┴───────────┴────────┴───────────┴───────────┴──────────┴───────────┘

BALANCE SHEET PRESENTATION:
───────────────────────────────────────────────────────────────────────────────
Costs and Estimated Earnings in Excess of Billings:
  Job 2401                                        $  50,000
  Job 2403                                           25,882
                                                  ──────────
    Total Underbillings (Current Asset)           $  75,882

Billings in Excess of Costs and Estimated Earnings:
  Job 2402                                        $ (48,485)
                                                  ──────────
    Total Overbillings (Current Liability)        $ (48,485)

Net Under/(Over) Billing Position                 $  27,397
═══════════════════════════════════════════════════════════════════════════════
```

---

### Example B: Loss Contract Scenario

**Job 2404 Analysis:**

| Item | Original | Current |
|------|----------|---------|
| Contract Amount | $500,000 | $500,000 |
| Total Estimated Cost | $420,000 | $550,000 |
| Projected Gross Profit | $80,000 | ($50,000) |
| GP% | 16.0% | (10.0%) |

**This is a LOSS CONTRACT!**

**Required Treatment:**
Recognize entire $50,000 loss immediately, regardless of percent complete.

**Journal Entry:**
```
Dr. Loss on Construction Contracts       50,000
    Cr. Provision for Loss on Contracts         50,000
```

---

### Example C: Completed Contract

**Job 2399 - Just Completed:**

| Item | Amount |
|------|--------|
| Final Contract Amount | $1,200,000 |
| Total Actual Costs | $980,000 |
| Final Gross Profit | $220,000 |
| Final GP% | 18.33% |
| Total Billings | $1,200,000 |
| Over/Under | $0 |

**Completed Job Entry:**
```
Dr. Billings on Construction Contracts  1,200,000
    Cr. Costs and Estimated Earnings             1,200,000
```

Job is removed from WIP schedule, no over/under billing remains.

---

## The WIP Schedule Note Disclosure

**Required Financial Statement Disclosure:**

```
NOTE X - CONTRACTS IN PROGRESS

The following is a summary of contracts in progress at December 31, 2024:

  Costs incurred on uncompleted contracts               $2,270,000
  Estimated earnings                                       487,397
                                                        ──────────
                                                         2,757,397
  Less: Billings to date                                (2,730,000)
                                                        ──────────
                                                        $   27,397
                                                        ══════════

Included in the accompanying balance sheet under the
following captions:

  Costs and estimated earnings in excess of billings
    on uncompleted contracts                            $   75,882
  Billings in excess of costs and estimated earnings
    on uncompleted contracts                               (48,485)
                                                        ──────────
                                                        $   27,397
                                                        ══════════
```

---

## Summary: WIP Schedule Key Points

| Topic | Key Takeaway |
|-------|--------------|
| Purpose | Drives revenue recognition and balance sheet |
| % Complete | Costs to Date ÷ Total Estimated Cost |
| Revenue | % Complete × Contract Amount |
| Over/Under | Billings - Revenue Earned |
| Underbilling | Asset - earned but not billed |
| Overbilling | Liability - billed but not earned |
| Updates | Monthly estimate updates critical |
| Review | Management review essential |

---

## Next Section: [05 - Assurance Overview](../05-Assurance-Overview/)
