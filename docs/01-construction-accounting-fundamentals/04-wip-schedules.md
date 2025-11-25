# Work-in-Progress (WIP) Schedules

## Overview

The Work-in-Progress (WIP) schedule is the most critical financial report for construction companies. It summarizes the status of all active contracts, calculates revenue recognition, and determines contract assets and liabilities.

## Purpose of WIP Schedules

1. **Revenue Recognition:** Calculate earned revenue under ASC 606
2. **Financial Statement Preparation:** Determine contract assets/liabilities
3. **Management Tool:** Monitor job profitability and progress
4. **Banking Requirement:** Required for most construction loans
5. **Bonding Requirement:** Required by surety companies
6. **Audit Evidence:** Primary document for auditing construction revenue

## WIP Schedule Components

### Standard Columns

| Column | Description | Source |
|--------|-------------|--------|
| Job Number | Unique project identifier | Job master file |
| Job Name | Project description | Contract |
| Contract Amount | Total contract price | Original + change orders |
| Estimated Total Cost | Current cost estimate | Cost estimate |
| Cost to Date | Actual costs incurred | Job cost ledger |
| Estimated Cost to Complete | Remaining costs | Estimate - costs to date |
| Percent Complete | Progress measure | Costs to date / Total estimated |
| Earned Revenue | Revenue recognized | % complete × contract |
| Billings to Date | Total billed | Billing records |
| Over/(Under) Billings | Contract asset/liability | Billings - earned revenue |
| Gross Profit | Recognized profit | Earned revenue - costs |

### Extended WIP Information

| Column | Description | Purpose |
|--------|-------------|---------|
| Original Contract | Initial contract amount | Variance tracking |
| Change Orders | Approved modifications | Contract tracking |
| Pending Changes | Unapproved modifications | Risk assessment |
| Original Estimate | Initial cost estimate | Fade analysis |
| Backlog | Unearned portion | Pipeline tracking |
| Gross Profit % | Profit margin | Performance metric |

## WIP Schedule Format

### Standard WIP Schedule

```
COMPANY NAME
WORK IN PROGRESS SCHEDULE
As of December 31, 2024

                                                                              Earned    Billings   Over/(Under)  Gross    Gross
Job #    Job Name          Contract    Est Total   Cost to    Est to    %     Revenue   to Date    Billings      Profit   Profit%
                           Amount      Cost        Date       Complete  Compl
───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
2024-001 ABC Office Bldg   $5,350,000  $4,600,000  $4,125,000 $475,000  89.7% $4,796,875 $4,650,000 ($146,875)   $671,875  14.0%
2024-002 XYZ Warehouse     $3,200,000  $2,750,000  $1,925,000 $825,000  70.0% $2,240,000 $2,400,000  $160,000    $315,000  14.1%
2024-003 Highway Bridge    $8,500,000  $7,400,000  $5,180,000 $2,220,000 70.0% $5,950,000 $5,750,000 ($200,000)  $770,000  12.9%
2024-004 School Renovation $2,100,000  $1,850,000  $1,480,000 $370,000  80.0% $1,680,000 $1,890,000  $210,000    $200,000  11.9%
2024-005 Medical Center    $12,000,000 $10,200,000 $3,060,000 $7,140,000 30.0% $3,600,000 $3,200,000 ($400,000)  $540,000  15.0%
───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
TOTALS                     $31,150,000 $26,800,000 $15,770,000 $11,030,000     $18,266,875 $17,890,000 ($376,875) $2,496,875

SUMMARY:
  Total Underbillings (Contract Assets):    $746,875
  Total Overbillings (Contract Liabilities): $370,000
  Net Underbillings:                        $376,875
```

## WIP Calculations

### Percent Complete Calculation

**Cost-to-Cost Method (Most Common):**
```
% Complete = Costs Incurred to Date / Total Estimated Costs

Example:
Costs to Date: $4,125,000
Total Estimated Costs: $4,600,000
% Complete = $4,125,000 / $4,600,000 = 89.67%
```

**Alternative Methods:**
| Method | Formula | Use When |
|--------|---------|----------|
| Labor Hours | Hours to Date / Total Est Hours | Labor-intensive work |
| Labor Dollars | Labor $ to Date / Total Est Labor $ | Labor drives costs |
| Units Produced | Units Complete / Total Units | Repetitive work |
| Output Survey | Physical inspection | Engineer estimates |

### Earned Revenue Calculation

```
Earned Revenue = % Complete × Total Contract Amount

Example:
% Complete: 89.67%
Contract Amount: $5,350,000
Earned Revenue = 89.67% × $5,350,000 = $4,796,875
```

### Over/Under Billings Calculation

```
Underbilling (Contract Asset):
  When: Earned Revenue > Billings to Date
  Amount = Earned Revenue - Billings

Overbilling (Contract Liability):
  When: Billings to Date > Earned Revenue
  Amount = Billings - Earned Revenue

Example 1 - Underbilling:
  Earned Revenue: $4,796,875
  Billings to Date: $4,650,000
  Underbilling: $146,875 (Asset)

Example 2 - Overbilling:
  Earned Revenue: $2,240,000
  Billings to Date: $2,400,000
  Overbilling: $160,000 (Liability)
```

### Gross Profit Calculation

```
Gross Profit to Date = Earned Revenue - Costs to Date

Example:
Earned Revenue: $4,796,875
Costs to Date: $4,125,000
Gross Profit: $671,875 (14.0%)
```

## WIP Analysis and Interpretation

### Fade Analysis

Compares original estimate to current estimate:

