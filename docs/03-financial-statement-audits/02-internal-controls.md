# Internal Controls for Construction Companies

## Overview

Internal controls are essential in construction companies due to decentralized operations, multiple job sites, and significant estimates. Understanding and testing controls is crucial for both financial reporting and operational efficiency.

## Control Environment

### Tone at the Top

| Element | Best Practices |
|---------|---------------|
| Integrity | Code of conduct, ethics policy |
| Competence | Training programs, credentials |
| Board Oversight | Active audit committee |
| Structure | Clear reporting lines |
| Authority | Defined approval limits |
| Accountability | Performance evaluations |

### Organizational Structure

```
TYPICAL CONSTRUCTION COMPANY STRUCTURE

CEO/President
├── CFO/Controller
│   ├── Accounting Manager
│   │   ├── Job Cost Accountant
│   │   ├── A/P Clerk
│   │   └── Payroll Clerk
│   └── Finance Manager
├── VP Operations
│   ├── Project Managers
│   │   └── Superintendents
│   │       └── Foremen
│   └── Safety Director
├── VP Business Development
│   └── Estimators
└── VP Human Resources
```

## Key Control Activities

### Revenue/Billing Cycle

| Control | Purpose | Test Procedure |
|---------|---------|----------------|
| PM approval of billings | Accuracy | Review approval signatures |
| Schedule of values reconciliation | Completeness | Test reconciliation |
| Change order approval matrix | Authorization | Review authority limits |
| Monthly WIP review | Accuracy of estimates | Review meeting minutes |
| Retainage tracking | Accuracy | Reconcile to contracts |

**Detailed Controls:**

1. **Billing Preparation**
   - Job cost accountant prepares draft billing
   - Project manager reviews against schedule of values
   - Operations approves work completion percentage
   - CFO reviews significant billings

2. **Revenue Recognition**
   - Monthly WIP schedule prepared by accounting
   - Project managers review and sign off
   - CFO reviews estimate changes
   - Controller approves final WIP

3. **Change Order Processing**
   - Project manager prepares change order request
   - Estimator prices the work
   - Operations VP approves (based on limits)
   - Owner approval required before recognition

### Cost Cycle

| Control | Purpose | Test Procedure |
|---------|---------|----------------|
| Purchase order requirements | Authorization | Test PO matching |
| Three-way match | Accuracy/Authorization | Test matching process |
| Job coding review | Accuracy | Review coded invoices |
| Timekeeping approval | Authorization | Test supervisor approvals |
| Subcontract approval | Authorization | Review approval limits |

**Detailed Controls:**

1. **Purchasing**
   - Purchase requisition by foreman
   - PO issued by purchasing (over threshold)
   - Delivery received and verified
   - Three-way match (PO, receipt, invoice)

2. **Subcontractor Invoice Processing**
   - Sub submits pay application
   - PM verifies work completion
   - Conditional lien waiver obtained
   - Accounting processes payment

3. **Payroll**
   - Daily time sheets by employee
   - Foreman approval
   - PM review of labor distribution
   - Payroll processes approved time

### Equipment Cycle

| Control | Purpose | Test Procedure |
|---------|---------|----------------|
| Capitalization policy | Proper classification | Test policy application |
| Internal rate review | Accurate job costing | Review rate calculations |
| Hour tracking verification | Accuracy | Test to source documents |
| Disposal authorization | Authorization | Review approval |

### Estimating Controls

| Control | Purpose | Test Procedure |
|---------|---------|----------------|
| Independent estimate review | Accuracy | Review sign-offs |
| Historical comparison | Reasonableness | Test comparisons |
| Executive bid review | Authorization | Review meeting minutes |
| Post-job analysis | Continuous improvement | Review fade analyses |

## IT General Controls

### Key IT Controls

| Area | Controls |
|------|----------|
| Access | User provisioning, password policies |
| Changes | Change management procedures |
| Operations | Backup, recovery, monitoring |
| Physical | Data center security |

### Construction Software Controls

```
JOB COST SYSTEM CONTROLS

Access Controls:
- Role-based access
- Job-level security
- Cost code restrictions
- Approval workflow

Processing Controls:
- Automatic cost coding
- Budget variance alerts
- Three-way matching
- Duplicate invoice detection

Output Controls:
- Report distribution controls
- WIP schedule approval workflow
- Management report package
```

## Testing Internal Controls

### Control Testing Approach

**Sample Size Determination:**

| Control Frequency | Sample Size (25 Reliance) | Sample Size (60 Reliance) |
|-------------------|---------------------------|---------------------------|
| Annual | 1 | 1 |
| Quarterly | 2 | 2 |
| Monthly | 2-5 | 5-9 |
| Weekly | 5-15 | 15-25 |
| Daily | 20-25 | 40-60 |

