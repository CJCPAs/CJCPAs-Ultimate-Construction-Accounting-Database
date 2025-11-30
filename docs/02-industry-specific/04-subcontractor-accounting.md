# Subcontractor Accounting

## Overview

Subcontractor management is critical for construction companies. Subcontracted work often represents 50-70% of contract costs, making proper accounting and controls essential.

## Subcontract Process

### Lifecycle

```
1. Solicitation
   ↓
2. Bid Analysis
   ↓
3. Award/Contracting
   ↓
4. Mobilization
   ↓
5. Performance/Billing
   ↓
6. Change Management
   ↓
7. Completion/Closeout
```

### Key Documents

| Document | Purpose | Accounting Use |
|----------|---------|----------------|
| Subcontract Agreement | Defines scope, price, terms | Commitment tracking |
| Schedule of Values | Allocates price to line items | Progress billing |
| Pay Application | Request for payment | Invoice processing |
| Lien Waiver | Releases lien rights | Payment requirement |
| Change Order | Modifies agreement | Cost tracking |
| Backcharge Notice | Documents deductions | Cost recovery |
| Certificate of Insurance | Proves coverage | Compliance |

## Subcontract Accounting Entries

### Award and Commitment

**Commitment tracking (memo entry or system):**
```
Subcontract Award: $500,000
No journal entry - tracked in commitment system

Commitment Report:
Job 2024-001
Subcontractor: ABC Electric
Original Contract: $500,000
Change Orders: $0
Revised Contract: $500,000
Billed to Date: $0
Remaining: $500,000
```

### Progress Billing Receipt

**Recording subcontractor invoice:**
```
Subcontractor Pay Application:
  Work Completed This Period: $85,000
  Materials Stored: $15,000
  Total Completed & Stored: $100,000
  Less Retainage (10%): ($10,000)
  Net Payment Due: $90,000

Journal Entry:
Dr. Work in Process - Subcontract (Job)    $100,000
    Cr. Accounts Payable - Subcontractors            $90,000
    Cr. Accounts Payable - Retainage                 $10,000
```

### Payment Processing

**Subcontractor payment:**
```
Dr. Accounts Payable - Subcontractors      $90,000
    Cr. Cash                                        $90,000
```

### Retainage Release

**Upon substantial completion (50% release):**
```
Accumulated Retainage: $50,000
Release: $25,000

Dr. Accounts Payable - Retainage           $25,000
    Cr. Cash                                        $25,000
```

**Final retainage release:**
```
Dr. Accounts Payable - Retainage           $25,000
    Cr. Cash                                        $25,000
```

### Subcontract Change Orders

**Approved change order:**
```
Change Order Amount: $35,000

Update commitment in system:
Original Contract: $500,000
Change Orders: $35,000
Revised Contract: $535,000

When billed:
Dr. Work in Process - Subcontract (Job)     $35,000
    Cr. Accounts Payable - Subcontractors           $31,500
    Cr. Accounts Payable - Retainage                 $3,500
```

## Lien Waiver Requirements

### Types of Lien Waivers

| Type | When Used | Effect |
|------|-----------|--------|
| Conditional - Progress | With progress payment | Effective when payment clears |
| Unconditional - Progress | After payment clears | Immediately effective |
| Conditional - Final | With final payment | Effective when payment clears |
| Unconditional - Final | After final payment | Releases all rights |

### Lien Waiver Workflow

```
1. Subcontractor submits pay application
   ↓
2. GC reviews and approves
   ↓
3. Subcontractor provides conditional waiver
   ↓
4. GC processes payment
   ↓
5. Subcontractor provides unconditional waiver (prior period)
   ↓
6. Process repeats monthly
```

### Accounting Control

**Payment release checklist:**
- [ ] Pay application approved by PM
- [ ] Insurance certificate current
- [ ] Conditional lien waiver for current billing
- [ ] Unconditional lien waiver for prior billing
- [ ] Certified payroll (if required)
- [ ] No outstanding backcharges
- [ ] Within subcontract budget

## Certified Payroll and Compliance

### Prevailing Wage Jobs

**Requirements:**
- Weekly certified payroll reports
- Specific wage rates by classification
- Fringe benefits properly paid
- Apprenticeship ratios maintained

**Compliance tracking:**
```
CERTIFIED PAYROLL COMPLIANCE LOG

Subcontractor: ABC Electric
Project: City Hall Renovation (Prevailing Wage)

Week Ending    Submitted    Compliant    Notes
─────────────────────────────────────────────────
01/07/2024     01/14/2024   Yes          -
01/14/2024     01/21/2024   Yes          -
01/21/2024     01/28/2024   No           Missing fringe
01/28/2024     02/04/2024   Yes          Corrected
```

### Insurance Compliance

**Minimum requirements tracking:**
```
SUBCONTRACTOR INSURANCE LOG

Subcontractor     GL          Auto        WC          Expires
─────────────────────────────────────────────────────────────────
ABC Electric      $2M/$4M     $1M         Yes         06/30/2024
XYZ Plumbing      $1M/$2M     $1M         Yes         12/31/2024
DEF Concrete      $2M/$4M     $1M         Yes         03/15/2024 *

* Expiring within 30 days - request renewal
```

## Backcharges

### Types of Backcharges

