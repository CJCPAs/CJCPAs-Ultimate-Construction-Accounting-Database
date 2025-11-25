# Equipment Accounting in Construction

## Overview

Construction companies make significant investments in equipment. Proper accounting for equipment affects profitability, tax liability, and financial statement presentation. This includes owned equipment, leased equipment, and rental equipment.

## Equipment Categories

### Owned Equipment

| Category | Examples | Typical Life |
|----------|----------|--------------|
| Heavy Equipment | Excavators, dozers, cranes | 10,000-20,000 hours |
| Support Equipment | Generators, compressors | 5,000-10,000 hours |
| Vehicles | Trucks, pickups | 5-7 years |
| Small Equipment | Power tools, pumps | 3-5 years |

### Leased Equipment

| Lease Type | Characteristics | Accounting Treatment |
|------------|-----------------|---------------------|
| Finance Lease | Ownership transfers, bargain purchase, or term > 75% of life | Capitalize as asset |
| Operating Lease | Short-term, cancelable | Expense over lease term |

### Rented Equipment

Short-term rental from third parties, expensed as incurred.

## Capitalization

### Capitalization Criteria

Assets should be capitalized when:
1. Useful life exceeds one year
2. Cost exceeds capitalization threshold (typically $2,500-$5,000)
3. Asset is used in operations

### Capitalized Costs

| Cost Component | Include? | Notes |
|----------------|----------|-------|
| Purchase price | Yes | Net of discounts |
| Sales tax | Yes | Capitalized |
| Freight/delivery | Yes | To put in use |
| Installation | Yes | To put in use |
| Initial repairs | Yes | If necessary for use |
| Training | No | Expense as incurred |
| Maintenance agreements | No | Expense over term |
| Financing costs | Generally No | Except during construction |

### Journal Entry for Acquisition

```
Purchase of excavator:
Equipment cost:        $350,000
Sales tax:              $28,000
Delivery:                $2,000
Total capitalized:     $380,000

Dr. Equipment - Heavy              $380,000
    Cr. Cash / Notes Payable               $380,000
```

## Depreciation Methods

### Straight-Line (Book)

```
Annual Depreciation = (Cost - Salvage Value) / Useful Life

Example:
Cost: $380,000
Salvage: $30,000
Life: 10 years
Annual Depreciation: ($380,000 - $30,000) / 10 = $35,000/year
```

### Units of Production (Operating Hours)

```
Depreciation per Hour = (Cost - Salvage Value) / Total Estimated Hours

Example:
Cost: $380,000
Salvage: $30,000
Estimated Hours: 10,000
Rate: ($380,000 - $30,000) / 10,000 = $35/hour

If 1,200 hours used this year: 1,200 × $35 = $42,000 depreciation
```

### MACRS (Tax)

| Asset Class | Recovery Period | Method |
|-------------|-----------------|--------|
| Vehicles | 5 years | 200% DB |
| Heavy equipment | 7 years | 200% DB |
| Land improvements | 15 years | 150% DB |
| Buildings | 39 years | Straight-line |

### Depreciation Entry

```
Dr. Depreciation Expense - Equipment     $35,000
    Cr. Accumulated Depreciation - Equipment     $35,000
```

## Internal Equipment Rates

### Purpose

Internal rates allow:
1. Charging jobs for equipment use
2. Tracking equipment profitability
3. Supporting bid estimates
4. Comparing owned vs. rented costs

### Rate Components

#### Ownership Costs

| Component | Calculation |
|-----------|-------------|
| Depreciation | (Cost - Salvage) / Life Hours |
| Interest | (Average Investment × Rate) / Annual Hours |
| Insurance | Annual Premium / Annual Hours |
| Property Tax | Annual Tax / Annual Hours |

#### Operating Costs

| Component | Calculation |
|-----------|-------------|
| Fuel | Consumption Rate × Price per Gallon |
| Maintenance | Historical Cost / Hours |
| Repairs | Historical Cost / Hours |
| Tires/Tracks | Replacement Cost / Life Hours |

### Sample Rate Calculation

```
EQUIPMENT RATE CALCULATION
Equipment: CAT 320 Excavator
Purchase Price: $380,000
Salvage Value: $30,000
Estimated Life: 10,000 hours
Annual Usage: 1,500 hours

OWNERSHIP COSTS (per hour):
Depreciation: ($380,000 - $30,000) / 10,000    = $35.00
Interest: ($380,000 × 0.5 × 6%) / 1,500        = $ 7.60
Insurance: $5,700 / 1,500                       = $ 3.80
Property Tax: $2,850 / 1,500                    = $ 1.90
─────────────────────────────────────────────────────────
Total Ownership                                 = $48.30/hr

OPERATING COSTS (per hour):
Fuel: 6 gallons × $4.00                        = $24.00
Maintenance/Repairs: historical average         = $12.00
Tires/Tracks: $15,000 / 3,000 hours            = $ 5.00
─────────────────────────────────────────────────────────
Total Operating                                 = $41.00/hr

TOTAL HOURLY RATE (bare)                        = $89.30/hr
With Operator ($55/hr fully loaded)             = $144.30/hr
```

## Equipment Accounting Entries

### Charging Jobs

**Monthly equipment charges to jobs:**
```
Dr. Work in Process - Equipment (Job 2024-001)   $15,000
Dr. Work in Process - Equipment (Job 2024-002)    $8,500
Dr. Work in Process - Equipment (Job 2024-003)   $12,000
    Cr. Equipment Revenue - Internal                     $35,500
```

