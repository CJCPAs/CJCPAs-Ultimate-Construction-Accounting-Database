# Cost Testing in Construction Audits

## Overview

Cost testing validates job costs and estimates, which directly impact revenue recognition and profitability reporting. This chapter covers procedures for testing various cost categories in construction.

## Cost Categories

### Direct Costs

| Category | Testing Focus |
|----------|---------------|
| Labor | Existence, accuracy, proper coding |
| Materials | Occurrence, accuracy, proper coding |
| Subcontractors | Occurrence, accuracy, completeness |
| Equipment | Occurrence, rates, proper coding |
| Other Direct | Occurrence, proper classification |

### Indirect Costs

| Category | Testing Focus |
|----------|---------------|
| Supervision | Allocation basis, reasonableness |
| Job Site Overhead | Proper job assignment |
| Equipment Overhead | Rate development |
| Insurance | Allocation method |

## Labor Cost Testing

### Payroll Testing

```
PAYROLL/LABOR COST TESTING

Objective: Test labor costs charged to jobs

Selection:
- Select pay periods across the year
- Include period-end cutoff
- Cover various job assignments

Sample: 4 pay periods, 60 employees per period

Test Procedures:
1. Obtain timesheet for selected employees
2. Verify supervisor approval
3. Agree hours to job cost system
4. Verify job coding
5. Recalculate gross pay
6. Trace to payroll register

Sample Results:
Period    Employee     Hours   Job Code   Rate    Amount   Result
─────────────────────────────────────────────────────────────────────
03/15/24  J. Smith     45      2024-001   $28.50  $1,282   ✓
03/15/24  M. Johnson   52      2024-002   $32.00  $1,808   ✓
06/28/24  R. Williams  40      2024-001   $30.00  $1,200   ✓
[Additional samples...]

Exceptions:
- 1 instance of unsigned timesheet (immaterial)
- Hours and rates properly calculated

Conclusion: Labor costs properly recorded and coded
```

### Labor Burden Testing

```
LABOR BURDEN RATE TESTING

Objective: Verify accuracy of burden rate

Burden Rate Calculation:
Component                    Amount      % of Wages
─────────────────────────────────────────────────────
FICA (Employer)              7.65%       7.65%
FUTA                         0.60%       0.60%
SUTA                         3.20%       3.20%
Workers' Compensation       12.50%      12.50%
Health Insurance           $850/mo      11.18%
401(k) Match                3.00%       3.00%
Other Benefits              2.50%       2.50%
─────────────────────────────────────────────────────
Total Burden Rate                       40.63%

Verification:
- Agreed FICA/FUTA rates to federal requirements
- Confirmed SUTA rate with state filing
- Verified workers' comp rate to policy
- Agreed health insurance to plan documents
- Confirmed 401(k) match to plan
- Rate appears reasonable for industry

Conclusion: Burden rate properly calculated
```

## Material Cost Testing

### Purchase Testing

```
MATERIAL COST TESTING

Objective: Test material costs charged to jobs

Selection Criteria:
- Large purchases (>$10,000)
- Period-end transactions
- Random sample of smaller items

Sample: 45 material purchases

Test Procedures:
1. Obtain purchase order (if required)
2. Review vendor invoice
3. Verify receiving documentation
4. Confirm proper job coding
5. Verify pricing reasonableness

Sample Results:
Vendor        Description     Amount    PO?   Receipt  Coded  Result
────────────────────────────────────────────────────────────────────────
ABC Lumber    2×4 framing     $12,500   Yes   Yes      Yes    ✓
XYZ Concrete  Ready-mix       $28,400   Yes   Yes      Yes    ✓
Steel Supply  Rebar           $45,000   Yes   Yes      Yes    ✓
HD Supply     Hardware        $2,150    N/A   Yes      Yes    ✓
[Additional samples...]

Exceptions:
- 2 items missing PO (under threshold - compliant)

Conclusion: Material costs properly recorded and coded
```

### Inventory Testing

```
INVENTORY TESTING (if material)

Year-End Inventory: $175,000

Components:
Category              Amount      Location
───────────────────────────────────────────
Lumber               $45,000     Yard
Concrete supplies    $25,000     Yard
Electrical          $35,000     Warehouse
Plumbing            $28,000     Warehouse
Hardware            $42,000     Warehouse
Total              $175,000

Test Procedures:
1. Observe physical inventory
2. Test counts to records
3. Review pricing
4. Assess obsolescence

Physical Count Results:
- Attended count on 12/31/24
- Test counted 35 items
- All counts agreed to records
- No obsolete items identified

Conclusion: Inventory properly stated
```