```
                            Original    Current     Fade
                            Estimate    Estimate    (Unfavorable)
Contract Amount             $5,200,000  $5,350,000  $150,000 F
Estimated Total Cost        $4,500,000  $4,600,000  ($100,000) U
Estimated Gross Profit       $700,000    $750,000   $50,000 F
Gross Profit %                13.46%      14.02%     0.56% F
```

### WIP Trend Analysis

Track WIP metrics over time:

| Metric | Q1 | Q2 | Q3 | Q4 | Trend |
|--------|----|----|----|----|-------|
| Net Underbillings | $250K | $320K | $290K | $377K | ↑ |
| Avg GP % | 12.5% | 13.1% | 13.8% | 14.0% | ↑ |
| Backlog | $18M | $22M | $25M | $28M | ↑ |
| Jobs with Fade | 2 | 1 | 3 | 2 | → |

### Red Flags in WIP

| Red Flag | Indication | Action |
|----------|------------|--------|
| Significant underbillings | Cash flow issue, aggressive revenue | Review billing practices |
| Large overbillings | Potential future revenue decline | Assess earned profit |
| Jobs with 0% profit | Breakeven or loss | Review estimates |
| High % complete, low billings | Collection risk | Accelerate billing |
| Declining GP percentages | Estimating problems | Analyze fade |
| Stale jobs (no activity) | Project issues | Investigate status |

## WIP Journal Entries

### Monthly Revenue Recognition

**When Earned Revenue > Prior Month:**
```
Dr. Costs in Excess of Billings OR
Dr. Accounts Receivable (if billed)           XXX
    Cr. Contract Revenue                           XXX
```

### Recording Overbillings

**When Billings Exceed Earned:**
```
Dr. Cash/Accounts Receivable                  XXX
    Cr. Billings in Excess of Costs                XXX
```

### Adjusting Entry for WIP Changes

**To record monthly WIP adjustment:**
```
Prior Month Earned Revenue: $4,500,000
Current Month Earned Revenue: $4,796,875
Revenue to Recognize: $296,875

Dr. Costs in Excess of Billings              $146,875
Dr. Accounts Receivable                       150,000
    Cr. Contract Revenue                           $296,875
```

## WIP Schedule Variations

### Detailed WIP with Cost Breakdown

```
Job: 2024-001 ABC Office Building

                        Budget      Actual     Variance    Est to      Total Est
Cost Category                       to Date                Complete    at Compl
─────────────────────────────────────────────────────────────────────────────────
Direct Labor           $450,000    $425,000    $25,000    $50,000    $475,000
Labor Burden           $168,750    $159,375    $9,375     $18,750    $178,125
Materials              $850,000    $890,000    ($40,000)  $85,000    $975,000
Subcontractors       $2,400,000  $2,200,000   $200,000   $275,000  $2,475,000
Equipment              $175,000    $165,000    $10,000    $20,000    $185,000
Other Direct           $250,000    $245,625    $4,375     $20,000    $265,625
Job Overhead           $206,250    $240,000    ($33,750)  $6,250     $246,250
─────────────────────────────────────────────────────────────────────────────────
Total                $4,500,000  $4,325,000   $175,000   $475,000  $4,800,000
```

### Summary WIP by Project Manager

```
PROJECT MANAGER SUMMARY
As of December 31, 2024

                      # of    Contract     Earned      Gross      GP%
Project Manager      Jobs     Value        Revenue     Profit
────────────────────────────────────────────────────────────────────
John Smith            5      $18,500,000  $12,250,000  $1,750,000  14.3%
Jane Doe              4      $12,650,000   $6,016,875    $746,875  12.4%
────────────────────────────────────────────────────────────────────
Company Total         9      $31,150,000  $18,266,875  $2,496,875  13.7%
```

### WIP with Retainage Tracking

```
                                             Retainage
Job        Earned     Billed     Collected   Receivable   Net A/R
─────────────────────────────────────────────────────────────────────
2024-001   $4,796,875 $4,650,000 $4,185,000  $465,000    $465,000
2024-002   $2,240,000 $2,400,000 $2,040,000  $240,000    $360,000
─────────────────────────────────────────────────────────────────────
Total      $7,036,875 $7,050,000 $6,225,000  $705,000    $825,000
```

## WIP Best Practices

### Monthly Procedures

1. **Update Cost Estimates**
   - Review actual vs. budget
   - Revise estimated costs to complete
   - Document significant changes

2. **Verify Costs to Date**
   - Reconcile to job cost ledger
   - Confirm all costs recorded
   - Review cut-off procedures

3. **Review Contract Status**
   - Update for approved change orders
   - Evaluate pending changes
   - Assess claim status

4. **Calculate and Review**
   - Compute new percentage complete
   - Calculate earned revenue
   - Analyze variances

5. **Management Review**
   - Project manager sign-off
   - Operations review
   - Executive approval

### Documentation Requirements

| Document | Purpose | Retention |
|----------|---------|-----------|
| Cost Estimates | Support total cost | Life of contract + 3 years |
| Change Orders | Support contract amount | Life of contract + 3 years |
| Monthly WIP | Revenue recognition | 7 years minimum |
| Variance Analysis | Support estimates | Life of contract |
| Manager Sign-off | Accountability | Life of contract |

### Internal Controls

1. **Segregation of Duties**
   - Estimators separate from cost accountants
   - Project managers review, not prepare
   - CFO/Controller final approval

2. **Approval Requirements**
   - Estimate revisions require approval
   - Change orders require documentation
   - Significant changes require executive approval

3. **Reconciliation**
   - WIP to general ledger monthly
   - Billings to accounts receivable
   - Costs to date to job cost ledger

---

*Previous: [Job Costing](03-job-costing.md)*  
*Next: [Billing Methods](05-billing-methods.md)*