| Type | Description | Documentation |
|------|-------------|---------------|
| Incomplete Work | Work not completed per contract | Scope verification |
| Defective Work | Work requiring correction | Inspection reports |
| Damage | Damage to other work/property | Photos, repair invoices |
| Cleanup | Cleanup not performed | Daily reports, photos |
| Equipment | Use of GC equipment | Equipment logs |
| Supervision | Additional oversight required | Time records |

### Backcharge Process

```
1. Identify Issue
   ↓
2. Document (photos, reports)
   ↓
3. Notify Subcontractor (written)
   ↓
4. Allow Cure Period (if possible)
   ↓
5. Perform Work or Incur Cost
   ↓
6. Issue Backcharge
   ↓
7. Deduct from Payment
```

### Backcharge Accounting

**Recording backcharge:**
```
GC performs work to correct subcontractor defect:
Labor: $3,500
Materials: $1,200
Total: $4,700

Dr. Accounts Receivable - Subcontractor     $4,700
    Cr. Work in Process (labor savings)             $3,500
    Cr. Inventory (materials)                       $1,200
```

**Offsetting against payment:**
```
Sub invoice: $45,000
Backcharge: ($4,700)
Net payment: $40,300

Dr. Accounts Payable - Subcontractors      $45,000
    Cr. Accounts Receivable - Sub Backcharge        $4,700
    Cr. Cash                                       $40,300
```

## Subcontractor Default

### Early Warning Signs

| Indicator | Risk Level | Action |
|-----------|------------|--------|
| Late pay applications | Medium | Verify work status |
| Slow progress | High | Evaluate capability |
| Labor shortages | High | Request staffing plan |
| Supplier complaints | High | Joint check consideration |
| Insurance lapses | Critical | Stop work, require coverage |
| Mechanic's liens filed | Critical | Legal review |

### Default Response Options

| Option | Description | When Used |
|--------|-------------|-----------|
| Supplementation | Add crews to assist | Minor delays |
| Takeover | Assume subcontract work | Persistent issues |
| Termination | End subcontract | Material breach |
| Bond Claim | Claim on performance bond | Bonded subcontracts |

### Accounting for Default

**Termination and completion by others:**
```
Original Subcontract: $500,000
Paid to Date: $350,000
Remaining Value: $150,000

Completion by Replacement:
New Subcontract: $185,000
Extra Cost: $35,000

Accounting:
Dr. Work in Process - Sub (new)            $185,000
    Cr. Accounts Payable (new sub)                 $185,000

If bond claim:
Dr. Receivable from Surety                  $35,000
    Cr. Extra Cost Recovery                         $35,000
```

## Joint Check Agreements

### Purpose

Protect GC from subcontractor failing to pay suppliers or lower-tier subs.

### How It Works

```
Material Supplier → Sub → GC

Joint Check:
GC issues check payable to:
"ABC Electric AND XYZ Supply"

Both must endorse for deposit
```

### Accounting

**Joint check issuance:**
```
Sub invoice: $85,000
Material supplier portion: $35,000

Dr. Accounts Payable - Sub                 $85,000
    Cr. Cash (joint check to sub + supplier)       $35,000
    Cr. Cash (check to sub only)                   $50,000

Note: Ensure both payees endorse joint check
```

## Reporting and Analysis

### Subcontractor Status Report

```
SUBCONTRACTOR STATUS REPORT
Project: ABC Office Building
As of: December 31, 2024

                          Original   Change    Current    Billed    Retain    Balance
Subcontractor             Contract   Orders    Contract   to Date   Held      to Bill
─────────────────────────────────────────────────────────────────────────────────────────
ABC Electric              $500,000   $35,000   $535,000   $425,000  $42,500   $110,000
XYZ Plumbing             $320,000   $15,000   $335,000   $268,000  $26,800    $67,000
DEF Mechanical           $450,000        $0   $450,000   $405,000  $40,500    $45,000
GHI Drywall              $185,000    $8,500   $193,500   $174,150  $17,415    $19,350
─────────────────────────────────────────────────────────────────────────────────────────
Total                  $1,455,000   $58,500 $1,513,500 $1,272,150 $127,215   $241,350
```

### Cost Variance by Trade

```
SUBCONTRACTOR COST VARIANCE ANALYSIS

                    Budget      Committed    Variance    Status
Trade               (Est)       (Actual)     Over/(Under)
──────────────────────────────────────────────────────────────
Electrical          $520,000    $535,000     ($15,000)   Review
Plumbing            $310,000    $335,000     ($25,000)   Issue
Mechanical          $475,000    $450,000      $25,000    Favorable
Drywall             $200,000    $193,500       $6,500    Favorable
──────────────────────────────────────────────────────────────
Total             $1,505,000  $1,513,500      ($8,500)
```

## Internal Controls

### Segregation of Duties

| Function | Responsibility |
|----------|----------------|
| Contract Execution | Operations/PM |
| Invoice Approval | Project Manager |
| Payment Processing | Accounts Payable |
| Lien Waiver Collection | AP or PM |
| Check Signing | Controller/CFO |

### Control Procedures

1. **Subcontract approval matrix** - Dollar thresholds for approval
2. **Insurance verification** - Before contract execution
3. **Pay application review** - PM approval required
4. **Lien waiver tracking** - No payment without waivers
5. **Retainage reconciliation** - Monthly verification
6. **Change order approval** - Per authority matrix
7. **Backcharge documentation** - Written notice required

---

*Previous: [Change Orders](03-change-orders.md)*  
*Next: [Audit Planning](../03-financial-statement-audits/01-audit-planning.md)*