## Subcontractor Cost Testing

### Subcontract Testing

```
SUBCONTRACTOR COST TESTING

Objective: Test subcontractor costs charged to jobs

Population: 125 subcontractor invoices
Sample: 35 invoices

Selection Criteria:
- All invoices >$50,000
- Final payments to subs
- Random sample of remainder

Test Procedures:
1. Obtain subcontract agreement
2. Review pay application
3. Verify work completion (PM approval)
4. Confirm lien waiver obtained
5. Verify proper job coding
6. Trace to accounts payable

Sample Results:
Subcontractor   Job       Amount     Contract  PM App   Lien    Result
─────────────────────────────────────────────────────────────────────────
ABC Electric    2024-001  $85,000    Yes       Yes      Yes     ✓
XYZ Plumbing    2024-001  $62,500    Yes       Yes      Yes     ✓
DEF Mechanical  2024-002  $125,000   Yes       Yes      Yes     ✓
GHI Drywall     2024-003  $48,000    Yes       Yes      Yes     ✓
[Additional samples...]

Exceptions: None

Conclusion: Subcontractor costs properly recorded
```

### Retainage Testing

```
SUBCONTRACTOR RETAINAGE TESTING

Objective: Verify retainage payable properly recorded

Retainage Payable Balance: $425,000

Test Procedures:
1. Obtain retainage detail by subcontractor
2. Select sample of subcontractors
3. Recalculate retainage per contracts
4. Verify retainage percentage
5. Confirm not released prematurely

Sample Results:
Subcontractor   Contract    Billed     Ret %   Retainage   Per Audit
─────────────────────────────────────────────────────────────────────────
ABC Electric    $535,000    $425,000   10%     $42,500     $42,500 ✓
XYZ Plumbing    $335,000    $268,000   10%     $26,800     $26,800 ✓
DEF Mechanical  $450,000    $405,000   10%     $40,500     $40,500 ✓
[Additional samples...]

Conclusion: Retainage payable properly recorded
```

## Equipment Cost Testing

### Internal Equipment Charges

```
EQUIPMENT COST TESTING

Objective: Test internal equipment charges to jobs

Test Procedures:
1. Obtain equipment hour log
2. Verify hours charged to job
3. Test internal rate calculation
4. Compare to external rental rates

Equipment Hour Testing:
Equipment     Job       Hours   Rate      Total      Verified
─────────────────────────────────────────────────────────────────
CAT 320       2024-001  240     $89.30    $21,432    ✓
Crane         2024-003  160     $350.00   $56,000    ✓
Loader        2024-002  80      $65.00    $5,200     ✓
[Additional items...]

Rate Comparison:
Equipment     Internal Rate   External Rate   Reasonable?
──────────────────────────────────────────────────────────
CAT 320       $89.30          $125.00         Yes
Crane         $350.00         $500.00         Yes
Loader        $65.00          $85.00          Yes

Conclusion: Equipment charges properly recorded
```

### Equipment Depreciation

```
EQUIPMENT DEPRECIATION TESTING

Objective: Verify depreciation expense accuracy

Depreciation per Books: $245,000

Test Procedures:
1. Obtain depreciation schedule
2. Verify useful lives per policy
3. Recalculate depreciation
4. Test additions and disposals

Depreciation Recalculation:
Asset             Cost       Salvage    Life   Annual Depr   Per Books
─────────────────────────────────────────────────────────────────────────
CAT 320          $380,000   $30,000    10 yr   $35,000       $35,000 ✓
Crane            $450,000   $50,000    15 yr   $26,667       $26,667 ✓
Loader           $185,000   $25,000    7 yr    $22,857       $22,857 ✓
[Additional items...]

Total per Audit: $245,000
Total per Books: $245,000
Difference: $0

Conclusion: Depreciation properly calculated
```

## Overhead Allocation Testing

### Allocation Method Review

```
OVERHEAD ALLOCATION TESTING

Objective: Test overhead allocation to jobs

Allocation Method: Direct labor dollars

Overhead Costs Allocated: $1,250,000
Direct Labor Base: $8,500,000
Overhead Rate: 14.7%

Test Procedures:
1. Verify overhead costs qualify for allocation
2. Test allocation base calculation
3. Recalculate overhead rate
4. Test allocation to sample jobs

Overhead Cost Review:
Category                Amount      Allocable?
────────────────────────────────────────────────
Supervision            $450,000     Yes
Job site office        $125,000     Yes
Small tools            $85,000      Yes
Vehicle costs          $190,000     Yes
Insurance allocation   $400,000     Yes
Total                $1,250,000

Job Allocation Test:
Job         Direct Labor   Rate    Overhead     Per Books   Diff
────────────────────────────────────────────────────────────────────
2024-001    $1,425,000     14.7%   $209,475     $209,500    $25
2024-002    $892,000       14.7%   $131,124     $131,100    $24
2024-003    $2,150,000     14.7%   $316,050     $316,000    $50
[Additional jobs...]

Conclusion: Overhead properly allocated
```

