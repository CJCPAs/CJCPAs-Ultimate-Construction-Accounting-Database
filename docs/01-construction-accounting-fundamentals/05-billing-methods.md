# Billing Methods in Construction

## Overview

Construction billing is unique due to long-term contracts, progress-based payments, and industry-specific practices. Understanding billing methods is critical for cash flow management, revenue recognition, and financial statement presentation.

## Progress Billing

### Definition

Progress billing allows contractors to bill customers based on work completed, rather than waiting until project completion. This is essential for managing cash flow on long-term projects.

### AIA Billing Documents

The American Institute of Architects (AIA) documents are industry-standard forms:

#### G702 - Application and Certificate for Payment
| Field | Description |
|-------|-------------|
| Application Number | Sequential billing number |
| Period To | Billing period end date |
| Contract Sum | Original contract amount |
| Net Change by Change Orders | Approved changes |
| Contract Sum to Date | Current total contract |
| Total Completed and Stored | Work in place + materials |
| Retainage | Amount withheld (typically 10%) |
| Total Earned Less Retainage | Net billing amount |
| Less Previous Certificates | Prior billings |
| Current Payment Due | Amount due this period |

#### G703 - Continuation Sheet
Schedule of values showing:
- Item number and description
- Scheduled value (budget per line item)
- Previous applications
- Work completed this period
- Materials presently stored
- Total completed and stored
- Percentage complete
- Balance to finish
- Retainage

### Sample Progress Billing

```
APPLICATION AND CERTIFICATE FOR PAYMENT (AIA G702)

TO OWNER:      ABC Development Corp           APPLICATION NO:    5
PROJECT:       Office Building                PERIOD TO:         January 31, 2024
FROM CONTRACTOR: XYZ Construction            CONTRACT DATE:     March 1, 2023

CONTRACTOR'S APPLICATION FOR PAYMENT

1. ORIGINAL CONTRACT SUM                               $5,200,000.00
2. Net change by Change Orders                           $150,000.00
3. CONTRACT SUM TO DATE (Line 1 + 2)                   $5,350,000.00
4. TOTAL COMPLETED & STORED TO DATE                    $4,650,000.00
   (Column G on G703)
5. RETAINAGE:
   a. 10% of Completed Work                 $465,000.00
   b. 10% of Stored Material                      $0.00
   Total Retainage (Lines 5a + 5b)                       $465,000.00
6. TOTAL EARNED LESS RETAINAGE                         $4,185,000.00
   (Line 4 Less Line 5 Total)
7. LESS PREVIOUS CERTIFICATES FOR PAYMENT              $3,825,000.00
   (Line 6 from prior Certificate)
8. CURRENT PAYMENT DUE                                   $360,000.00
9. BALANCE TO FINISH, INCLUDING RETAINAGE                $700,000.00
   (Line 3 less Line 4)
```

## Retainage

### Definition

Retainage is a portion of the contract price withheld until substantial or final completion. It provides security to the owner that work will be completed.

### Common Retainage Terms

| Rate | When Used | Release Terms |
|------|-----------|---------------|
| 10% | Standard commercial | 50% at substantial completion, 50% at final |
| 5% | Government, large projects | Per contract terms |
| 0% | Some negotiated contracts | N/A |
| Graduated | Complex projects | Rate decreases as project progresses |

### Retainage Accounting

**Billing with Retainage:**
```
Gross Billing: $450,000
Retainage (10%): $45,000
Net Billing: $405,000

Journal Entry:
Dr. Accounts Receivable - Trade        $405,000
Dr. Accounts Receivable - Retainage     $45,000
    Cr. Progress Billings                       $450,000
```

**Retainage Release:**
```
Upon Substantial Completion:
Dr. Accounts Receivable - Trade        $225,000
    Cr. Accounts Receivable - Retainage         $225,000

Dr. Cash                               $225,000
    Cr. Accounts Receivable - Trade             $225,000
```

### Retainage with Subcontractors

**Withholding from Subcontractor:**
```
Subcontractor Invoice: $100,000
Retainage Withheld (10%): $10,000
Net Payment: $90,000

Journal Entry:
Dr. Work in Process - Subcontractor    $100,000
    Cr. Accounts Payable - Trade                 $90,000
    Cr. Accounts Payable - Retainage             $10,000
```

## Schedule of Values

### Purpose

A schedule of values:
1. Allocates contract price to line items
2. Establishes basis for progress billing
3. Provides transparency to owner
4. Enables tracking of completion percentage

### Considerations for Establishing Schedule

| Factor | Consideration |
|--------|---------------|
| Front-Loading | Avoid excessive early billing that reduces leverage |
| Accuracy | Values should reflect actual cost distribution |
| Detail Level | Balance detail with administrative burden |
| Mobilization | Typically limited to 3-5% of contract |
| General Conditions | Monthly allocation is common |

### Sample Schedule of Values

