# A. Current Assets

## Complete Guide to Construction Company Current Assets

---

## Table of Contents

1. [Cash and Cash Equivalents](#1-cash-and-cash-equivalents)
2. [Contract Receivables](#2-contract-receivables)
3. [Retention Receivable](#3-retention-receivable)
4. [Costs in Excess of Billings (Underbillings)](#4-costs-in-excess-of-billings-underbillings)
5. [Inventory - Materials and Supplies](#5-inventory---materials-and-supplies)
6. [Prepaid Expenses](#6-prepaid-expenses)
7. [Other Current Assets](#7-other-current-assets)

---

## 1. Cash and Cash Equivalents

### Definition
Unrestricted funds available for immediate use, including:
- Checking accounts (operating, payroll)
- Savings accounts
- Money market accounts
- Cash on hand (petty cash)
- Cash equivalents (original maturity ≤ 90 days)

### What Makes Construction Cash Different

**Multiple Bank Accounts are Common:**
| Account Type | Purpose |
|--------------|---------|
| Operating Account | Day-to-day expenses |
| Payroll Account | Payroll processing |
| Retainage Account | Some require separate account |
| Joint Check Account | Joint venture projects |
| Project-Specific Account | Required by some contracts |

**Cash Flow Patterns:**
- Highly cyclical with billing cycles
- Large swings based on project timing
- Retention release creates cash spikes
- Front-loaded billing creates cash cushion

---

### Journal Entries

**Cash Receipt from Customer:**
```
Dr. Cash                              100,000
    Cr. Accounts Receivable                    100,000
```

**Payment to Vendor:**
```
Dr. Accounts Payable                   50,000
    Cr. Cash                                    50,000
```

**Payroll:**
```
Dr. Cost of Revenue - Labor            75,000
Dr. General & Administrative           25,000
    Cr. Cash                                   100,000
```

---

### Balance Sheet Presentation

**Standard:**
```
Cash and Cash Equivalents                     $1,234,567
```

**If Material Restrictions:**
```
Cash and Cash Equivalents                     $1,034,567
Restricted Cash (held for bond requirements)     200,000
```

---

### Accounting Policies to Document

1. Definition of cash equivalents used
2. Handling of restricted cash
3. Treatment of outstanding checks
4. Petty cash policies
5. Bank reconciliation frequency

---

## 2. Contract Receivables

### Definition
Amounts billed to customers for work performed under construction contracts, net of any allowance for doubtful accounts.

Also called:
- Accounts Receivable - Trade
- Accounts Receivable - Contracts
- Billed Receivables

---

### Components

| Component | Description |
|-----------|-------------|
| **Progress Billings** | Amounts billed for work performed |
| **Approved Change Orders** | Additional work billed and approved |
| **Final Billings** | Completion billings |
| **Less: Allowance** | Estimated uncollectible amounts |

---

### What is NOT Contract Receivables

| Item | Where It Goes |
|------|---------------|
| Retention withheld by customer | Retention Receivable (separate line) |
| Unbilled work (underbillings) | Costs in Excess of Billings |
| Claims not yet approved | Usually not recorded, or Other Receivables |
| Receivables from non-construction operations | Other Receivables |

---

### Aging Schedule - Construction Specifics

**Typical Construction Aging:**
| Age | Concern Level | Common Cause |
|-----|--------------|--------------|
| Current (0-30 days) | Normal | Regular billing cycle |
| 31-60 days | Monitor | Slow-paying customer, disputes |
| 61-90 days | Elevated | Potential collection issue |
| 90+ days | High | Disputed, customer financial trouble |

**IMPORTANT:** Construction receivables often have longer collection cycles than other industries. 45-60 days is often "normal" for construction.

---

### Allowance for Doubtful Accounts

**Methods:**
1. **Percentage of Receivables:** Apply historical loss rate to AR balance
2. **Aging Method:** Apply different percentages to each aging bucket
3. **Specific Identification:** Reserve specific known problem accounts

**Example - Aging Method:**

| Age | Balance | Reserve % | Reserve |
|-----|---------|-----------|---------|
| 0-30 | $500,000 | 0.5% | $2,500 |
| 31-60 | $200,000 | 2% | $4,000 |
| 61-90 | $75,000 | 5% | $3,750 |
| 90+ | $50,000 | 25% | $12,500 |
| **Total** | **$825,000** | | **$22,750** |

---

### Journal Entries

**Initial Billing:**
```
Dr. Contract Receivables              150,000
    Cr. Billings on Contracts                  150,000
```

**Establish Allowance:**
```
Dr. Bad Debt Expense                    5,000
    Cr. Allowance for Doubtful Accounts         5,000
```

**Write-off Uncollectible Account:**
```
Dr. Allowance for Doubtful Accounts    10,000
    Cr. Contract Receivables                   10,000
```

**Recovery of Previously Written-off Account:**
```
Dr. Contract Receivables               10,000
    Cr. Allowance for Doubtful Accounts        10,000

Dr. Cash                               10,000
    Cr. Contract Receivables                   10,000
```

---

### Balance Sheet Presentation

**Option 1 - Net Presentation:**
```
Contract Receivables (net of allowance of $22,750)    $802,250
```

**Option 2 - Gross with Contra:**
```
Contract Receivables                   $825,000
Less: Allowance for Doubtful Accounts   (22,750)
                                       ─────────
Net Contract Receivables               $802,250
```

---

## 3. Retention Receivable

### Definition
The portion of contract billings withheld by the customer until satisfactory completion of the contract (or a specified portion of the contract).

Also called:
- Retainage Receivable
- Holdback Receivable

---

### How Retention Works

**Typical Terms:**
- 5-10% of each progress billing is withheld
- Released upon substantial completion
- May be released in stages (50% at substantial completion, 50% at final completion)
- Final release may require lien waivers, warranties

**Example:**

Progress Billing: $100,000
Retention @ 10%: ($10,000)
Net Amount Due: $90,000

The $90,000 goes to Contract Receivables
The $10,000 goes to Retention Receivable

---

### Classification: Current vs. Non-Current

**Key Question:** When will the retention be collected?

| Collection Timing | Classification |
|------------------|----------------|
| Within one year | Current Asset |
| Beyond one year | Non-Current Asset |
| Per contract terms | Based on contract |

**GAAP Guidance:** Classify based on when collection is expected, considering:
- Contract completion dates
- Retention release provisions
- Historical collection experience

**Practical Approach:** Many contractors classify ALL retention as current because:
- Projects typically complete within 12 months
- Provides conservative working capital presentation
- Simplifies tracking

---

### Journal Entries

**When Progress Bill is Issued:**
```
Dr. Contract Receivables               90,000
Dr. Retention Receivable               10,000
    Cr. Billings on Contracts                 100,000
```

**When Retention is Released and Collected:**
```
Dr. Cash                               10,000
    Cr. Retention Receivable                   10,000
```

---

### Collectibility Considerations

**Factors Affecting Retention Collectibility:**
1. Customer financial condition
2. Contract disputes/claims
3. Completion of punch list items
4. Subcontractor lien releases obtained
5. Warranty provisions

**Should You Reserve Against Retention?**

Yes, if there's evidence of:
- Customer financial difficulties
- Unresolved disputes
- Liquidated damages exposure
- Back-charges expected

---

### Balance Sheet Presentation

**Simple:**
```
Retention Receivable                          $350,000
```

**Split Current/Non-Current:**
```
CURRENT ASSETS:
  Retention Receivable - Current              $250,000

NON-CURRENT ASSETS:
  Retention Receivable - Long-Term            $100,000
```

---

## 4. Costs in Excess of Billings (Underbillings)

### Definition

The amount by which:
**Revenue Earned to Date** exceeds **Billings to Date**

This represents work performed and revenue recognized, but not yet billed to the customer.

Also called:
- Underbillings
- Contract Assets
- Costs and Estimated Earnings in Excess of Billings

---

### The Calculation (Per Job)

```
                   Costs Incurred to Date
% Complete    =    ─────────────────────────
                   Total Estimated Costs

Revenue Earned = % Complete × Total Contract Price

Earned Gross Profit = Revenue Earned - Costs Incurred

Total Earned (Costs + GP) = Costs + Earned GP

Underbilling = Total Earned - Billings to Date
               (if positive)
```

---

### Complete Example

**Contract Details:**
- Contract Price: $1,000,000
- Total Estimated Costs: $800,000
- Costs Incurred to Date: $400,000
- Billings to Date: $350,000

**Calculation:**
| Step | Calculation | Amount |
|------|-------------|--------|
| % Complete | $400,000 / $800,000 | 50% |
| Revenue Earned | 50% × $1,000,000 | $500,000 |
| Costs Incurred | Given | $400,000 |
| Gross Profit Earned | $500,000 - $400,000 | $100,000 |
| Billings to Date | Given | $350,000 |
| **Underbilling** | $500,000 - $350,000 | **$150,000** |

This $150,000 is an **ASSET** - the company has earned revenue it hasn't billed yet.

---

### Why Underbillings Happen

| Reason | Description |
|--------|-------------|
| Billing timing | Work completed at month-end, bill goes out next month |
| Front-loaded costs | More expensive work done first |
| Retainage effect | Retention earned but not billed separately |
| Unapproved change orders | Work done but can't bill until approved |
| Billing disputes | Work performed, customer disputing billing |

---

### Journal Entry to Record Underbillings

**Method 1 - Adjust WIP Accounts:**
```
Dr. Costs in Excess of Billings       150,000
    Cr. Construction Revenue                   150,000
```

**Method 2 - Through Earned Revenue Calculation:**
The underbilling is calculated on the WIP schedule. The total earned column less billings equals underbillings. The entry records revenue equal to the earned amount.

---

### Auditor Concerns with Underbillings

**High Risk Area Because:**
1. Based on management estimates (% complete)
2. Subjective cost to complete estimates
3. Can hide cost overruns
4. Optimistic estimates inflate profits

**Red Flags:**
- Underbillings growing significantly
- Underbillings as high % of revenue
- Large underbillings on jobs nearing completion
- Underbillings on jobs with negative cash flow from customer

---

### Balance Sheet Presentation

**Standard (Current Asset):**
```
Costs and Estimated Earnings in Excess of Billings    $450,000
```

**With Note Disclosure:**
```
The following summarizes contracts in progress at December 31:

Costs incurred on uncompleted contracts         $5,000,000
Estimated earnings                               1,250,000
                                                ──────────
                                                 6,250,000
Less: Billings to date                          (6,100,000)
                                                ──────────
                                                $  150,000
                                                ══════════

Included in the accompanying balance sheet:
  Costs in excess of billings                   $  450,000
  Billings in excess of costs                     (300,000)
                                                ──────────
                                                $  150,000
                                                ══════════
```

---

## 5. Inventory - Materials and Supplies

### Definition

Materials and supplies owned by the contractor, not yet used in production:
- Raw materials for installation
- Construction supplies
- Work-in-progress items (prefabricated)
- Small tools and consumables

---

### Types of Construction Inventory

| Type | Description | Valuation |
|------|-------------|-----------|
| **Job Materials** | Materials purchased for specific jobs | At cost, transferred to job cost when used |
| **Stock Materials** | Common materials kept on hand | Lower of cost or NRV |
| **Supplies** | Consumables (fasteners, small items) | At cost |
| **Prefabricated Items** | Items being fabricated for installation | Accumulated cost |

---

### Job vs. Inventory Accounting

**Materials Purchased FOR a Specific Job:**
```
Dr. Cost of Revenue - Materials (Job 101)     25,000
    Cr. Accounts Payable                              25,000
```
Goes directly to job cost, NOT inventory.

**Materials Purchased FOR Stock:**
```
Dr. Inventory - Materials                     25,000
    Cr. Accounts Payable                              25,000
```
Stays in inventory until used.

**When Stock Materials Used on a Job:**
```
Dr. Cost of Revenue - Materials (Job 102)     10,000
    Cr. Inventory - Materials                         10,000
```

---

### The Uninstalled Materials Problem (Revisited)

**Scenario:** $500,000 of HVAC equipment purchased for Job 103, sitting in warehouse at year-end.

**Three Options:**

| Option | Treatment | Effect on WIP |
|--------|-----------|---------------|
| 1. Inventory | Record as inventory, not job cost | No impact on % complete |
| 2. Job Cost | Record as job cost | Inflates % complete |
| 3. ASC 606 Treatment | Recognize revenue = cost (zero margin) | Proper matching |

**Best Practice:**
- Significant uninstalled materials should NOT inflate percentage complete
- Record at cost with zero margin until installed
- Or keep in inventory until installed

---

### Valuation

**Rule:** Lower of Cost or Net Realizable Value (NRV)

**NRV Impairment Entry:**
```
Dr. Inventory Impairment Loss               5,000
    Cr. Inventory - Materials                       5,000
```

---

### Balance Sheet Presentation

**Simple:**
```
Inventory                                        $125,000
```

**Detailed:**
```
Inventory:
  Materials                              $75,000
  Supplies                                35,000
  Prefabricated Items                     15,000
                                        ─────────
  Total Inventory                        $125,000
```

---

## 6. Prepaid Expenses

### Definition

Expenses paid in advance of receiving the benefit:
- Insurance premiums
- Rent deposits
- Prepaid software licenses
- Prepaid bonding fees

---

### Common Prepaid Items in Construction

| Item | Typical Term | Amortization |
|------|--------------|--------------|
| General Liability Insurance | Annual | 12 months |
| Workers' Compensation | Annual | 12 months |
| Builders Risk (per project) | Project duration | Over project |
| Equipment Insurance | Annual | 12 months |
| Bond Premiums | Per bond | Over bond period |
| Vehicle Insurance | Annual | 12 months |
| Software Subscriptions | Annual | 12 months |
| Rent | Monthly or Annual | Recognize as incurred |

---

### Journal Entries

**Payment of Annual Insurance Premium:**
```
Dr. Prepaid Insurance                   120,000
    Cr. Cash                                    120,000
```

**Monthly Amortization:**
```
Dr. Insurance Expense - G&A              10,000
    Cr. Prepaid Insurance                        10,000
```

**Job-Specific Insurance (charged to job):**
```
Dr. Cost of Revenue - Insurance (Job 105)  5,000
    Cr. Prepaid Insurance                         5,000
```

---

### Presentation

```
Prepaid Expenses                              $85,000
```

Or, if material, breakout in notes:
```
Prepaid expenses consist of:
  Prepaid insurance                     $60,000
  Prepaid rent                           15,000
  Other prepaids                         10,000
                                        ────────
  Total prepaid expenses                $85,000
```

---

## 7. Other Current Assets

### Definition

Current assets not fitting other categories:
- Deposits (if refundable within 1 year)
- Employee advances
- Receivables from related parties
- Short-term notes receivable
- Tax refunds receivable
- Miscellaneous receivables

---

### Common "Other" Items in Construction

| Item | Description |
|------|-------------|
| **Bid Deposits** | Refundable amounts submitted with bids |
| **Equipment Deposits** | Deposits for rented equipment |
| **Utility Deposits** | Deposits for job-site utilities |
| **Employee Advances** | Loans to employees |
| **Due from Affiliates** | Amounts owed from related entities |
| **Tax Refunds** | Estimated tax overpayments |
| **Insurance Claims Receivable** | Claims filed, expected recovery |

---

### Journal Entries

**Employee Advance:**
```
Dr. Employee Advances                    2,000
    Cr. Cash                                     2,000
```

**Repayment via Payroll Deduction:**
```
Dr. Wages Payable                        2,000
    Cr. Employee Advances                        2,000
```

**Bid Deposit Submitted:**
```
Dr. Deposits                             5,000
    Cr. Cash                                     5,000
```

**Bid Deposit Returned:**
```
Dr. Cash                                 5,000
    Cr. Deposits                                 5,000
```

---

### Presentation

```
Other Current Assets                          $35,000
```

If significant, detail in notes:
```
Other current assets consist of:
  Employee advances                      $10,000
  Deposits                                15,000
  Insurance claims receivable              8,000
  Other                                    2,000
                                        ─────────
  Total other current assets             $35,000
```

---

## Summary: Current Assets Key Points

| Account | Key Accounting Issue | Audit Focus |
|---------|---------------------|-------------|
| Cash | Reconciliation, restrictions | Bank confirms |
| Contract Receivables | Collectibility, allowance | Aging, confirms |
| Retention Receivable | Classification, collectibility | Contract terms |
| Underbillings | Estimation, % complete accuracy | WIP testing |
| Inventory | Valuation, job allocation | Physical count |
| Prepaids | Amortization accuracy | Verify coverage |
| Other | Existence, collectibility | Support documentation |

---

## Next Section: [B. Non-Current Assets](../B-Non-Current-Assets/)
