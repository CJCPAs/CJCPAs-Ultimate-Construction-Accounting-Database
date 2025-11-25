# Job Costing in Construction

## Overview

Job costing is the foundation of construction accounting. It involves tracking all costs associated with each specific construction project to determine profitability, manage budgets, and support accurate revenue recognition.

## Cost Categories

### Direct Costs

Costs that can be directly traced to a specific job.

#### Labor
| Component | Description | Tracking Method |
|-----------|-------------|-----------------|
| Field Labor | Workers directly on jobsite | Timesheets by job/cost code |
| Labor Burden | Taxes, insurance, benefits | Burden rate × hours |
| Premium Pay | Overtime, shift differential | Time records |
| Per Diem | Travel allowances | By job assignment |

**Labor Burden Rate Calculation:**
```
Annual Burden Costs:
- FICA (7.65%)                    $ 5,814
- FUTA (0.6%)                     $   456
- SUTA (varies, assume 3%)        $ 2,280
- Workers' Comp (varies, 10%)     $ 7,600
- Health Insurance                $ 8,400
- Retirement/401(k)               $ 2,280
- Other Benefits                  $ 1,520
Total Burden                      $28,350

Base Annual Wages                 $76,000
Burden Rate: $28,350 / $76,000 = 37.3%

Fully Burdened Rate: $36.54/hr × 1.373 = $50.17/hr
```

#### Materials
| Type | Description | Tracking |
|------|-------------|----------|
| Permanent Materials | Incorporated into project | Purchase orders, invoices |
| Temporary Materials | Forms, scaffolding | Allocation or direct charge |
| Small Tools | Consumables under $500 | Direct or overhead |
| Consumables | Fuel, welding rod | Direct or allocation |

#### Subcontractor Costs
| Element | Tracking | Considerations |
|---------|----------|----------------|
| Contract Amount | Subcontract agreement | Include scope clearly |
| Change Orders | Written amendments | Approve before work |
| Back Charges | Deduction documentation | Document thoroughly |
| Retainage | Percentage withheld | Track separately |

#### Equipment Costs
| Type | Cost Method | Rate Basis |
|------|-------------|------------|
| Owned Equipment | Internal rates | Hourly/daily/monthly |
| Rented Equipment | Actual rental | Invoice amount |
| Leased Equipment | Lease payments | Per lease terms |
| Operated Equipment | Operator included | Combined rate |

### Indirect Costs (Job Overhead)

Costs related to jobs but not directly traceable.

| Cost Type | Examples | Allocation Method |
|-----------|----------|-------------------|
| Supervision | Project managers, superintendents | Direct to job or allocated |
| Job Site Office | Trailer rental, utilities | Direct charge |
| Temporary Facilities | Fencing, signage | Direct charge |
| Safety Equipment | PPE, barriers | Direct or allocated |
| Quality Control | Testing, inspection | Direct or allocated |
| Project Insurance | Builder's risk | Direct or allocated |

### General & Administrative Overhead

Company-wide costs not specific to jobs.

| Category | Examples |
|----------|----------|
| Executive Salaries | CEO, CFO, administration |
| Office Rent | Main office facilities |
| Professional Fees | Accounting, legal |
| Office Supplies | General office operations |
| Insurance | General liability, E&O |
| Marketing | Advertising, proposals |

## Cost Code Structure

### Hierarchical Structure

```
Level 1: Division (CSI Format)
    Level 2: Subdivision
        Level 3: Cost Type
            Level 4: Detail (optional)

Example:
03 - Concrete
    03100 - Concrete Formwork
        03100-L - Labor
        03100-M - Materials
        03100-S - Subcontract
        03100-E - Equipment
```

### CSI MasterFormat Divisions

