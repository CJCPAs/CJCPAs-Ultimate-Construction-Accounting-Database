# Change Orders and Claims Accounting

## Overview

Change orders and claims are integral to construction contracts. Proper accounting requires understanding when to recognize revenue and how to present these items in financial statements.

## Change Orders

### Definition

A change order is a modification to the original contract that changes:
- Scope of work
- Contract price
- Contract time
- Or any combination thereof

### Types of Change Orders

| Type | Description | Revenue Treatment |
|------|-------------|-------------------|
| Approved | Written, priced, signed by owner | Include in contract price |
| Pending | Submitted, awaiting approval | Variable consideration analysis |
| Unpriced | Scope approved, price TBD | Estimate if probable and measurable |
| Constructive | Owner directive without formal CO | Variable consideration analysis |

### Change Order Lifecycle

```
1. Identification
   ↓
2. Pricing/Estimating
   ↓
3. Submission to Owner
   ↓
4. Negotiation
   ↓
5. Approval/Rejection
   ↓
6. Contract Amendment
```

### Accounting for Approved Change Orders

**Entry when approved:**
```
Change Order Value: $150,000
Additional Estimated Cost: $120,000

Original Contract: $5,000,000
New Contract Total: $5,150,000

Original Estimated Cost: $4,250,000
New Estimated Cost: $4,370,000

Percent Complete (before CO): 60%
Revenue Recognized (before CO): $3,000,000

New Percent Complete: Costs to Date / $4,370,000
(Assuming same costs to date: $2,550,000 / $4,370,000 = 58.4%)

Revenue Recognized: 58.4% × $5,150,000 = $3,006,600
Cumulative Catch-up: $3,006,600 - $3,000,000 = $6,600
```

### Accounting for Pending Change Orders

**ASC 606 Variable Consideration Analysis:**

Include in transaction price if:
1. Amount can be reasonably estimated
2. Significant revenue reversal is not probable

**Factors indicating inclusion:**
- Owner has approved scope
- Only pricing is being negotiated
- Historical pattern of approval
- Legal enforceability

**Factors indicating constraint:**
- Owner disputes validity
- Significant uncertainty in outcome
- Limited experience with owner
- Resolution expected to take extended time

### Change Order Documentation

| Document | Purpose |
|----------|---------|
| Request for Information (RFI) | Clarify design/specifications |
| Architect's Supplemental Instruction (ASI) | Design clarification |
| Proposal Request | Owner requests pricing |
| Change Order Proposal | Contractor's pricing submission |
| Change Order | Final approved document |
| Field Order | Emergency or minor changes |

## Claims

### Definition

A claim is a request for payment beyond the contract price for:
- Owner-caused delays
- Acceleration
- Disruption
- Differing site conditions
- Design errors
- Breach of contract

### Types of Claims

| Claim Type | Basis | Common Causes |
|------------|-------|---------------|
| Delay | Time extension costs | Owner delays, weather |
| Disruption | Loss of productivity | Out-of-sequence work |
| Acceleration | Premium time costs | Schedule compression |
| Differing Conditions | Changed conditions | Unforeseen subsurface |
| Design Defects | Errors and omissions | Professional negligence |

### Claim Recognition Criteria

Under ASC 606, recognize claims when:
1. Contract or law supports contractor's right
2. Amount can be reliably estimated
3. Collection is probable
4. Not subject to significant reversal

**Conservative approach:** Often wait until resolved or nearly resolved.

### Claim Calculation Components

#### Delay Claim

```
DELAY CLAIM CALCULATION

Extended General Conditions:
  Superintendent (2 months × $12,000)           $24,000
  Project Manager (2 months × $15,000)          $30,000
  Job Site Office (2 months × $2,500)            $5,000
  Utilities (2 months × $1,200)                  $2,400
  Insurance (2 months × $3,500)                  $7,000
  Bonds (2 months × $2,000)                      $4,000
─────────────────────────────────────────────────────────
Total Extended GCs                              $72,400

Escalation:
  Material escalation                           $45,000
  Labor escalation                              $28,000
─────────────────────────────────────────────────────────
Total Escalation                                $73,000

Home Office Overhead (Eichleay Formula):
  Contract Billings / Total Billings × HO Overhead × Days
  $5,000,000 / $25,000,000 × $1,200,000 × 60/365 = $39,452
─────────────────────────────────────────────────────────
Total Home Office Overhead                      $39,452

Subtotal                                       $184,852
Markup (10%)                                    $18,485
─────────────────────────────────────────────────────────
TOTAL CLAIM                                    $203,337
```

#### Disruption Claim (Measured Mile Analysis)