```
SCHEDULE OF VALUES
Project: ABC Office Building
Contract Amount: $5,350,000

Item  Description              Scheduled    % of      Previous    This      Total      % Complete
No.                            Value        Total     Period      Period    Complete
─────────────────────────────────────────────────────────────────────────────────────────────────
001   Mobilization             $  150,000    2.8%    $150,000    $      0  $150,000    100.0%
002   Site Work                $  320,000    6.0%    $320,000    $      0  $320,000    100.0%
003   Concrete Foundation      $  425,000    7.9%    $425,000    $      0  $425,000    100.0%
004   Structural Steel         $  890,000   16.6%    $845,000    $ 45,000  $890,000    100.0%
005   Exterior Walls           $  650,000   12.1%    $585,000    $ 65,000  $650,000    100.0%
006   Roofing                  $  380,000    7.1%    $190,000    $190,000  $380,000    100.0%
007   Interior Framing         $  285,000    5.3%    $213,750    $ 71,250  $285,000    100.0%
008   Mechanical (HVAC)        $  720,000   13.5%    $540,000    $ 90,000  $630,000     87.5%
009   Electrical               $  580,000   10.8%    $435,000    $ 72,500  $507,500     87.5%
010   Plumbing                 $  340,000    6.4%    $255,000    $ 42,500  $297,500     87.5%
011   Interior Finishes        $  450,000    8.4%    $135,000    $135,000  $270,000     60.0%
012   Final Completion         $  160,000    3.0%    $      0    $      0  $      0      0.0%
─────────────────────────────────────────────────────────────────────────────────────────────────
      TOTAL                   $5,350,000  100.0%  $4,093,750    $711,250 $4,805,000     89.8%
```

## Types of Construction Contracts

### Fixed-Price (Lump Sum)

**Characteristics:**
- Total price determined at contract signing
- Contractor bears cost risk
- Owner bears less risk, pays premium
- Change orders modify price

**Billing Method:**
Progress billing based on schedule of values or percentage complete.

**Revenue Recognition:**
Percentage of completion based on costs incurred.

### Cost-Plus Contracts

**Types:**
| Type | Description | Fee Calculation |
|------|-------------|-----------------|
| Cost + Fixed Fee | Reimbursable costs plus fixed fee | Fixed amount |
| Cost + Percentage | Costs plus percentage markup | % of actual costs |
| Cost + Fee with GMP | Costs + fee up to guaranteed maximum | Fixed + savings share |

**Billing Method:**
Actual costs incurred plus fee (or percentage of fee).

**Revenue Recognition:**
Costs incurred plus proportionate fee recognition.

### Time and Materials (T&M)

**Characteristics:**
- Billing based on actual time and materials
- Rates established in contract
- Owner bears cost risk
- Often used for uncertain scope

**Billing Method:**
```
Labor: Hours × Billing Rate
Materials: Actual Cost × Markup
Equipment: Hours × Equipment Rate

Example:
Carpenter - 80 hrs @ $75/hr    = $6,000
Materials (at 15% markup)       = $2,300
Equipment rental               = $  800
Total Invoice                  = $9,100
```

### Unit Price Contracts

**Characteristics:**
- Price established per unit of work
- Quantities estimated, actual billed
- Used when scope uncertain but units known

**Billing Method:**
```
Item               Unit    Contract    Actual     Extended
                   Price   Quantity    Quantity   Amount
─────────────────────────────────────────────────────────
Excavation (CY)    $15.00   10,000     9,850     $147,750
Concrete (CY)      $450.00     500       520     $234,000
Rebar (Ton)      $2,500.00      25        26      $65,000
```

## Billing Best Practices

### Timing

| Practice | Benefit |
|----------|---------|
| Bill monthly on consistent date | Predictable cash flow |
| Bill immediately upon milestone | Accelerates collection |
| Bill change orders promptly | Avoids disputes |
| Submit complete documentation | Reduces rejection |

### Documentation Requirements

1. **Progress Photos:** Visual evidence of completion
2. **Daily Reports:** Support for work performed
3. **Delivery Tickets:** Proof of materials
4. **Certified Payroll:** For prevailing wage jobs
5. **Lien Waivers:** Required for payment

### Collection Acceleration

| Strategy | Implementation |
|----------|----------------|
| Pre-billing meeting | Resolve issues before billing |
| Detailed backup | Reduce owner questions |
| Electronic submission | Faster processing |
| Follow-up calls | 48 hours after submission |
| Retainage negotiation | Seek early release |

## Billing vs. Revenue Recognition

### Key Distinction

| Concept | Definition | Financial Statement Impact |
|---------|------------|---------------------------|
| Billings | Amounts invoiced to customer | Reduces contract asset/increases liability |
| Revenue | Earned under ASC 606 | Income statement |

### Reconciliation

```
Example Reconciliation:
                            Job 2024-001
Beginning Underbillings      $100,000
+ Revenue Recognized          $296,875
- Billings This Period       ($250,000)
= Ending Underbillings        $146,875
```

### Entries

**When billing exceeds revenue recognition:**
```
Dr. Accounts Receivable                $250,000
    Cr. Billings in Excess of Costs         $XXX
    Cr. Contract Revenue                     $XXX
```

**When revenue recognition exceeds billing:**
```
Dr. Costs in Excess of Billings        $XXX
Dr. Accounts Receivable                $XXX
    Cr. Contract Revenue                    $296,875
```

## Electronic Billing and Payment

### Modern Billing Platforms

| Platform | Features |
|----------|----------|
| Textura | AIA billing, compliance, payment |
| GCPay | Progress billing, lien waiver tracking |
| Procore | Integrated project management and billing |
| Autodesk BIM 360 | Document-linked billing |

### Benefits of Electronic Billing

1. Faster submission and approval
2. Automated compliance tracking
3. Digital lien waiver management
4. Reduced errors
5. Better audit trail

---

*Previous: [WIP Schedules](04-wip-schedules.md)*  
*Next: [Equipment Accounting](06-equipment-accounting.md)*
