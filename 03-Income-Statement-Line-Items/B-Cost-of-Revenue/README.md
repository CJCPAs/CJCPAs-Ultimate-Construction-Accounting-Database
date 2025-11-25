# B. Cost of Revenue

## Complete Guide to Construction Company Direct Costs

---

## Table of Contents

1. [Overview: Cost of Revenue](#overview-cost-of-revenue)
2. [Direct Labor](#1-direct-labor)
3. [Materials](#2-materials)
4. [Subcontractors](#3-subcontractors)
5. [Equipment Costs](#4-equipment-costs)
6. [Other Direct Costs](#5-other-direct-costs)

---

## Overview: Cost of Revenue

### Definition

Costs directly attributable to construction contracts:
- Can be traced to specific jobs
- Vary with production/volume
- Included in percentage-of-completion calculation

Also called:
- Direct Costs
- Job Costs
- Cost of Construction
- Cost of Goods Sold (less common for construction)

---

### Direct vs. Indirect Costs

| Direct Costs (Cost of Revenue) | Indirect Costs (G&A) |
|--------------------------------|----------------------|
| Field labor on jobs | Office staff salaries |
| Materials installed | Office supplies |
| Subcontractors | Office rent |
| Equipment on jobs | Professional fees |
| Job-specific insurance | General insurance |
| Job trailers | Corporate overhead |

---

### Why Proper Classification Matters

1. **WIP Schedule:** Direct costs drive % complete calculation
2. **Job Costing:** Accurate job profitability analysis
3. **Bidding:** Markup applied to direct costs
4. **Bonding:** Sureties analyze cost structure
5. **Taxes:** Different treatment in some cases

---

## 1. Direct Labor

### Definition

Wages and related costs for workers directly performing construction work.

---

### Components of Direct Labor

| Component | Description |
|-----------|-------------|
| **Base Wages** | Regular hourly or salary pay |
| **Overtime Premium** | Extra pay for OT hours |
| **Burden/Fringes** | Employer taxes and benefits |
| **Union Benefits** | Per-hour union contributions |
| **Travel Pay** | Travel time to job sites |
| **Per Diem** | Daily allowances |

---

### Labor Burden (Fringes)

**Burden Rate Calculation:**

| Item | Rate | Annual Cost (Example) |
|------|------|----------------------|
| Base Wage | $25/hour | $52,000 |
| FICA (Employer) | 7.65% | $3,978 |
| FUTA | 0.6% | $42 (on first $7K) |
| SUTA | 3.0% | $210 (varies) |
| Workers' Comp | 8.0% | $4,160 |
| Health Insurance | Flat | $12,000 |
| 401(k) Match | 3.0% | $1,560 |
| **Total Burden** | | **$21,950** |
| **Burden Rate** | | **42.2%** |

**Burdened Rate:** $25 × 1.422 = $35.55/hour

---

### Labor Cost Accounting

**Costing Methods:**

| Method | Description |
|--------|-------------|
| **Actual Costing** | Actual wages + actual burden |
| **Standard Costing** | Standard rates × hours |
| **Burden Rate** | Base × burden percentage |

---

### Journal Entries

**Record Payroll (Actual):**
```
Dr. Cost of Revenue - Labor (Job 101)    15,000
Dr. Cost of Revenue - Labor (Job 102)    10,000
Dr. Cost of Revenue - Labor (Job 103)    12,000
    Cr. Cash                                    30,000
    Cr. Payroll Tax Liabilities                  3,500
    Cr. Benefits Payable                         3,500
```

**With Burden Applied:**
```
Dr. Cost of Revenue - Labor (Job 101)    15,000
Dr. Cost of Revenue - Burden (Job 101)    6,330
    Cr. Cash                                    15,000
    Cr. Payroll Tax Liabilities                  2,700
    Cr. Benefits Payable/Cash                    3,630
```

---

### Labor Reports

**Daily Time Sheet → Job Cost Report:**

| Employee | Job | Hours | Rate | Extension |
|----------|-----|-------|------|-----------|
| Smith, J | 101 | 8 | $28.00 | $224.00 |
| Smith, J | 102 | 2 | $42.00* | $84.00 |
| Jones, M | 101 | 10 | $32.00 | $320.00 |
| Jones, M | Shop | 2 | $32.00 | $64.00** |

*Overtime rate
**May charge to overhead vs. direct

---

### Balance Sheet/Income Statement Presentation

**Income Statement:**
```
COST OF REVENUE:
  Direct Labor                              $2,150,000
  Labor Burden                                 900,000
                                           ───────────
  Total Labor Cost                          $3,050,000
```

Or combined:
```
COST OF REVENUE:
  Direct Labor                              $3,050,000
```

---

## 2. Materials

### Definition

Materials and supplies purchased for and installed in construction projects.

---

### Types of Materials

| Type | Examples |
|------|----------|
| **Structural** | Concrete, steel, rebar, lumber |
| **Mechanical** | HVAC equipment, ductwork, piping |
| **Electrical** | Wire, conduit, panels, fixtures |
| **Plumbing** | Pipe, fittings, fixtures |
| **Finishes** | Drywall, flooring, paint, tile |
| **Specialty** | Windows, doors, hardware |
| **Consumables** | Fasteners, adhesives, small tools |

---

### Material Cost Components

| Component | Description |
|-----------|-------------|
| **Purchase Price** | Invoice cost |
| **Freight/Delivery** | Shipping to job |
| **Sales Tax** | If applicable |
| **Handling** | Costs to get to installation point |
| **Less: Discounts** | Early pay, volume discounts |
| **Less: Returns** | Credits for returns |

---

### Material Procurement Methods

| Method | Description | Accounting |
|--------|-------------|------------|
| **Direct Purchase** | Buy for specific job | Charge direct to job |
| **Stock Purchase** | Buy for inventory | Inventory → Job when used |
| **Owner Furnished** | Owner provides | No cost to contractor |
| **Vendor Consignment** | Pay when used | Charge when consumed |

---

### Journal Entries

**Purchase Materials for Job:**
```
Dr. Cost of Revenue - Materials (Job 101)   50,000
    Cr. Accounts Payable                          50,000
```

**Purchase Materials for Inventory:**
```
Dr. Inventory - Materials                   25,000
    Cr. Accounts Payable                          25,000
```

**Transfer from Inventory to Job:**
```
Dr. Cost of Revenue - Materials (Job 102)   10,000
    Cr. Inventory - Materials                     10,000
```

**Material Return:**
```
Dr. Accounts Payable                         5,000
    Cr. Cost of Revenue - Materials (Job 101)      5,000
```

---

### Uninstalled Materials Issue

**Scenario:** $200,000 of equipment purchased, sitting in warehouse at year-end.

**Problem:** Including in costs incurred inflates percentage complete.

**Solutions:**

1. **Exclude from % Complete Calculation:**
   - Keep in inventory
   - Transfer to job cost when installed

2. **ASC 606 Treatment:**
   - Recognize revenue equal to cost (zero margin)
   - Adjust when installed

---

### Income Statement Presentation

```
COST OF REVENUE:
  Materials                                 $3,500,000
```

Or detailed:
```
COST OF REVENUE - MATERIALS:
  Concrete                          $  750,000
  Steel and Rebar                      650,000
  Lumber                               425,000
  Electrical                           500,000
  Plumbing                             375,000
  HVAC                                 450,000
  Other Materials                      350,000
                                   ───────────
  Total Materials                   $3,500,000
```

---

## 3. Subcontractors

### Definition

Costs for work performed by subcontracted specialty contractors.

---

### Common Subcontracted Work

| Trade | Typical Scope |
|-------|---------------|
| Earthwork/Excavation | Site prep, grading, utilities |
| Concrete | Foundations, flatwork, structural |
| Structural Steel | Steel erection |
| Electrical | Power, lighting, systems |
| Plumbing | Water, waste, gas piping |
| HVAC | Heating, cooling, ventilation |
| Fire Protection | Sprinklers, alarms |
| Drywall | Framing, hanging, finishing |
| Painting | Interior/exterior painting |
| Flooring | Carpet, tile, hardwood |
| Roofing | Roof installation |
| Glass/Glazing | Windows, curtain wall |

---

### Subcontractor Payment Process

```
Subcontractor Performs Work
         ↓
Subcontractor Submits Pay Application
         ↓
GC Reviews and Approves
         ↓
GC Includes in Progress Billing to Owner
         ↓
Owner Pays GC (less retention)
         ↓
GC Pays Subcontractor (less retention)
```

---

### Retention

**Standard Terms:**
- 5-10% withheld until completion
- Released upon substantial completion
- May require lien waivers

**Example:**
- Subcontractor billing: $100,000
- Retention @ 10%: ($10,000)
- Net payment: $90,000

---

### Journal Entries

**Record Subcontractor Invoice:**
```
Dr. Cost of Revenue - Subcontract (Job 101)   100,000
    Cr. Accounts Payable - Trade                    90,000
    Cr. Accounts Payable - Retention                10,000
```

**Pay Subcontractor (Net of Retention):**
```
Dr. Accounts Payable - Trade                   90,000
    Cr. Cash                                        90,000
```

**Release Retention:**
```
Dr. Accounts Payable - Retention               10,000
    Cr. Cash                                        10,000
```

---

### Back-Charges to Subcontractors

**When sub causes damage or deficient work:**

**Journal Entry:**
```
Dr. Accounts Payable - Subcontractor        5,000
    Cr. Cost of Revenue - Subcontract              5,000
```

Or if recorded as receivable:
```
Dr. Accounts Receivable - Back-Charge       5,000
    Cr. Cost of Revenue - Subcontract              5,000
```

---

### Income Statement Presentation

```
COST OF REVENUE:
  Subcontractors                            $4,250,000
```

Or detailed:
```
COST OF REVENUE - SUBCONTRACTORS:
  Electrical                       $  850,000
  Plumbing                            650,000
  HVAC                                725,000
  Drywall                             450,000
  Earthwork                           375,000
  Other Subcontractors              1,200,000
                                  ───────────
  Total Subcontractors             $4,250,000
```

---

## 4. Equipment Costs

### Definition

Costs for equipment used on construction projects.

---

### Equipment Cost Categories

| Category | Description |
|----------|-------------|
| **Owned Equipment** | Depreciation, maintenance, fuel |
| **Rented Equipment** | External rental charges |
| **Leased Equipment** | Lease payments |
| **Small Tools** | Hand tools, power tools |

---

### Equipment Costing Methods

**Method 1: Actual Cost**
Charge actual depreciation, maintenance, fuel to jobs.

**Method 2: Internal Rental Rate**
Charge jobs an hourly/daily rate for equipment usage.

**Method 3: Equipment Division**
Separate profit center "rents" to jobs at market rates.

---

### Internal Equipment Rates

**Setting Internal Rates:**

| Cost Component | Annual Cost | Hours | Rate/Hour |
|----------------|-------------|-------|-----------|
| Depreciation | $50,000 | 2,000 | $25.00 |
| Maintenance | $15,000 | 2,000 | $7.50 |
| Fuel | $20,000 | 2,000 | $10.00 |
| Insurance | $5,000 | 2,000 | $2.50 |
| **Total** | **$90,000** | **2,000** | **$45.00** |

---

### Journal Entries

**Record Equipment Rental (External):**
```
Dr. Cost of Revenue - Equipment (Job 101)    5,000
    Cr. Accounts Payable                          5,000
```

**Record Internal Equipment Charge:**
```
Dr. Cost of Revenue - Equipment (Job 101)    2,250
    Cr. Equipment Revenue (Internal)              2,250
```

**Record Fuel for Equipment:**
```
Dr. Cost of Revenue - Equipment (Job 101)      500
    Cr. Cash / Accounts Payable                     500
```

---

### Small Tools

**Capitalization Threshold:**
- Under $500: Expense immediately
- Over $500: Capitalize or expense per policy

**Methods:**
1. Expense all small tools as purchased
2. Capitalize and depreciate over short life
3. Maintain small tool inventory

---

### Income Statement Presentation

```
COST OF REVENUE:
  Equipment Costs                           $  750,000
```

Or detailed:
```
COST OF REVENUE - EQUIPMENT:
  Equipment Rental                    $350,000
  Equipment Depreciation               200,000
  Fuel and Lubricants                  125,000
  Equipment Repairs                     50,000
  Small Tools                           25,000
                                     ─────────
  Total Equipment Costs               $750,000
```

---

## 5. Other Direct Costs

### Definition

Job-related costs not fitting into labor, materials, subcontractor, or equipment categories.

---

### Common Other Direct Costs

| Category | Examples |
|----------|----------|
| **Permits & Fees** | Building permits, inspection fees |
| **Job Insurance** | Builder's risk, wrap-up policies |
| **Bonds** | Performance and payment bond premiums |
| **Testing** | Soil, concrete, steel testing |
| **Engineering** | Job-specific engineering services |
| **Temporary Facilities** | Job trailers, temp power, fencing |
| **Safety** | Safety equipment, training |
| **Travel & Subsistence** | Out-of-town job expenses |
| **Warranty** | Warranty work costs |

---

### Permit Costs

**Building Permits:**
- Typically based on project value
- May be paid by owner or contractor
- Direct job cost

**Journal Entry:**
```
Dr. Cost of Revenue - Permits (Job 101)     15,000
    Cr. Cash                                      15,000
```

---

### Job-Specific Insurance

**Builder's Risk Insurance:**
- Covers project during construction
- May be owner or contractor provided
- Direct job cost if contractor pays

**OCIP/CCIP (Wrap-Up Programs):**
- Owner or Contractor Controlled Insurance Program
- Covers all contractors on project
- May result in insurance credits to subs

---

### Bond Costs

**Performance and Payment Bonds:**

| Bond | Purpose |
|------|---------|
| Performance Bond | Guarantees completion |
| Payment Bond | Guarantees payment to subs/suppliers |

**Typical Rate:** 1-3% of contract price

**Journal Entry:**
```
Dr. Cost of Revenue - Bonds (Job 101)       25,000
    Cr. Cash / Prepaid Bonds                      25,000
```

---

### Temporary Facilities

**Common Items:**
- Job trailer/office
- Temporary power
- Temporary water
- Temporary fencing
- Temporary toilets
- Dumpsters

**Journal Entry:**
```
Dr. Cost of Revenue - Temp Facilities (Job 101)   3,500
    Cr. Accounts Payable                               3,500
```

---

### Travel & Subsistence

**For Out-of-Town Jobs:**
- Per diem allowances
- Travel costs
- Temporary housing

**Journal Entry:**
```
Dr. Cost of Revenue - Travel (Job 101)       8,000
    Cr. Cash / Employee Advances                   8,000
```

---

### Income Statement Presentation

```
COST OF REVENUE:
  Other Direct Costs                        $  450,000
```

Or detailed:
```
COST OF REVENUE - OTHER DIRECT:
  Permits and Fees                     $75,000
  Bonds                                 85,000
  Job Insurance                         65,000
  Testing and Inspections               45,000
  Temporary Facilities                  80,000
  Travel and Subsistence                55,000
  Safety                                25,000
  Other                                 20,000
                                      ─────────
  Total Other Direct Costs            $450,000
```

---

## Complete Cost of Revenue Presentation

```
COST OF REVENUE:
  Direct Labor                          $3,050,000
  Materials                              3,500,000
  Subcontractors                         4,250,000
  Equipment Costs                          750,000
  Other Direct Costs                       450,000
                                       ───────────
    TOTAL COST OF REVENUE              $12,000,000
```

---

## Summary: Cost of Revenue Key Points

| Category | Key Considerations |
|----------|-------------------|
| Labor | Include burden; proper job allocation |
| Materials | Exclude uninstalled from % complete |
| Subcontractors | Track retention both ways |
| Equipment | Choose consistent costing method |
| Other Direct | Don't mix with G&A costs |

---

## Next Section: [C. Operating Expenses](../C-Operating-Expenses/)