## Cost Cutoff Testing

### Year-End Procedures

```
COST CUTOFF TESTING

Objective: Verify costs recorded in proper period

Test 1: Last Invoices Entered in December
Invoice      Vendor          Date Rcvd   Service Date   Amount    Proper?
─────────────────────────────────────────────────────────────────────────
INV-4521    ABC Supply      12/28/24    12/20/24       $15,000   Yes
INV-4522    XYZ Concrete    12/29/24    12/27/24       $28,000   Yes
INV-4523    DEF Electric    12/30/24    12/15/24       $45,000   Yes
INV-4524    Material Co     12/31/24    12/28/24       $8,500    Yes

Test 2: First Invoices Entered in January
Invoice      Vendor          Date Rcvd   Service Date   Amount    Accrued?
─────────────────────────────────────────────────────────────────────────
INV-4601    ABC Supply      01/03/25    12/28/24       $22,000   Yes
INV-4602    XYZ Rental      01/05/25    12/31/24       $12,500   Yes
INV-4603    Labor Temp      01/08/25    01/05/25       $8,000    N/A

Test 3: Payroll Cutoff
- Last payroll 12/27/24 (through 12/22/24)
- Accrual for 12/23-12/31: $185,000
- Verified calculation: Days × average daily labor

Conclusion: Cost cutoff properly applied
```

## Estimate to Complete Testing

### Overall Estimate Review

```
ESTIMATE TO COMPLETE SUMMARY

Objective: Evaluate reasonableness of estimates

Overall Analysis:
Total Estimated Costs to Complete: $11,030,000
Total Remaining Budget: $12,450,000
Ratio: 88.6%

By Job Analysis:
Job         Est to Complete   Budget Remain   Ratio   Status
────────────────────────────────────────────────────────────────
2024-001    $475,000          $550,000        86%     Favorable
2024-002    $825,000          $900,000        92%     On target
2024-003    $2,220,000        $2,450,000      91%     On target
2024-004    $370,000          $400,000        93%     On target
2024-005    $7,140,000        $8,150,000      88%     Favorable
─────────────────────────────────────────────────────────────────
Total       $11,030,000       $12,450,000     88.6%

Jobs Requiring Additional Review:
- None - all estimates appear conservative to budget

Conclusion: Estimates to complete appear reasonable
```

### Subsequent Events Review

```
SUBSEQUENT EVENTS - COST REVIEW

Objective: Corroborate estimates with subsequent activity

Review Period: January 1-31, 2025

Costs Incurred in January by Job:
Job         Estimate       Jan Costs   Pace     Issues?
────────────────────────────────────────────────────────────
2024-001    $475,000       $85,000     Normal   No
2024-002    $825,000       $180,000    Normal   No
2024-003    $2,220,000     $420,000    Normal   No
2024-004    $370,000       $125,000    Normal   No
2024-005    $7,140,000     $650,000    Normal   No

Significant Developments:
- No cost overruns identified
- No change orders requiring loss recognition
- No significant claims or disputes arose

Conclusion: Subsequent activity supports year-end estimates
```

## Cost Testing Summary

```
COST TESTING SUMMARY

Areas Tested:
□ Labor costs - Properly recorded and coded
□ Labor burden - Rate properly calculated
□ Material costs - Properly recorded and coded
□ Subcontractor costs - Properly recorded
□ Subcontractor retainage - Properly stated
□ Equipment costs - Properly charged
□ Depreciation - Properly calculated
□ Overhead allocation - Properly applied
□ Cost cutoff - Proper period
□ Estimates to complete - Appear reasonable

Exceptions Identified:
- 1 unsigned timesheet (immaterial)

Adjustments Proposed: None

Conclusion:
Job costs are properly recorded, coded, and stated in
accordance with GAAP. Estimates to complete appear
reasonable and are supported by subsequent events.
```

---

*Previous: [Revenue Testing](04-revenue-testing.md)*  
*Next: [WIP Audit Procedures](06-wip-audit-procedures.md)*