```
MEASURED MILE ANALYSIS

Task: Concrete Placement

Unimpacted Period (Measured Mile):
  Cubic Yards Placed: 500 CY
  Labor Hours: 400 hours
  Productivity: 1.25 CY/hour

Impacted Period:
  Cubic Yards Placed: 500 CY
  Labor Hours: 625 hours
  Productivity: 0.80 CY/hour

Lost Productivity:
  Expected Hours (500 CY × 0.8 hr/CY): 400 hours
  Actual Hours: 625 hours
  Lost Hours: 225 hours

Claim:
  Lost Hours × Labor Rate × Burden
  225 hours × $45/hour × 1.35 = $13,669
```

### Claims Accounting Entries

**When claim is probable and estimable (conservative):**
```
Claim amount: $200,000
Recognition: 50% (due to uncertainty)

Dr. Claim Receivable                    $100,000
    Cr. Contract Revenue                        $100,000
```

**When claim is resolved:**
```
Settlement amount: $175,000
Previously recognized: $100,000

Dr. Cash/Accounts Receivable             $175,000
    Cr. Claim Receivable                        $100,000
    Cr. Contract Revenue                         $75,000
```

## Backcharges

### Definition

Backcharges are costs charged to another party (usually subcontractor) for:
- Work not performed
- Defective work requiring correction
- Damage caused by subcontractor
- Cleanup costs

### Accounting for Backcharges

**Charging subcontractor:**
```
Correction work performed: $15,000

Dr. Accounts Receivable - Subcontractor    $15,000
    Cr. Work in Process (or Other Income)         $15,000
```

**Deducting from subcontractor payment:**
```
Subcontractor invoice: $50,000
Less backcharge: $15,000
Net payment: $35,000

Dr. Accounts Payable - Subcontractor       $50,000
    Cr. Accounts Receivable - Subcontractor       $15,000
    Cr. Cash                                      $35,000
```

### Being Backcharged

```
Owner backcharge for cleanup: $5,000

Dr. Work in Process - Other Costs           $5,000
    Cr. Accounts Payable                           $5,000
```

## Liquidated Damages

### Definition

Predetermined amounts due to owner for late completion, established in contract.

### Accounting Treatment

**Accrual when probable:**
```
10 days late × $5,000/day = $50,000

Dr. Contract Revenue (or Loss)             $50,000
    Cr. Accrued Liquidated Damages                $50,000
```

**Offset against billings:**
```
When deducted from final payment:

Dr. Accrued Liquidated Damages             $50,000
    Cr. Accounts Receivable                       $50,000
```

### Impact on Revenue Recognition

Liquidated damages are negative variable consideration:
- Reduce transaction price when probable
- Update estimate each reporting period

## Financial Statement Presentation

### Balance Sheet

| Item | Classification | Notes |
|------|----------------|-------|
| Approved Change Orders | Part of contract assets/liabilities | Included in WIP |
| Pending Change Orders | May be contract asset or disclosed | Depends on recognition |
| Claims Receivable | Separate line item or disclosed | May be long-term |
| Backcharges Receivable | Accounts receivable | May need allowance |
| Liquidated Damages | Contract liability or accrued expense | Offset to A/R |

### Disclosure Requirements

```
NOTE X - CONSTRUCTION CONTRACT RECEIVABLES AND CLAIMS

The Company has claims against owners totaling $450,000 related to owner-caused
delays and changes in project scope. These claims are included in contract
assets to the extent the Company believes collection is probable and the
amounts can be reasonably estimated. The ultimate resolution of these claims
could result in amounts materially different from recorded amounts.

Unapproved change orders included in contract revenue totaled $280,000 at
December 31, 2024. Management believes these amounts will be collected based
on documentation supporting the changes and the Company's historical
experience with similar change orders.
```

## Audit Considerations

### Change Order Testing

| Procedure | Purpose |
|-----------|---------|
| Review pending CO log | Identify unapproved amounts |
| Test approval documentation | Verify revenue recognition |
| Analyze historical patterns | Assess variable consideration |
| Evaluate collectibility | Assess constraint |
| Review subsequent approvals | Confirm estimates |

### Claims Testing

| Procedure | Purpose |
|-----------|---------|
| Review claim documentation | Evaluate legal basis |
| Evaluate entitlement | Assess probability |
| Test calculations | Verify amounts |
| Obtain legal representations | Evaluate resolution likelihood |
| Review settlement history | Assess estimation |

### Red Flags

1. Significant pending change orders relative to contract size
2. Aged pending items without resolution
3. Claims without strong legal support
4. Pattern of change order disputes with owner
5. Aggressive revenue recognition on unapproved items

---

*Previous: [Contract Types](02-contract-types.md)*  
*Next: [Subcontractor Accounting](04-subcontractor-accounting.md)*