### Recording Actual Costs

**Depreciation:**
```
Dr. Equipment Expense - Depreciation            $35,000
    Cr. Accumulated Depreciation - Equipment            $35,000
```

**Fuel:**
```
Dr. Equipment Expense - Fuel                    $18,000
    Cr. Cash / Accounts Payable                         $18,000
```

**Repairs:**
```
Dr. Equipment Expense - Repairs                 $12,500
    Cr. Cash / Accounts Payable                         $12,500
```

### Equipment Department P&L

```
EQUIPMENT DEPARTMENT INCOME STATEMENT
For the Year Ended December 31, 2024

Equipment Revenue - Internal Charges                 $425,000

Equipment Expenses:
  Depreciation                         $245,000
  Interest                              $32,000
  Insurance                             $18,500
  Fuel                                 $112,000
  Repairs & Maintenance                 $45,000
  Other                                 $12,500
Total Equipment Expenses                             $465,000
─────────────────────────────────────────────────────────────
Equipment Department (Loss)                          ($40,000)
```

## Lease Accounting (ASC 842)

### Classification Test

A lease is a finance lease if ANY criteria met:
1. Ownership transfers at end of lease
2. Bargain purchase option exists
3. Lease term ≥ 75% of economic life
4. Present value of payments ≥ 90% of fair value
5. Asset is specialized with no alternative use

### Finance Lease Accounting

**Initial Recognition:**
```
Present Value of Lease Payments: $280,000
(Using incremental borrowing rate)

Dr. Right-of-Use Asset                  $280,000
    Cr. Lease Liability                         $280,000
```

**Monthly Payment:**
```
Monthly Payment: $8,500
Interest Portion: $1,400
Principal Portion: $7,100

Dr. Interest Expense                     $1,400
Dr. Lease Liability                      $7,100
    Cr. Cash                                     $8,500
```

**Depreciation:**
```
Dr. Depreciation Expense - ROU Asset     $7,000
    Cr. Accumulated Depreciation - ROU Asset     $7,000
```

### Operating Lease Accounting

**Initial Recognition:**
```
Present Value of Lease Payments: $85,000

Dr. Right-of-Use Asset                   $85,000
    Cr. Lease Liability                          $85,000
```

**Monthly Recognition:**
```
Dr. Lease Expense (straight-line)        $2,833
    Cr. Lease Liability (actual payment diff)      $XXX
    Cr. Right-of-Use Asset (amortization)          $XXX
```

## Equipment Records and Tracking

### Equipment Master File

| Field | Description |
|-------|-------------|
| Equipment ID | Unique identifier |
| Description | Make, model, serial number |
| Category | Heavy, support, vehicle |
| Acquisition Date | Date placed in service |
| Original Cost | Capitalized amount |
| Salvage Value | Estimated residual |
| Depreciation Method | Straight-line, hours |
| Location | Current job assignment |
| Status | Active, idle, disposed |

### Hour Tracking

| Method | Description |
|--------|-------------|
| Hour Meters | Physical meter readings |
| GPS Tracking | Automated hour capture |
| Timecards | Operator-reported hours |
| Fuel Records | Hours estimated from fuel use |

### Maintenance Records

| Record Type | Purpose |
|-------------|---------|
| Service History | Track maintenance performed |
| Repair Log | Document repairs and costs |
| Parts Inventory | Track parts used |
| Warranty Claims | Document warranty repairs |

## Equipment Disposal

### Sale of Equipment

```
Equipment Original Cost: $380,000
Accumulated Depreciation: $245,000
Book Value: $135,000
Sale Price: $120,000
Loss on Sale: $15,000

Dr. Cash                                $120,000
Dr. Accumulated Depreciation            $245,000
Dr. Loss on Sale of Equipment            $15,000
    Cr. Equipment - Heavy                       $380,000
```

### Trade-In

```
Old Equipment Book Value: $135,000
Trade-In Allowance: $150,000
New Equipment Price: $420,000
Cash Paid: $270,000

Dr. Equipment - Heavy (new)             $420,000
Dr. Accumulated Depreciation (old)      $245,000
    Cr. Equipment - Heavy (old)                 $380,000
    Cr. Gain on Trade-In                         $15,000
    Cr. Cash                                    $270,000
```

### Abandonment/Scrap

```
Equipment Original Cost: $25,000
Accumulated Depreciation: $25,000
Book Value: $0
Scrap Recovery: $500

Dr. Cash                                   $500
Dr. Accumulated Depreciation             $25,000
    Cr. Equipment - Small                        $25,000
    Cr. Gain on Disposal                            $500
```

## Tax Considerations

### Section 179 Expensing

| Year | Maximum Deduction | Phase-Out Threshold |
|------|-------------------|---------------------|
| 2024 | $1,160,000 | $2,890,000 |

Allows immediate expensing of qualifying equipment purchases.

### Bonus Depreciation

| Placed in Service | Percentage |
|-------------------|------------|
| 2023 | 80% |
| 2024 | 60% |
| 2025 | 40% |
| 2026 | 20% |

Additional first-year depreciation on qualified property.

### De Minimis Safe Harbor

May expense items under $2,500 (with policy) or $5,000 (with audited financials).

---

*Previous: [Billing Methods](05-billing-methods.md)*  
*Next: [Joint Ventures](07-joint-ventures.md)*