### Revenue Recognition Control Tests

**Test of WIP Review Control:**
```
CONTROL: Monthly WIP schedule reviewed and approved by CFO

Objective: Test operating effectiveness

Procedure:
1. Obtain WIP schedules for each month
2. Verify CFO signature/approval
3. Verify date of approval (timely)
4. Review evidence of review (changes, questions)
5. Test selected estimate changes for support

Sample: All 12 months (monthly control)

Results:
Month     Approved    Timely    Evidence
Jan       Yes         Yes       Notes
Feb       Yes         Yes       Questions
Mar       Yes         Yes       Estimate change
...

Conclusion: Control operating effectively
```

**Test of Change Order Approval:**
```
CONTROL: Change orders approved per authority matrix

Objective: Test operating effectiveness

Procedure:
1. Obtain change order log
2. Select sample of change orders
3. Verify approval per authority limits
4. Test owner approval on file
5. Verify proper accounting treatment

Sample: 25 change orders from population of 150

Results:
CO#      Amount      Approver     Proper     Owner
                     Level        Auth       Approval
CO-001   $15,000     PM           Yes        Yes
CO-002   $85,000     VP Ops       Yes        Yes
CO-003   $150,000    CEO          Yes        Yes
...

Conclusion: Control operating effectively
```

### Cost Control Tests

**Test of Three-Way Match:**
```
CONTROL: Three-way match required for vendor payments

Objective: Test operating effectiveness

Procedure:
1. Select sample of vendor payments
2. Verify purchase order on file
3. Verify receiving document
4. Verify invoice matches PO and receipt
5. Verify proper job coding

Sample: 40 payments from population of 3,000

Results:
Vendor        Amount      PO      Rcpt    Match   Coded
ABC Supply    $5,250      Yes     Yes     Yes     Yes
XYZ Parts     $12,800     Yes     Yes     Yes     Yes
...

Exception: 1 item missing receiving document

Conclusion: Control operating effectively with minor exception
```

## Control Deficiencies

### Classification

| Type | Definition | Example |
|------|------------|---------|
| Deficiency | Control doesn't prevent/detect misstatement | Missing approval signature |
| Significant Deficiency | Less severe than material weakness | No segregation of duties |
| Material Weakness | Reasonable possibility of material misstatement | No WIP review process |

### Common Deficiencies in Construction

1. **Lack of Segregation of Duties**
   - Same person prepares and approves payments
   - Project manager controls all job costs

2. **Inadequate WIP Review**
   - Estimates not reviewed by management
   - No documentation of review

3. **Weak Change Order Controls**
   - Revenue recognized on unapproved changes
   - No tracking of pending changes

4. **Poor Job Cost Controls**
   - Costs not coded timely
   - No verification of coding accuracy

5. **IT Control Weaknesses**
   - Shared passwords
   - No access reviews
   - Lack of audit trails

### Documentation of Deficiencies

```
CONTROL DEFICIENCY EVALUATION

Deficiency: Subcontractor invoices paid without PM approval

Compensating Controls:
- CFO reviews all payments over $25,000
- Monthly subcontractor cost review by operations

Likelihood of Misstatement:
- Possible - payments could be made for work not performed

Magnitude of Potential Misstatement:
- Material - subcontractor costs are 60% of revenue

Conclusion: Significant Deficiency

Recommendation:
- Implement mandatory PM approval for all sub invoices
- Add approval workflow in accounting system
```

## Communication Requirements

### To Management

| Item | When | How |
|------|------|-----|
| All deficiencies | During/after audit | Written letter |
| Fraud indicators | Immediately | In person, then written |
| Recommendations | With deficiency letter | Written |

### To Those Charged with Governance

| Item | Required Communication |
|------|----------------------|
| Significant deficiencies | Yes - in writing |
| Material weaknesses | Yes - in writing |
| Other deficiencies | Optional |
| Management letter | Common practice |

### Sample Management Letter Comment

```
INTERNAL CONTROL OBSERVATION

Observation:
We noted that the Company does not have a formal process for
reviewing and approving the Work-in-Progress (WIP) schedule.
The WIP schedule is prepared by the job cost accountant and
used without independent review by management.

Risk:
The WIP schedule is the primary basis for revenue recognition.
Without management review, errors in estimates could result in
material misstatement of contract revenue and gross profit.

Recommendation:
We recommend implementing a monthly WIP review process that includes:
1. Project manager certification of estimates to complete
2. CFO review of significant changes in estimates
3. Documentation of review through sign-off procedures

Management Response:
Management agrees with the recommendation and will implement a
formal WIP review process beginning January 1, 2025.
```

---

*Previous: [Audit Planning](01-audit-planning.md)*  
*Next: [Substantive Procedures](03-substantive-procedures.md)*