| Division | Description | Common Subcategories |
|----------|-------------|---------------------|
| 01 | General Requirements | Supervision, temporary facilities |
| 02 | Existing Conditions | Demolition, site clearing |
| 03 | Concrete | Formwork, reinforcement, placing |
| 04 | Masonry | Block, brick, stone |
| 05 | Metals | Structural steel, misc metals |
| 06 | Wood/Plastics | Framing, finish carpentry |
| 07 | Thermal/Moisture | Insulation, roofing, waterproofing |
| 08 | Openings | Doors, windows, hardware |
| 09 | Finishes | Drywall, paint, flooring |
| 10 | Specialties | Signage, lockers, accessories |
| 21 | Fire Suppression | Sprinklers |
| 22 | Plumbing | Piping, fixtures |
| 23 | HVAC | Heating, cooling, ventilation |
| 26 | Electrical | Power, lighting |

### Cost Type Codes

| Code | Type | Description |
|------|------|-------------|
| L or 100 | Labor | Direct field labor |
| M or 200 | Materials | Permanent materials |
| S or 300 | Subcontract | Subcontractor costs |
| E or 400 | Equipment | Owned/rented equipment |
| O or 500 | Other | Misc direct costs |

## Job Cost Accounting Entries

### Recording Labor

**Payroll Entry:**
```
Dr. Work in Process - Labor (by job/cost code)    XXX
Dr. Work in Process - Labor Burden (by job)       XXX
    Cr. Accrued Payroll                                XXX
    Cr. Payroll Tax Payable                            XXX
    Cr. Insurance Payable                              XXX
```

### Recording Materials

**Purchase on Account:**
```
Dr. Work in Process - Materials (by job)          XXX
    Cr. Accounts Payable                               XXX
```

**From Inventory:**
```
Dr. Work in Process - Materials (by job)          XXX
    Cr. Inventory - Materials                          XXX
```

### Recording Subcontractor Costs

**Upon Receipt of Invoice:**
```
Dr. Work in Process - Subcontract (by job)        XXX
    Cr. Accounts Payable - Subcontractors              XXX
    Cr. Accounts Payable - Retainage                   XXX
```

### Recording Equipment

**Internal Equipment Charges:**
```
Dr. Work in Process - Equipment (by job)          XXX
    Cr. Equipment Revenue (internal)                   XXX
```

**External Rental:**
```
Dr. Work in Process - Equipment (by job)          XXX
    Cr. Accounts Payable                               XXX
```

## Job Cost Reports

### Job Cost Detail Report

```
JOB: 2024-001 ABC Office Building
PERIOD ENDING: March 31, 2024

Cost Code        Description        Budget      Actual    Variance    % Used
─────────────────────────────────────────────────────────────────────────────
01100-L         Supervision        $120,000    $95,000   $25,000     79.2%
01100-O         General Cond.       $85,000    $72,000   $13,000     84.7%
03100-L         Concrete Labor     $180,000   $165,000   $15,000     91.7%
03100-M         Concrete Mat'l     $220,000   $235,000  ($15,000)   106.8%
03100-S         Concrete Sub       $150,000   $150,000       $0     100.0%
05100-S         Structural Steel   $890,000   $875,000   $15,000     98.3%
...
─────────────────────────────────────────────────────────────────────────────
TOTALS                           $4,500,000 $4,125,000  $375,000     91.7%
```

### Job Profitability Report

```
JOB: 2024-001 ABC Office Building

                                Original      Current       Variance
────────────────────────────────────────────────────────────────────
Contract Amount               $5,200,000    $5,350,000     $150,000
Approved Change Orders                 0       150,000      150,000
────────────────────────────────────────────────────────────────────
Total Contract               $5,200,000    $5,350,000     $150,000

Estimated Costs              $4,500,000    $4,600,000    ($100,000)
Estimated Gross Profit         $700,000      $750,000      $50,000
Estimated GP %                   13.46%        14.02%        0.56%
────────────────────────────────────────────────────────────────────
Costs to Date                            $4,125,000
Estimated Costs to Complete              $  475,000
Total Estimated Costs                    $4,600,000
────────────────────────────────────────────────────────────────────
Percent Complete (Cost Basis)                89.67%
Revenue Earned to Date                   $4,796,875
Gross Profit Earned to Date             $  671,875
```

### Cost Variance Analysis

| Variance Type | Formula | Indicates |
|---------------|---------|-----------|
| Budget Variance | Budget - Actual | Over/under budget |
| Unit Cost Variance | (Budget Unit Cost - Actual Unit Cost) × Actual Qty | Pricing efficiency |
| Quantity Variance | (Budget Qty - Actual Qty) × Budget Unit Cost | Usage efficiency |
| Productivity Variance | (Budget Hours - Actual Hours) × Budget Rate | Labor efficiency |

## Overhead Allocation Methods

### Direct Labor Hours
```
Overhead Rate = Total Overhead / Total Direct Labor Hours
Job Overhead = Job Direct Labor Hours × Overhead Rate
```

### Direct Labor Dollars
```
Overhead Rate = Total Overhead / Total Direct Labor Cost
Job Overhead = Job Direct Labor Cost × Overhead Rate
```

### Direct Costs
```
Overhead Rate = Total Overhead / Total Direct Costs
Job Overhead = Job Direct Costs × Overhead Rate
```

### Contract Revenue
```
Overhead Rate = Total Overhead / Total Contract Revenue
Job Overhead = Job Contract Revenue × Overhead Rate
```

## Equipment Cost Accounting

### Internal Equipment Rates

**Components of Internal Rate:**
| Component | Calculation |
|-----------|-------------|
| Depreciation | Cost / Useful Life Hours |
| Interest | Average Investment × Rate / Annual Hours |
| Insurance | Annual Premium / Annual Hours |
| Taxes | Annual Property Tax / Annual Hours |
| Repairs | Historical Average / Annual Hours |
| Fuel | Consumption Rate × Fuel Cost |
| Operator | Hourly Wage + Burden (if included) |

**Example Rate Calculation:**
```
Equipment: CAT 320 Excavator
Purchase Price: $350,000
Useful Life: 10,000 hours
Annual Hours: 1,500

Ownership Costs (per hour):
  Depreciation: $350,000 / 10,000 = $35.00
  Interest: ($350,000 × 0.5 × 6%) / 1,500 = $7.00
  Insurance: $4,200 / 1,500 = $2.80
  Taxes: $2,100 / 1,500 = $1.40
  Total Ownership: $46.20/hr

Operating Costs (per hour):
  Repairs: $15.00 (historical average)
  Fuel: 6 gal/hr × $4.00 = $24.00
  Total Operating: $39.00/hr

Total Rate: $85.20/hr (bare)
With Operator: $85.20 + $55.00 = $140.20/hr
```

### Equipment Accounting Entries

**Job Charges:**
```
Dr. Work in Process - Equipment (Job)             XXX
    Cr. Equipment Income - Internal                    XXX
```

**Actual Equipment Costs:**
```
Dr. Equipment Expense - Depreciation              XXX
Dr. Equipment Expense - Repairs                   XXX
Dr. Equipment Expense - Fuel                      XXX
    Cr. Accumulated Depreciation                       XXX
    Cr. Cash/Accounts Payable                          XXX
    Cr. Inventory - Fuel                               XXX
```

**Equipment Profit/Loss:**
```
Equipment Income - Internal                      $XXX
Less: Equipment Expenses                         (XXX)
─────────────────────────────────────────────────────
Equipment Department Profit/(Loss)               $XXX
```

## Best Practices

### Daily Cost Tracking
1. Record all labor daily via timesheets
2. Code all invoices promptly
3. Review cost reports weekly
4. Address variances immediately

### Cost Code Discipline
1. Use consistent coding structure
2. Train all personnel on coding
3. Review coded transactions
4. Maintain cost code dictionary

### Documentation
1. Retain all supporting documents
2. Document allocation methods
3. Keep contemporaneous records
4. Support all estimates

### Reconciliation
1. Reconcile payroll to job costs
2. Reconcile A/P to job costs
3. Verify equipment charges
4. Review subcontractor billings

---

*Previous: [Revenue Recognition](02-revenue-recognition.md)*  
*Next: [WIP Schedules](04-wip-schedules.md)*
