# **GUIDE FOR BASIC ACCOUNTING AND REPORTING**

**Updates to Federal Employees' Compensation Act (Workers' Compensation) Effective Date: Fiscal year 2013**

Note: The update to FECA implementation guidance was prepared in GTAS implementation test environment. GTAS implementation date is effective for fiscal 2014. If you have 2013 reporting questions related to this guidance, please contact USSGL Advisory Division

### **Prepared by:**

**UNITED STATES STANDARD GENERAL LEDGER ADVISORY DIVISION GOVENRMENTWIDE ACCOUNTING BUREAU OF THE FISCAL SERVICE U.S. DEPARTMENT OF TREASURY**

| Version | Date          | Description of Change                             | Effective | Effective |
|---------|---------------|---------------------------------------------------|-----------|-----------|
| Number  |               |                                                   | USSGL TFM | Date      |
| 1.0     |               | Updated Version –<br>Updated earlier version      |           | FY 2002   |
| 2.0     | 5/ 3<br>/2012 | Updated Version<br>incorporating DOL's accounting | S2-12-03  | FY 2013   |
|         |               | transactions<br>using new<br>USSGL accounts.      |           |           |

**Note:** This scenario follow USSGL TFM S2-12-03 (July 2012), Part 2 Fiscal 2013 crosswalks, and Part 3 "GTAS Implementation Testing" Fiscal 2014 format of USSGL accounts and attributes.

<span id="page-2-2"></span><span id="page-2-1"></span><span id="page-2-0"></span>**USSGL Proprietary and Budgetary Account Attribute Table[1](#page-2-0)**

|               |                                     |             | USSGL Account |             |                      |        |        |         |           |         |
|---------------|-------------------------------------|-------------|---------------|-------------|----------------------|--------|--------|---------|-----------|---------|
| USSGL Account |                                     |             | Attributes    |             | Bulk File Attributes |        |        |         |           |         |
| No.           | USSGL Account Title                 | Normal Bal. | Budge/        | Anticipated | Debit/               | Begin/ | Fed/   | Trading | Trading   | Exch/   |
|               |                                     | Ind.        | Prop          |             | Credit               | End    | NonFed | Partner | Ptnr Main | Nonexch |
| 132100        | Unfunded FECA Benefit Contributions | D           | P             | N           | D                    | B/E    | F      | ###     | ####      | *2      |
|               | Receivable                          |             |               |             |                      |        |        |         |           |         |
| 540500        | Unfunded FECA Benefit Revenue       | C           | P             | N           | C                    | E      | F      | ###     | ####      | X       |
| 540600        | Contra Revenue for<br>Unfunded FECA | D           | P             | N           | D                    | E      | F      | ###     | ####      | X       |
|               | Benefit Revenue                     |             |               |             |                      |        |        |         |           |         |

**USSGL Proprietary and Budgetary Account Attribute Table - Continue**

|        |                                                | TAS Attributes |                     |            |            |  |  |
|--------|------------------------------------------------|----------------|---------------------|------------|------------|--|--|
|        | USSGL Account                                  |                |                     |            |            |  |  |
|        | USSGL Account Title                            | Fund Type      | Reporting Type Code | TAS Status | Trans Code |  |  |
| 132100 | Unfunded FECA Benefit Contributions Receivable | EG             | U                   | U          | N          |  |  |
| 540500 | Unfunded FECA Benefit Revenue                  | EG             | U                   | U          | N          |  |  |
| 540600 | Contra Revenue for<br>Unfunded FECA Benefit    | EG             | U                   | U          | N          |  |  |
|        | Revenue                                        |                |                     |            |            |  |  |

**Crosswalk Impact**

| USSGL<br>Account<br>Number | Balance<br>Sheet | Net Cost | Net<br>Position | Custodial<br>Activity | P&F/<br>SF133 | SBR | 2108 | Reclassified<br>Balance<br>Sheet3 | Reclassified<br>Net Cost3 | Reclassified<br>Net<br>Position3 |
|----------------------------|------------------|----------|-----------------|-----------------------|---------------|-----|------|-----------------------------------|---------------------------|----------------------------------|
| 1321                       | Line 3           | N/A      | N/A             | N/A                   | N/A           | N/A | N/A  | Line 2.2                          | N/A                       | N/A                              |
| 5405                       | Line 33          | Line 2   | N/A             | N/A                   | N/A           | N/A | N/A  | Line 9.1                          | Line 11.1                 | N/A                              |
| 5406                       | Line<br>33       | Line 2   | N/A             | N/A                   | N/A           | N/A | N/A  | Line 9.1                          | Line 11.1                 | N/A                              |

<sup>1</sup> Refer to TFM S2-12-03(July 2012), Part 2, Section IV for a listing of domain values. <sup>2</sup> Asterisk indicates a particular attribute does not apply to the specific USSGL account.

<sup>3</sup> Fiscal 2013 reclassified statements are not yet available. It is possible for the line numbers on the reclassified crosswalks to change at that time.

### **Background:**

Federal Employees' Compensation Act (FECA) is administered by the Department of Labor (DOL), Office of Workers' Compensation Programs (OWCP). FECA provides income and medical cost protection worldwide for job-related injuries, diseases, or deaths of civilian employees of the Federal Government through a special benefit fund called the Federal Employees' Compensation Fund. The Employees Compensation Fund consists of reimbursements for benefits from insured worker's employing agencies and annual appropriation from the General Fund of Treasury.

The FECA fund pays benefits on behalf of Federal entities as costs are incurred and bills the entity annually before August 15 for the costs incurred during the **previous** 12-month period ended June 30 (July 1 – June 30). Federal entities fund the FECA payments through appropriations reimbursed to the FECA fund. For those agencies that have funding though appropriation, each entity shall include in its annual budget estimates for the fiscal year beginning in the next calendar year a request for an appropriation for the amount equal to the costs (approximately 15 months). Once the appropriation is received, the payments are due to DOL within 30 days.

There are 4 different types of FECA payment activities:

- a. Appropriated Agencies under 2-year cycle
- b. Non-appropriated Agencies
- c. Non-billable agencies
- d. Prepayment by Agency

This guidance will address the most common FECA payment activity, appropriated agencies under 2 year cycle. The USSGL may provide additional guidance on other FECA payment activities in the future should there be a need.

### **FECA Liability:**

Workers'' Compensation claims are submitted to, and approved by, the DOL. DOL pays the claim holders. DOL then prepares a chargeback billing to the responsible agencies. Public Law (PL) 93-416, Section 8147 (the FECA law) essentially gives agencies funded by appropriation 2 years to pay the chargeback bill; thereby allowing time for applicable amount to be included in budget submissions. Therefore, there should be an unfunded liability reported in the agencies' books for these 2 years (bills are for periods July 1 – June 30), plus an accrual for the 4th quarter of the current FY. This amount must be split into a current portion for the amount

<span id="page-4-1"></span><span id="page-4-0"></span>to be paid in the next FY and a non-current portion for the remaining amount. Pursuant to the FECA law, once funding is received the FECA chargeback bill should be paid within 30 days. FECA chargeback bills that are still outstanding after the 30-day period are considered delinquent and should be reflected as a funded liability with a footnote disclosure.[4](#page-4-0)

### **FECA Actuarial Information:**

The FECA Actuarial liability includes the expected liability for death, disability, medical, and other approved costs. It is estimated using the paid-loss extrapolation method. This method uses historical benefit payment patterns related to a specific incurred period to predict the entire payments related to that period. The payments are discounted to present value.

The DOL sends each agencies the actuarial liability estimates for future worker's compensation benefits amounts for both the current and prior years. The current figure is what the new balance in the Actuarial FECA Liability Account (2650) should be after the source data (DOL information) journal voucher entry is completed by the entity. This entry represents a change in accounting estimate, and is strictly proprietary, as actuarial liabilities are unfunded.[5](#page-4-1) The expense is determined by comparing the current-year amount to the prior-year amount.

### Journal Voucher Entry Support:

The following support must be included with the Actuarial FECA Liability entry:

- 1. The DOL Memorandum for Chief Financial Officers of Executive Departments and Agencies, which contains the actuarial balances.
- 2. Agency-Wide Financial Statements Directorate allocation spreadsheet reflecting the percentage allocation to the entity level.
- 3. A copy of the last three annual chargeback bills for the department level.

1 of 71 5/3/2012

<sup>4</sup> See Illustration 1 for sample journal entry to record *Unfunded FECA liability* <sup>5</sup> If there is an increase in FECA actuarial liability, debit USSGL account 7600 and credit USSGL account 2650. Reverse the entry if there is a decrease in the FECA actuarial liability.

### **Questions and Answers for Paying agencies with Permanent Indefinite Authority.**

**Question:** Can a paying agency with permanent indefinite budget authority always record a FECA liability as funded? **Answer:** No. Although an agency may have a permanent indefinite appropriation, the Treasury Appropriation Fund Symbol must have budgetary resources available for the FECA obligation as of end of the fiscal year and must be apportioned (if applicable) in order to record a budgetary account payable.

**Question:** Can a paying agency with permanent indefinite budget authority record a FECA liability as funded where its Treasury Appropriation Fund Symbol has budgetary resources available for obligation as of the end of the fiscal year but the FECA chargeback bill is budgeted for a subsequent fiscal year?

**Answer:** No, the paying agency with permanent indefinite budget authority should not record a budgetary account payable with the budgetary resources available for obligation as of the end of the fiscal year. As of the end of the fiscal year, the FECA liability would be classified as unfunded. In a future fiscal year, the agency would record the funded FECA liability for the period the FECA chargeback bill was budgeted.

### **Relevant References:**

### **Per SFFAS No. 7, FECA transactions are considered exchange revenue.**

**Paragraph 320. Employer entity payments for unemployment benefits and workers compensation**.-The employer entity recognizes a liability and an expense for Federal employees who are laid-off or injured on the job and are entitled under law to unemployment benefits or workers compensation, respectively. The payment to the former or current employee is made by the unemployment trust fund (Department of Labor) in the case of unemployment benefits and by the special benefits fund (Department of Labor) in the case of workers compensation. Unemployment benefits are reimbursed by the former employer entity; and workers compensation costs are mostly charged back to the employer entity.

**Paragraph 321**. Since the costs are recognized by the employer entity and its payment to the unemployment trust fund or the special benefits fund reimburses these funds for the costs they incur, the amounts these funds receive from the employer entity are exchange revenues.

**OMB Circular A11, section 32.2, How do I treat agency benefit payments under the Federal Employees' Compensation Act?**  For accounts subject to appropriations action, include in your budget year estimates the amount billed by the Employment Standards Administration (Office of Workers' Compensation Program) of the Department of Labor for benefits paid on behalf of employees of your agency in the past year under the Federal Employees' Compensation Act.

For accounts not subject to appropriations action, you must pay the bill in the current year.

### **Assumptions Used in This guidance:**

- 1) Department of Labor's 016 1521 is a no year fund.
- 2) DOL uses FECA reimbursements from agencies to pay for the FECA claims filed by the injured employees. DOL will use this resource to pay the FECA claims. For the purpose of this illustration, assume agency 040's reimbursement is used to pay agency 30's employees. Agency 040 was chosen for illustrative purpose only.
- 3) Agency codes 030 and 040 are fictious agency code. They are used to illustrate partner codes in this guidance.
- 4) Assume agency 030 is a newly formed agency and it started its operation in Year X1.
- 5) Agency 030 receives a chargeback in Year X2 for actual FECA payments made by DOL on behalf of Agency 030 from Jul X1 June X2. Assume DOL did not pay FECA claims to agency 030 employees prior to Oct 1, X1(fiscal year X2).
- 6) To simplify the FECA illustration, agency 030 will not have any other activity recorded except FECA related activities.
- 7) Assume agency 030 FECA reimbursement to DOL is paid out from a multi year fund which is also mandatory program.

**New USSGL Accounts**

**Account Title:** Unfunded FECA Benefit Contributions Receivable

**Account Number:** 132100

**Account Definition:** The amount recorded by the Department of Labor for unfunded FECA contributions due from Federal

employers. Until the Federal paying agency records the actual budgetary obligation, the associated FECA liability and receivable are

considered unfunded. This account does not close at yearend.

**Normal Balance**: Debit

**Justification:** To assist agencies with interagency reconciliation of benefit programs.

**Account Title:** Unfunded FECA Benefit Revenue

**Account Number:** 540500

**Account Definition:** The amount of unfunded FECA accrued revenue recorded by the Department of Labor due from Federal

employers.

**Normal Balance**: Credit

**Justification:** To assist agencies with interagency reconciliation of benefit programs.

**Account Title:** Contra Revenue for Unfunded FECA Benefit Revenue

**Account Number:** 540600

**Account Definition:** The amount reflecting a reduction in unfunded FECA revenue for a benefit program based on adjustments as

stipulated by law.

**Normal Balance**: Debit

**Justification:** To assist agencies with interagency reconciliation of benefit programs.

### **Changes to Existing Accounts:**

**Account Title:** Funded Employment Benefit Contributions Receivable

**Account Number:** 132000 **Normal Balance**: Debit

**Account Definition:** The amount recorded by administering agencies for funded contributions due from Federal employers and/or covered employees for employment related benefits such as retirement, health insurance, life insurance, Federal Employees' Compensation Act, and unemployment compensation. This amount excludes Social Security taxes. When the Federal paying agency records the actual budgetary obligation, the associated FECA liability and receivable are considered funded. This account does not close at yearend.

**Justification:** To assist agencies with inter-agency reconciliation of benefit programs.

**Account Title:** Funded Benefit Program Revenue

**Account Number:** 540000 **Normal Balance**: Credit

**Account Definition:** The amount of funded revenue recorded by administering agencies for retirement plans, insurance plans, and

other annuities.

**Justification:** To assist agencies with inter-agency reconciliation of benefit programs.

**New Account Title:** Contra Revenue for Funded Benefit Program Revenue

**Account Number:** 540900 **Normal Balance**: Debit

**Account Definition:** The amount reflecting a reduction in funded revenue for a benefit program based on adjustments as stipulated by

law.

**Justification:** To assist agencies with inter-agency reconciliation of benefit programs.

### **Listing of USSGL Accounts Used In This Scenario**

| Account     |                                                                                      |
|-------------|--------------------------------------------------------------------------------------|
| Number      | Account Name                                                                         |
|             |                                                                                      |
| Budgetary   |                                                                                      |
| 411900      | Appropriation Realized                                                               |
| 420100      | Total Actual Resource Realized -<br>Collection                                       |
| 421000      | Anticipated Reimbursements and Other Income                                          |
| 422100      | Unfilled Customer Order without Advance                                              |
| 425100      | Reimbursements and Other Income Earned -<br>Receivable                               |
| 425200      | Reimbursements and Other Income Earned -<br>Collected                                |
| 445000      | Unapportioned Authority                                                              |
| 451000      | Apportionment                                                                        |
| 459000      | Apportionment<br>–<br>Anticipated<br>Resources –<br>Program Subject to Apportionment |
| 461000      | Allotment                                                                            |
| 490100      | Delivered Orders –<br>Obligations, Unpaid                                            |
| 490200      | Delivered Orders –<br>Obligations Pd                                                 |
| Proprietary |                                                                                      |
| 101000      | Fund Balance with Treasury                                                           |
| 132000      | Funded Employment Benefit Contributions Receivable                                   |
| 132100      | Unfunded Employee Benefit Contributions Receivable                                   |
| 221500      | Other Post Employment Benefits Due and Payable                                       |
| 222500      | Unfunded FECA Liability                                                              |
| 265000      | Actuarial FECA Liability                                                             |
| 310000      | Unexpended Appropriation                                                             |
| 310100      | Unexpended Appropriation -Appropriation Received                                     |
| 310700      | Unexpended Appropriation Used                                                        |
| 331000      | Cumulative Results of Operations                                                     |
| 540000      | Funded Benefit Program Revenue                                                       |

| 540500 | Unfunded Benefit Program Revenue                                                                |
|--------|-------------------------------------------------------------------------------------------------|
| 570000 | Appropriation Used                                                                              |
| 640000 | Benefit Expense                                                                                 |
| 685000 | Employer Contributions to Employee Benefit Programs Not Requiring Current-Year Budget Authority |
| 760000 | Changes in Actuarial Liability                                                                  |

#### **Beginning Trial Balance**

| Agency (030)                               |    |    | DOL (016<br>1521)                                      |         |         |
|--------------------------------------------|----|----|--------------------------------------------------------|---------|---------|
| Budgetary                                  | DR | CR | Budgetary                                              | DR      | CR      |
| 420100<br>Total Actual Resource Realized - | 0  |    | 425100<br>–Reimbursements and Other Income Earned<br>- | 700,000 |         |
| Collection                                 |    |    | Receivable                                             |         |         |
| 445000 Unapportioned Authority             |    | 0  | 445000<br>Unapportioned Authority                      |         | 700,000 |
| Totals                                     |    |    | Totals                                                 | 700,000 | 700,000 |
|                                            |    |    |                                                        |         |         |
| Proprietary                                |    |    | Proprietary                                            |         |         |
| 310000(G099)<br>Unexpended Appropriation   | 0  |    | 132000(F040) Funded Employment Benefit Contributions   | 700,000 |         |
|                                            |    |    | Receivable                                             |         |         |
| 331000<br>Cumulative Results of Operations |    | 0  | 331000<br>Cumulative Results of Operations             |         | 700,000 |
|                                            |    |    |                                                        |         |         |
| TOTALS                                     | 0  | 0  | TOTALS                                                 | 700,000 | 700,000 |

### **FECA Calculations Provided by DOL to Agency 030 for 20X2**

**Calculation Table:**

| Funded/Unfunded FECA Liability/FECA                  | Chargeback        | Amounts | Funded/Unfunded FECA Expense/FECA       | Chargeback        | Amounts |
|------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Receivable                                           | Period or FY      |         | Revenue                                 | Period or FY      |         |
| Year X1                                              |                   |         | Year X1                                 |                   |         |
| Annual Chargeback                                    | 07/01/X0-06/30/X1 | 0       | Annual Chargeback                       | 07/01/X0-06/30/X1 | 0       |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Total Unfunded Liability\<br>Receivable<br>Year X1   | 10/01/X0-09/30/X1 | 0       | Total Unfunded FECA Exp/Revenue Year X1 | 10/01/X0-09/30/X1 | 0       |
| Cumulative Unfunded Liability\<br>Receiv<br>Year X1  | 10/01/X0-09/30/X1 | 0       |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X2                                              |                   |         | Year X2                                 |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Quarter 1, Year X2 10/01/X1-12/31/X1                 |                   | 60,000  | Quarter 1, Year X2 10/01/X1-12/31/X1    |                   | 60,000  |
| Quarter 2, Year X2 01/01/X2-03/31/X2                 |                   | 70,000  | Quarter 2, Year X2 01/01/X2-03/31/X2    |                   | 70,000  |
| Quarter 3, Year X2 04/01/X2-06/30/X2                 |                   | 40,000  | Quarter 3, Year X2 04/01/X2-06/30/X2    |                   | 40,000  |
| Annual Chargeback                                    | 07/01/X1-06/30/X2 | 170,000 | Annual Chargeback                       | 07/01/X1-06/30/X2 | 170,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Total Unfunded Liability\<br>Receivable Year X2      | 10/01/X1-09/30/X2 | 205,000 | Total Unfunded FECA Exp/Revenue Year X2 | 10/01/X1-09/30/X2 | 205,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X2 | 10/01/X0-09/30/X2 | 205,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X3                                              |                   |         | Year X3                                 |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Quarter 1, Year X3 10/01/X2-12/31/X2                 |                   | 45,000  | Quarter 1, Year X3 10/01/X2-12/31/X2    |                   | 45,000  |
| Quarter 2, Year X3 01/01/X3-03/31/X3                 |                   | 60,000  | Quarter 2, Year X3 01/01/X3-03/31/X3    |                   | 60,000  |
| Quarter 3, Year X3 04/01/X3-06/30/X3                 |                   | 50,000  | Quarter 3, Year X3 04/01/X3-06/30/X3    |                   | 50,000  |
| Annual Chargeback                                    | 07/01/X2-06/30/X3 | 190,000 | Annual Chargeback                       | 07/01/X2-06/30/X3 | 190,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X3 07/01/X3-09/30/X3                 |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |
| Total Unfunded Liability\<br>Receivable Year X3      | 10/01/X2-09/30/X3 | 210,000 | Total Unfunded FECA Exp/Revenue Year X3 | 10/01/X2-09/30/X3 | 210,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X3 | 10/01/X0-09/30/X3 | 415,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X4                                              |                   |         | Year X4                                 |                   |         |
| Quarter 4, Year X3 07/01/X3-09/30/X3                 |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |

| Quarter 1, Year X4 10/01/X3-12/31/X3                                    |                   | 50,000  | Quarter 1, Year X4 10/01/X3-12/31/X3    |                   | 50,000  |
|-------------------------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Quarter 2,<br>Year X4 01/01/X4-03/31/X4                                 |                   | 65,000  | Quarter 2, Year X4 01/01/X4-03/31/X4    |                   | 65,000  |
| Quarter 3, Year X4 04/01/X4-06/30/X4                                    |                   | 80,000  | Quarter 3, Year X4 04/01/X4-06/30/X4    |                   | 80,000  |
| Annual Chargeback                                                       | 07/01/X3-06/30/X4 | 250,000 | Annual Chargeback                       | 07/01/X3-06/30/X4 | 250,000 |
|                                                                         |                   |         |                                         |                   |         |
| Quarter 4, Year X4 07/01/X4-09/30/X4                                    |                   | 45,000  | Quarter 4, Year X4 07/01/X4-09/30/X4    |                   | 45,000  |
| Total Unfunded Liability\<br>Receivable Year X4                         | 10/01/X3-09/30/X4 | 240,000 | Total Unfunded FECA Exp/Revenue Year X4 | 10/01/X3-09/30/X4 | 240,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X4                    | 10/01/X0-09/30/X4 | 485,000 | Net Unfunded FECA Exp/Revenue Year X4   | 10/01/X3-09/30/X4 | 70,000  |
| +205,000<br>+<br>210,000<br>+240,000<br>= 655,000 -170,000<br>= 485,000 |                   |         | +240,000 –<br>170,000 = 70,000          |                   |         |
| Total Funded Liability\<br>Receivable Year X4                           | 10/01/X1-09/30/X2 | 170,000 | Total Funded FECA Exp/Revenue Year X4   | 10/01/X1-09/30/X2 | 170,000 |

### **Year X2**

1) DOL receives apportionment and allotment for reimbursements from agency 040. Note: DOL is using reimbursements from prior claims from other agencies to fund the FECA claim for agency 030 employees.

| Agency (030) Transaction                 | Transaction<br>Code | DOL (016<br>1521) Transaction                                                                                                                                           |              |
|------------------------------------------|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Budgetary<br>None<br>Proprietary<br>None |                     | Budgetary<br>445000<br>Unapportioned Authority<br>700,000<br>451000<br>Apportionment<br>700,000<br>451000<br>Apportionment<br>700,000<br>461000<br>Allotment<br>700,000 | A116<br>A120 |
|                                          |                     | Proprietary<br>None                                                                                                                                                     |              |

2) DOL receives FECA reimbursements from agency 040. Although DOL receives reimbursements from the other Federal agencies on a regular basis, for this illustration purpose the payment from agency 040 will only appear once to show the funding of agency 030's actual FECA compensation.

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                                                    |     |
|--------------------------|-------------|-------------------------------------------------------------------------------|-----|
|                          | Code        |                                                                               |     |
| Budgetary                |             | Budgetary                                                                     |     |
| None                     |             | 425200 Reimbursements and Other Income Earned –<br>Collected<br>700,000       | New |
|                          |             | 425100 Reimbursements and Other Income Earned –<br>Receivable<br>700,000      |     |
| Proprietary              |             |                                                                               |     |
| None                     |             | Proprietary                                                                   |     |
|                          |             | 101000(G099)<br>Fund Balance with Treasury<br>700,000                         |     |
|                          |             | 132000(F040) Funded Employment Benefit Contributions<br>Receivable<br>700,000 |     |

<span id="page-16-2"></span><span id="page-16-1"></span><span id="page-16-0"></span>3) DOL pays workers' compensation to employees of agency 030 from Qtr 1, Year 2(10/1/X1-12/31/X1). Assume this is the first FECA claim payments for agency 030.

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                     |        |      |
|--------------------------|-------------|------------------------------------------------|--------|------|
|                          | Code        |                                                |        |      |
| Budgetary                |             | Budgetary                                      |        |      |
| None                     |             | 461000<br>Allotment                            | 60,000 | E106 |
|                          |             | 490200<br>Delivered Orders –<br>Obligations Pd | 60,000 | B110 |
| Proprietary              |             |                                                |        |      |
| None                     |             | Proprietary                                    |        |      |
|                          |             | 640000(N)<br>Benefit expense                   | 60,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury     | 60,000 |      |

4) DOL notifies[6](#page-16-0) agency 030 of \$60,000 which reflects its workers' compensation paid out during Qtr 1, Year 2(10/1/X1-12/31/X1). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                   | TC   |
|-----------------------------------------------------------------------|------|--------------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary8                                                   |      |
| None                                                                  |      | None                                                         | C421 |
| Proprietary                                                           |      |                                                              |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                                  |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>60,000       | B422 | 132100(F030)<br>Unfunded Employee Benefit Contrib Rec 60,000 |      |
| 222500(F016) Unfunded FECA Liability7<br>60,000                       |      | 540500(F030)<br>Unfunded Benefit Program Revenue<br>60,000   |      |

Changes in uncollected customer payments from Federal sources. You need to adjust the spending authority from cash collections if the account is authorized to perform reimbursable work for another Federal account and you incur obligations against receivables from Federal sources and unfilled customer orders from Federal sources without an advance—that is, before receiving the cash. The law allows you to incur such obligations as long as the paying account is a Federal account and an obligation is recorded against resources available to the paying account. For example, a financing account can obligate against a subsidy accounts receivable from the program account before the cash is received from the program account if the program account has recorded an obligation in the form of a subsidy accounts payable to the financing account.

<sup>6</sup> DOL notifies the agencies by providing them with the quarterly chargebacks.

<sup>7</sup> From an agency or fund perspective, the **accrued unfunded FECA liability** is the difference between the FECA benefits paid by the FECA Special Benefits Fund and the agency's actual cash payment to the Fund. For example, the Special Benefits Fund will pay benefits on behalf of an agency or fund through the current year. However, most agencies' actual cash payments to the FECA Special Benefit Fund for the current FY will reimburse the Fund for benefits paid through a prior fiscal year. The difference between these two amounts -- benefits paid by the Fund and reimbursements made by the agencies -- is the accrued unfunded liability.

<sup>8</sup> OMB A11 20.4

5) DOL pays workers' compensation to employees of agency 030 from Qtr 2, Year 2(01/01/X2-03/31/X2).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |      |
|--------------------------|-------------|---------------------------------------------|--------|------|
|                          | Code        |                                             |        |      |
| Budgetary                |             | Budgetary                                   |        |      |
| None                     |             | 461000 Allotment                            | 70,000 | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd | 70,000 | B110 |
| Proprietary              |             |                                             |        |      |
| None                     |             | Proprietary                                 |        |      |
|                          |             | 640000(N)<br>Benefit expense                | 70,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  | 70,000 |      |

6) DOL notifies agency 030 of \$70,000 which reflects its workers' compensation paid out during Qtr 2, Year 2(01/01/X2-03/31/X2). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not | B422 | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>70,000       |      | 132100(F030) Unfunded Employee Benefit Contrib Rec 70,000 |      |
| 222500(F016) Unfunded FECA Liability<br>70,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>70,000   |      |

7) DOL pays workers' compensation to employees of agency 030 from Qtr 3, Year 2(04/01/X2-06/30/X2).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                                                                |        |        |              |
|--------------------------|-------------|-------------------------------------------------------------------------------------------|--------|--------|--------------|
|                          | Code        |                                                                                           |        |        |              |
| Budgetary                |             | Budgetary                                                                                 |        |        |              |
| None                     |             | 461000 Allotment<br>490200 Delivered Orders –<br>Obligations Pd                           | 40,000 | 40,000 | E106<br>B110 |
| Proprietary<br>None      |             | Proprietary<br>640000(N)<br>Benefit expense<br>101000(G099)<br>Fund Balance with Treasury | 40,000 | 40,000 |              |

8) DOL notifies agency 030 of \$40,000 which reflects its workers' compensation paid out during Qtr 3, Year 2(04/01/X2-06/30/X2). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC     | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|--------|-----------------------------------------------------------|------|
| Budgetary                                                             |        | Budgetary                                                 |      |
| None                                                                  |        | None                                                      | C421 |
| Proprietary                                                           |        |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not | B422   | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>40,000       |        | 132100(F030) Unfunded Employee Benefit Contrib Rec 40,000 |      |
| 222500(F016) Unfunded FECA Liability                                  | 40,000 | 540500(F030) Unfunded Benefit Program Revenue<br>40,000   |      |

9) Before 8/15/X2, the Department of Labor issues first FECA annual chargeback bill (7/1/X1-6/30/x2) to agency 030 for the actual amount of workers' compensation DOL has paid on behalf of agency 030 from 10/1/X1 to 6/30/X2. Note: agency 030 did not have any FECA claims paid until 10/1/X1. Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the following quarter. Assume for illustration purpose the sum of the quarterly amounts and the annual chargeback amounts are equal. Approximately after 15 months (fiscal year 20X4), agency 030 receives funding to reimburse DOL.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

**Note:** Any agency that identifies a discrepancy on their annual chargeback bill should communicate the need for the adjustment to DOL. Once the validity of the adjustment is confirmed, DOL will make the correction to its records which will then be reflected on the next Chargeback bill. No adjusting entries should be made preemptively on the part of the agency; otherwise, the correction will be reflected twice on that agency's financial statements.

10) DOL pays workers' compensation claim of \$35,000 to agency 030's employees from Qtr 4, Year 2(7/1/X2-9/30/X2).

| Agency (030) Transaction | Transaction | DOL (016 1521)<br>Transaction                  |        |        |      |
|--------------------------|-------------|------------------------------------------------|--------|--------|------|
|                          | Code        |                                                |        |        |      |
| Budgetary                |             | Budgetary                                      |        |        |      |
| None                     |             | 461000<br>Allotment                            | 35,000 |        | E106 |
|                          |             | 490200<br>Delivered Orders –<br>Obligations Pd |        | 35,000 | B110 |
| Proprietary              |             |                                                |        |        |      |
| None                     |             | Proprietary                                    |        |        |      |
|                          |             | 640000(N)<br>Benefit expense                   | 35,000 |        |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury     |        | 35,000 |      |

11) DOL notifies agency 030 of \$35,000 which reflects its workers' compensation paid out during Qtr 4, Year 2(7/1/X2-9/30/X2). Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the 4th quarter. Assume there are no differences for this illustration purpose. DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>35,000       | B422 | 132100(F030) Unfunded Employee Benefit Contrib Rec 35,000 |      |
| 222500(F016) Unfunded FECA Liability<br>35,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>35,000   |      |

12) Agency 030 submits annual budget estimates for the fiscal year beginning in the next calendar year to request for an appropriation for unfunded FECA cost.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

<span id="page-20-1"></span><span id="page-20-0"></span>13) Department of Labor provides FECA actuarial liability[9](#page-20-0) to agency 030. This entry is made at the Fiscal-Year-end only and there is no budgetary impact.

| Agency (030) Transaction                       |           | TC   | DOL (016 1521) Transaction | TC |
|------------------------------------------------|-----------|------|----------------------------|----|
| Budgetary                                      |           |      | Budgetary                  |    |
| None                                           |           |      | None                       |    |
|                                                |           |      |                            |    |
| Proprietary                                    |           |      | Proprietary                |    |
| (N) Changes in Actuarial Liability10<br>760000 | 3,000,000 | B426 | None                       |    |
| 265000<br>(N) Actuarial FECA Liability         | 3,000,000 |      |                            |    |

<sup>9</sup> The **FECA actuarial liability** includes the expected liability for death, disability, medical, and other approved costs. It is estimated using the paid-loss extrapolation method. This method uses historical benefit payment patterns related to a specific incurred period to predict the entire payments related to that period. The payments are discounted to present value.

<sup>10</sup> This is the first year that agency 030 is in operation; therefore there is no prior year FECA actuarial liability recorded. The change will be Ending-Beginning(0)

#### **PRE-CLOSING TRIAL BALANCE**

#### **YEAR 2**

| Agency (030)                               |           |           | DOL (016 1521) Transaction                      |         |         |  |
|--------------------------------------------|-----------|-----------|-------------------------------------------------|---------|---------|--|
| Budgetary                                  | DR        | CR        | Budgetary                                       | DR      | CR      |  |
| 420100 Total Actual Resource Realized -    | 0         |           | 425200 Reimbursements and Other Income Earned – | 700,000 |         |  |
| Collection                                 |           |           | Collected                                       |         |         |  |
| 445000 Unapportioned Authority             |           | 0         | 461000 Allotment                                |         | 495,000 |  |
|                                            |           |           | 490200 Delivered Orders –<br>Obligations Pd     |         | 205,000 |  |
|                                            |           |           |                                                 | 700,000 | 700,000 |  |
|                                            |           |           |                                                 |         |         |  |
| Proprietary                                |           |           | Proprietary                                     |         |         |  |
| 222500(F016)<br>Unfunded FECA Liability    |           | 205,000   | 101000(G099)<br>Fund Balance with Treasury      | 495,000 |         |  |
| 265000N Actuarial FECA Liability           |           | 3,000,000 | 132100(F030) Unfunded Employee Benefit          | 205,000 |         |  |
|                                            |           |           | Contributions Receivable                        |         |         |  |
| 310000 (G099)Unexpended Appropriation      |           | 0         | 331000 Cumulative Results of Operations         |         | 700,000 |  |
| 331000 Cumulative Results of Operations    |           | 0         | 540500(F030) Unfunded Benefit Program revenue   |         | 205,000 |  |
| 685000(F016) Employer Contributions to     | 205,000   |           | 640000N Benefits Expense                        | 205,000 |         |  |
| employee Benefit Programs Not requiring CY |           |           |                                                 |         |         |  |
| Budget Authority                           |           |           |                                                 |         |         |  |
| 760000N Changes in Actuarial Liability     | 3,000,000 |           |                                                 |         |         |  |
| TOTALS                                     | 3,205,000 | 3,205,000 | TOTALS                                          | 905,000 | 905,000 |  |

#### **CLOSING ENTRIES FOR END OF YEAR 2**

**C1. To record the closing of revenue, expense, and other financing source accounts to cumulative results of operations.**

| Agency (030)                                 |           |           | DOL (016 1521) Transaction |                                          |         |         |      |
|----------------------------------------------|-----------|-----------|----------------------------|------------------------------------------|---------|---------|------|
| USSGL Account                                | Debit     | Credit    | TC                         |                                          | Debit   | Credit  | TC   |
| Budgetary                                    |           |           |                            | Budgetary                                |         |         |      |
| None                                         |           |           |                            | None                                     |         |         |      |
|                                              |           |           |                            |                                          |         |         |      |
| Proprietary                                  |           |           |                            | Proprietary                              |         |         |      |
| 331000<br>Cumulative Results of Operations   | 3,000,000 |           | F340                       | 540500(F030)<br>Unfunded Benefit Program | 205,000 |         | F336 |
| 760000<br>(N) Changes in Actuarial Liability |           | 3,000,000 |                            | Revenue                                  |         |         |      |
|                                              |           |           |                            | 331000 Cumulative Results of             |         | 0       |      |
| 331000<br>Cumulative Results of Operations   | 205,000   |           | F336                       | Operations                               |         |         |      |
| 685000<br>(F16) Employer Contributions to    |           | 205,000   |                            | 640000(N)<br>Benefit Expense             |         | 205,000 |      |
| Employee Benefit Programs Not Requiring      |           |           |                            |                                          |         |         |      |
| Current-Year Budget Authority (Unobligated)  |           |           |                            |                                          |         |         |      |

**C2. To record the closing of budgetary resources.** 

| Agency (030)                             |       |        |    | DOL (016 1521) Transaction                                                                                                        |         |         |      |
|------------------------------------------|-------|--------|----|-----------------------------------------------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account                            | Debit | Credit | TC |                                                                                                                                   | Debit   | Credit  | TC   |
| Budgetary<br>None<br>Proprietary<br>None |       |        |    | Budgetary<br>420100<br>Total Actual Resources<br>Collected<br>425200<br>–Reimbursements and Other<br>Income Earned –<br>Collected | 700,000 | 700,000 | F302 |
|                                          |       |        |    | Proprietary<br>None                                                                                                               |         |         |      |

**C3. To record the closing of unobligated balances to no year funds.** 

| Debit   | Credit | TC      |
|---------|--------|---------|
|         |        |         |
|         |        |         |
| 495,000 |        | F308    |
|         |        |         |
|         |        |         |
|         |        |         |
|         |        |         |
|         |        | 495,000 |

**C4. To record the closing of paid delivered order to total actual resources.** 

| Agency (030)        |       |        |    | DOL (016 1521) Transaction                                                                           |         |         |      |
|---------------------|-------|--------|----|------------------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account       | Debit | Credit | TC |                                                                                                      | Debit   | Credit  | TC   |
| Budgetary<br>None   |       |        |    | Budgetary<br>490200<br>Delivered Orders-Obligations Pd<br>420100<br>Total Actual Resources-Collected | 205,000 | 205,000 | F314 |
| Proprietary<br>None |       |        |    | Proprietary<br>None                                                                                  |         |         |      |

#### **POST-CLOSING TRIAL BALANCE YEAR 2**

| Agency (030)                               |           |           | DOL (016)                                  |         |         |
|--------------------------------------------|-----------|-----------|--------------------------------------------|---------|---------|
| Budgetary                                  | DR        | CR        | Budgetary                                  | DR      | CR      |
| 420100<br>Total Actual Resource Realized - | 0         |           | 420100<br>Total Actual Resources-Collected | 495,000 |         |
| Collection                                 |           |           |                                            |         |         |
| 445000 Unapportioned Authority             |           | 0         | 445000 Unapportioned Authority             |         | 495,000 |
|                                            |           |           |                                            | 495,000 | 495,000 |
|                                            |           |           | TOTALS                                     |         |         |
|                                            |           |           |                                            |         |         |
| Proprietary                                |           |           | Proprietary                                |         |         |
| 222500(F016) Unfunded FECA Liability       |           | 205,000   | 101000(G099)<br>Fund Balance with Treasury | 495,000 |         |
| 265000(N)<br>Actuarial FECA Liability      |           | 3,000,000 | 132100(F030) Unfunded Employee Benefit     | 205,000 |         |
|                                            |           |           | Contributions Receivable                   |         |         |
| 331000 Cumulative Results of Operations    | 3,205,000 |           | 331000 Cumulative Results of Operations    |         | 700,000 |
|                                            |           |           |                                            |         |         |
|                                            |           |           |                                            |         |         |
| TOTALS                                     | 3,205,000 | 3,205,000 | TOTALS                                     | 700,000 | 700,000 |

#### **BALANCE SHEET YEAR 2**

|                                                                          | Agency 030  | DOL(016) |
|--------------------------------------------------------------------------|-------------|----------|
| Assets                                                                   |             |          |
| Intragovernmental                                                        |             |          |
| 1. Fund Balance with Treasury (101000)                                   |             | 495,000  |
| (132100E)<br>3. Accounts Receivable                                      | 0           | 205,000  |
| 6. Total Intragovernmental                                               |             | 700,000  |
| 15. Total Assets                                                         |             | 700,000  |
| Liabilities                                                              |             |          |
| Intragovernmental                                                        |             |          |
| 19 Other (222500)                                                        | 205,000     |          |
| Total Intragovernmental                                                  | 205,000     |          |
| Liabilities with Public                                                  |             |          |
| 24. Federal Employee and Veteran Benefits (265000)                       | 3,000,000   |          |
| 28.Total Liabilities                                                     | 3,205,000   |          |
| Net Position                                                             |             |          |
| 31. Unexpended Appropriation –<br>Other Funds                            |             | 0        |
| 33. Cumulative Results of Operations-Other Funds (640000, 685000,760000) | (3,205,000) | 700,000  |
| 34. Total Net Position                                                   | (3,205,000) | 700,000  |
| 35. Total Liabilities and Net Position                                   | 0           | 700,000  |
|                                                                          |             |          |

#### **STATEMENT OF NET COST YEAR 2**

| Program Costs                                            | Agency (030) | DOL(016) |
|----------------------------------------------------------|--------------|----------|
| Program A:                                               |              |          |
| 1. Gross Cost :                                          |              |          |
| (685000F, 640000N)                                       | 205,000      | 205,000  |
| (760000N)                                                | 3,000,000    |          |
| 2. Less: Earned Income(540500E)                          | 0            | 205,000  |
| 3. Net Program Costs                                     | 3,205,000    | 0        |
| 5.<br>Net Program Costs Including Assumption Changes     | 3,205,000    | 0        |
| 6.<br>Costs Not Assigned to Programs                     |              |          |
| 7.<br>Less: Earned Revenues Not Attributable to Programs |              |          |
| 8.<br>Net Cost of Operations                             | 3,205,000    | 0        |

### **USSGL 2108 YEAR-END CLOSING STATEMENT YEAR 2**

|                     | Agency (030) | DOL(016) |
|---------------------|--------------|----------|
| Column 5 (101000E)  | 0            | 495,000  |
|                     |              |          |
| Column 11 (461000E) | 0            | 495,000  |

### **Statement of Changes In Net Position YEAR 2**

| Cumulative Results of Operations<br>1. Beginning Balance<br>2. Adjustments | Agency (030)<br>0 | DOL(016)<br>700,000 |
|----------------------------------------------------------------------------|-------------------|---------------------|
| 3. Beginning Balances, as Adjusted                                         | 0                 | 700,000             |
| Budgetary Financing Sources                                                |                   |                     |
| 4. Other Adjustments                                                       |                   |                     |
| 5. Appropriations Used                                                     |                   |                     |
| 6. Nonexchange Revenue                                                     |                   |                     |
| 7. Donations and Forfeitures                                               |                   |                     |
| 8. Transfers in/out without reimbursements                                 |                   |                     |
| 9. Other                                                                   |                   |                     |
| Other Financing Sources:                                                   |                   |                     |
| 10. Donations and Forfeitures                                              |                   |                     |
| 13. Other (599400)                                                         |                   |                     |
| 14. Total Financing Sources                                                |                   | 0                   |
| 15. Net Cost of Operations                                                 | (3,205,000)       | 0                   |
| 16. Net Change                                                             | (3,205,000)       | 0                   |
| 17. Cumulative Results of Operations                                       | (3,205,000)       | 0                   |
| Unexpended Appropriations                                                  |                   |                     |
| 18. Beginning Balance                                                      | 0                 | 0                   |
| 19. Adjustments                                                            |                   |                     |
| 20. Beginning Balance, as adjusted                                         | 0                 | 0                   |
| Budgetary Financing Sources                                                |                   |                     |
| 21. Appropriations Received (310100)                                       | 0                 | 0                   |
| 22. Appropriations Transferred in/out                                      |                   |                     |
| 23. Other<br>Adjustments                                                   |                   |                     |
| 24. Appropriations Used (310700)                                           | 0                 | 0                   |
| 25. Total Budgetary Financing Sources                                      | 0                 | 0                   |
| 26. Total Unexpended Appropriations                                        | 0                 | 0                   |
| 27. Net Position                                                           | (3,205,000)       | 700,000             |
|                                                                            |                   |                     |

### **STATEMENT OF BUDGETARY RESOURCES**

|                                                                                                          | TAFS (030) | TAFS (16 1521) |  |
|----------------------------------------------------------------------------------------------------------|------------|----------------|--|
| BUDGETARY RESOURCES                                                                                      |            |                |  |
| 1000<br>Unobligated balance<br>brought forward, October (420100B)                                        | 0          | 0              |  |
| 1890 Spending Authority for Offsetting Collection (425200E)                                              | 0          | 700,000        |  |
| 1910 Total Budgetary Resources (sum of SBR lines 1000, 1020, 1021, 1043, 1290,<br>1490, 1690, and 1890.) | 0          | 700,000        |  |
| STATUS OF BUDGETARY RESOURCES                                                                            |            |                |  |
| 2190 Obligations Incurred (490200E)                                                                      | 0          | 205,000        |  |
| 2204 Apportioned (461000E)                                                                               | 0          | 495,000        |  |
| 2490 Unobligated balance brought forward, end of year (sum of SBR lines 2204, 2304,                      |            |                |  |
| and 2404.)                                                                                               |            | 495,000        |  |
| 2500 Total Budgetary Resources (sum of SBR lines 2190 and 2490)                                          | 0          | 700,000        |  |

#### **SF133: REPORTING ON BUDGET EXECUTIONS AND BUDGETARY RESOURCES AND BUDGET PROGRAM & FINANCING (P&F) SCHEDULE YEAR 2**

|                                                                          | Agency (030) |     | DOL(016)  |           |
|--------------------------------------------------------------------------|--------------|-----|-----------|-----------|
| BUDGETARY RESOURCES                                                      | SF 133       | P&F | SF133     | P&F       |
| All Accounts:                                                            |              |     |           |           |
| 0900 Total New Obligations (490200E)                                     | N/A          | 0   | N/A       | 205,000   |
| Unobligated Balance                                                      |              |     |           |           |
| 1000 Unobligated Balances Brought Forward 10/1 (420001E)                 |              |     |           |           |
| 1200 Appropriation (411900E)                                             | 0            | 0   |           |           |
| 1800 Spending Authority from Offsetting Collections (Mandatory) (425200) |              |     | 700,000   | 700,000   |
| 1801Change in Uncollected Customer Payments from Federal Sources         |              |     |           |           |
| 1910 Total budgetary resources (calc. line 1800-1842)                    |              |     | 700,000   | N/A       |
| 1930 Total budgetary resources available (calc. line 1800)               |              |     | N/A       | 700,000   |
| STATUS OF BUDGETARY RESOURCES                                            |              |     |           |           |
| 2102 Reimbursable<br>( 490200)                                           |              |     | 205,000   | N/A       |
|                                                                          | 0            |     |           |           |
| 2104<br>Reimbursable Obligations<br>(total)                              |              |     | 205,000   | N/A       |
|                                                                          |              |     |           |           |
| Unobligated balance:                                                     |              |     |           |           |
| 2201 Available in the Current Period (461000)                            |              |     | 495,000   | N/A       |
| 2403 Other                                                               |              |     | 0         | N/A       |
| 2500 Total budgetary resources<br>(equals line 1910)                     |              |     | 700,000   | N/A       |
| CHANGE IN OBLIGATED BALANCE                                              |              |     |           |           |
| Changes in obligated balance during the year:                            |              |     |           |           |
| 3010 Obligations incurred, unexpired accounts (490200E)                  | 0            | 0   | 205,000   | 205,000   |
| 3020 Outlays (gross) (-) (490200E)<br>Uncollected Payments               |              |     | (205,000) | (205,000) |
| 3090 Uncollected Payments from Federal Sources (422100E)                 |              |     | 0         | 0         |
| 3100 Obligated balance, start of<br>year                                 |              |     | 0         | 0         |
| 3200 Obligated balance, end of year (calc. lines 3010<br>and 3020)       |              |     | 0         | 0         |
| BUDGET AUTHORITY AND OUTLAYS, NET                                        |              |     |           |           |
| Mandatory:                                                               |              |     |           |           |
| Gross budget authority and outlays:                                      |              |     |           |           |
| 4090 Budget authority gross (calc. lines 1800)                           |              |     | 700,000   | 700,000   |

| 4100 Outlays<br>from new mandatory authority<br>(490200)                                |   |   | 205,000   | 205,000   |
|-----------------------------------------------------------------------------------------|---|---|-----------|-----------|
| 4110<br>Total outlays, gross (calc. line 4100)                                          |   |   | 205,000   | 205,000   |
| 4120 Offsets against gross budget authority and outlays<br>(425200) (-)                 |   |   | (700,000) | (700,000) |
| 4140 Change in Uncollected Customer Payments from Federal sources (Unexpired)           |   |   | 0         | 0         |
| 4160 Budget authority, net (mandatory) (Cal line 4090 and 4120, 4140)                   |   |   | 0         | 0         |
| 4170 Outlays, net (mandatory) (Calc line 4110+ 4120 through 4124)                       |   |   | (495,000) | (495,000) |
| Budget authority and outlays, net (total):                                              |   |   |           |           |
| 4180 Budget authority, net (discretionary and mandatory) (Sum of line 4070<br>and 4160) |   |   | 0         | 0         |
| 4190 Outlays, net (discretionary and mandatory) (calc. line 4080<br>and 4170)           | 0 | 0 | (495,000) | (495,000) |

### **FECA Calculations Provided by DOL for 20X3 Calculation Table:**

| Funded/Unfunded FECA Liability/FECA                  | Chargeback        | Amounts | Funded/Unfunded FECA Expense/FECA       | Chargeback        | Amounts |
|------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Receivable                                           | Period or FY      |         | Revenue                                 | Period or FY      |         |
| Year X1                                              |                   |         | Year X1                                 |                   |         |
| Annual Chargeback                                    | 07/01/X0-06/30/X1 | 0       | Annual Chargeback                       | 07/01/X0-06/30/X1 | 0       |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Total Unfunded Liability\<br>Receivable Year X1      | 10/01/X0-09/30/X1 | 0       | Total Unfunded FECA Exp/Revenue Year X1 | 10/01/X0-09/30/X1 | 0       |
| Cumulative Unfunded Liability\<br>Receivable Year X1 | 10/01/X0-09/30/X1 | 0       |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X2                                              |                   |         | Year X2                                 |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Quarter 1, Year X2 10/01/X1-12/31/X1                 |                   | 60,000  | Quarter 1, Year X2 10/01/X1-12/31/X1    |                   | 60,000  |
| Quarter 2, Year X2 01/01/X2-03/31/X2                 |                   | 70,000  | Quarter 2, Year X2 01/01/X2-03/31/X2    |                   | 70,000  |
| Quarter 3, Year X2 04/01/X2-06/30/X2                 |                   | 40,000  | Quarter 3, Year X2 04/01/X2-06/30/X2    |                   | 40,000  |
| Annual Chargeback                                    | 07/01/X1-06/30/X2 | 170,000 | Annual Chargeback                       | 07/01/X1-06/30/X2 | 170,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Total Unfunded Liability\<br>Receivable Year X2      | 10/01/X1-09/30/X2 | 205,000 | Total Unfunded FECA Exp/Revenue Year X2 | 10/01/X1-09/30/X2 | 205,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X2 | 10/01/X0-09/30/X2 | 205,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X3                                              |                   |         | Year X3                                 |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Quarter 1, Year X3 10/01/X2-12/31/X2                 |                   | 45,000  | Quarter 1, Year X3 10/01/X2-12/31/X2    |                   | 45,000  |
| Quarter 2, Year X3 01/01/X3-03/31/X3                 |                   | 60,000  | Quarter 2, Year X3 01/01/X3-03/31/X3    |                   | 60,000  |
| Quarter 3, Year X3 04/01/X3-06/30/X3                 |                   | 50,000  | Quarter 3, Year X3 04/01/X3-06/30/X3    |                   | 50,000  |
| Annual Chargeback                                    | 07/01/X2-06/30/X3 | 190,000 | Annual Chargeback                       | 07/01/X2-06/30/X3 | 190,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X3 07/01/X3-09/30/X3                 |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |
| Total Unfunded Liability\<br>Receivable Year X3      | 10/01/X2-09/30/X3 | 210,000 | Total Unfunded FECA Exp/Revenue Year X3 | 10/01/X2-09/30/X3 | 210,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X3 | 10/01/X0-09/30/X3 | 415,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X4                                              |                   |         | Year X4                                 |                   |         |

| Quarter 4, Year X3 07/01/X3-09/30/X3                     |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |
|----------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Quarter 1, Year X4 10/01/X3-12/31/X3                     |                   | 50,000  | Quarter 1, Year X4 10/01/X3-12/31/X3    |                   | 50,000  |
| Quarter 2, Year X4 01/01/X4-03/31/X4                     |                   | 65,000  | Quarter 2, Year X4 01/01/X4-03/31/X4    |                   | 65,000  |
| Quarter 3, Year X4 04/01/X4-06/30/X4                     |                   | 80,000  | Quarter 3, Year X4 04/01/X4-06/30/X4    |                   | 80,000  |
| Annual<br>Chargeback                                     | 07/01/X3-06/30/X4 | 250,000 | Annual Chargeback                       | 07/01/X3-06/30/X4 | 250,000 |
|                                                          |                   |         |                                         |                   |         |
| Quarter 4, Year X4 07/01/X4-09/30/X4                     |                   | 45,000  | Quarter 4, Year X4 07/01/X4-09/30/X4    |                   | 45,000  |
| Total Unfunded Liability\<br>Receivable Year X4          | 10/01/X3-09/30/X4 | 240,000 | Total Unfunded FECA Exp/Revenue Year X4 | 10/01/X3-09/30/X4 | 240,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X4     | 10/01/X0-09/30/X4 | 485,000 | Net Unfunded FECA Exp/Revenue Year X4   | 10/01/X3-09/30/X4 | 70,000  |
| +205,000 + 210,000 +240,000 = 655,000 -170,000 = 485,000 |                   |         | +240,000 –<br>170,000 =<br>70,000       |                   |         |
| Total Funded Liability\<br>Receivable Year X4            | 10/01/X1-09/30/X2 | 170,000 | Total Funded FECA Exp/Revenue Year X4   | 10/01/X1-09/30/X2 | 170,000 |

**Year 3**

1) DOL receives apportionment and allotment on unobligated balance carried forward from PY. Assume it is available for obligation.

| Agency (030) Transaction                 | TC   | DOL (016 1521) Transaction                                                                                                                                  | TC           |
|------------------------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Budgetary<br>None<br>Proprietary<br>None | B422 | Budgetary<br>445000 Unapportioned Authority<br>495,000<br>451000 Apportionment<br>495,000<br>451000 Apportionment<br>495,000<br>461000 Allotment<br>495,000 | A116<br>A120 |
|                                          |      | Proprietary<br>None                                                                                                                                         |              |

2) DOL pays workers' compensation to employees of agency 030 from Qtr 1, Year 3(10/1/X2-12/31/X2).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |        |      |
|--------------------------|-------------|---------------------------------------------|--------|--------|------|
|                          | Code        |                                             |        |        |      |
| Budgetary                |             | Budgetary                                   |        |        |      |
| None                     |             | 461000 Allotment                            | 45,000 |        | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd |        | 45,000 | B110 |
| Proprietary              |             |                                             |        |        |      |
| None                     |             | Proprietary                                 |        |        |      |
|                          |             | 640000(N)<br>Benefit expense                | 45,000 |        |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  |        | 45,000 |      |

3) DOL notifies agency 030 of \$45,000 which reflects its workers' compensation paid out during Qtr 1, Year 3(10/1/X2-12/31/X2). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |  |  |  |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|--|--|--|
| Budgetary                                                             |      | Budgetary                                                 |      |  |  |  |
| None                                                                  |      | None                                                      | C421 |  |  |  |
| Proprietary                                                           |      |                                                           |      |  |  |  |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                               |      |  |  |  |
| Requiring Current-Year Budget Authority (Unobligated)<br>45,000       | B422 | 132100(F030) Unfunded Employee Benefit Contrib Rec 45,000 |      |  |  |  |
| 222500(F016) Unfunded FECA Liability<br>45,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>45,000   |      |  |  |  |

4) DOL pays workers' compensation to employees of agency 030 from Qtr 2, Year 3(01/01/X3-03/31/X3).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |      |
|--------------------------|-------------|---------------------------------------------|--------|------|
|                          | Code        |                                             |        |      |
| Budgetary                |             | Budgetary                                   |        |      |
| None                     |             | 461000 Allotment                            | 60,000 | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd | 60,000 | B110 |
| Proprietary              |             | Proprietary                                 |        |      |
| None                     |             | 640000(N)<br>Benefit expense                | 60,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  | 60,000 |      |

5) DOL notifies agency 030 of \$60,000 which reflects its workers' compensation paid out during Qtr 2, Year 3(01/01/X3-03/31/X3). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>60,000       | B422 | 132100(F030) Unfunded Employee Benefit Contrib Rec 60,000 |      |
| 222500(F016) Unfunded FECA Liability<br>60,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>60,000   |      |

6) DOL pays workers' compensation to employees of agency 030 from Qtr 3, Year 3(04/01/X3-06/30/X3).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |      |
|--------------------------|-------------|---------------------------------------------|--------|------|
|                          | Code        |                                             |        |      |
| Budgetary                |             | Budgetary                                   |        |      |
| None                     |             | 461000 Allotment                            | 50,000 | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd | 50,000 | B110 |
| Proprietary              |             | Proprietary                                 |        |      |
| None                     |             | 640000(N) Benefit expense                   | 50,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  | 50,000 |      |

7) DOL notifies agency 030 of \$50,000 which reflects its workers' compensation paid out during Qtr 3, Year 3(04/01/X3-06/30/X3). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              |        | TC   | DOL (016 1521) Transaction                                |        | TC   |
|-----------------------------------------------------------------------|--------|------|-----------------------------------------------------------|--------|------|
| Budgetary                                                             |        |      | Budgetary                                                 |        |      |
| None                                                                  |        |      | None                                                      |        | C421 |
| Proprietary                                                           |        |      |                                                           |        |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |        | B422 | Proprietary                                               |        |      |
| Requiring Current-Year Budget Authority (Unobligated)                 | 50,000 |      | 132100(F030) Unfunded Employee Benefit Contrib Rec 50,000 |        |      |
| 222500(F016) Unfunded FECA Liability                                  | 50,000 |      | 540500(F030) Unfunded Benefit Program Revenue             | 50,000 |      |

8) Before 8/15/X3, the Department of Labor issues FECA annual chargeback bill (7/1/X2-6/30/X3) to agency 030 for the actual amount of workers' compensation DOL has paid on behalf of agency 030 from 7/1/X2-6/30/X3. No accounting entry is needed when the annual chargeback is sent to the agencies. Both Agency 030 and DOL have already recorded their unfunded liability/receivable and unfunded expense/revenue when the quarterly chargebacks were sent at each quarter. Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the following quarter. Assume for illustration purpose the sum of the quarterly amounts and the annual chargeback amounts are equal. Approximately after 15 months (fiscal year 20X5), agency 030 receives funding to reimburse DOL.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

**Note:** Any agency that identifies a discrepancy on their chargeback bill should communicate the need for the adjustment to DOL. Once the validity of the adjustment is confirmed, DOL will make the correction to its records which will then be reflected on the next Chargeback bill. No adjusting entries should be made preemptively on the part of the agency; otherwise, the correction will be reflected twice on that agency's financial statements.

9) DOL pays workers' compensation claim of \$55,000 to agency 030's employees from Qtr 4, Year 3(7/1/X3-9/30/X3).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |      |
|--------------------------|-------------|---------------------------------------------|--------|------|
|                          | Code        |                                             |        |      |
| Budgetary                |             | Budgetary                                   |        |      |
| None                     |             | 461000 Allotment                            | 55,000 | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd | 55,000 | B110 |
| Proprietary              | B422        |                                             |        |      |
| None                     |             | Proprietary                                 |        |      |
|                          |             | 640000(N)<br>Benefit expense                | 55,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  | 55,000 |      |

10) DOL notifies agency 030 of \$55,000 which reflects its workers' compensation paid out during Qtr 4, Year 3(7/1/X3-9/30/X3). Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the 4th quarter. Assume there are no differences. DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>55,000       | B422 | 132100(F030) Unfunded Employee Benefit Contrib Rec 55,000 |      |
| 222500(F016) Unfunded FECA Liability<br>55,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>55,000   |      |

11) Agency 030 submits annual budget estimates for the fiscal year beginning in the next calendar year to request for an appropriation for unfunded FECA cost.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

12) Department of Labor provides FECA actuarial liability to agency 030. This entry is made at the Fiscal-Year-end only and there is no budgetary impact.

| Agency (030) Transaction                  |           | TC   | DOL (016 1521) Transaction | TC |
|-------------------------------------------|-----------|------|----------------------------|----|
| Budgetary                                 |           |      | Budgetary                  |    |
| None                                      |           |      | None                       |    |
|                                           |           |      |                            |    |
| Proprietary                               |           |      | Proprietary                |    |
| 760000 (N) Changes in Actuarial Liability | 2,500,000 | B426 | None                       |    |
| 265000 (N) Actuarial FECA Liability       | 2,500,000 |      |                            |    |

#### **PRE-CLOSING TRIAL BALANCE YEAR 3**

| Agency (030)                             |           | DOL (016) |                                                    |         |         |  |
|------------------------------------------|-----------|-----------|----------------------------------------------------|---------|---------|--|
| Budgetary                                | DR        | CR        | Budgetary                                          | DR      | CR      |  |
| 420100<br>Total Actual Resource Realized | 0         |           | 420100<br>Total Actual Resources-Collected         | 495,000 |         |  |
| -<br>Collection                          |           |           |                                                    |         |         |  |
| 445000 Unapportioned Authority           |           | 0         | 461000 Allotment                                   |         | 285,000 |  |
|                                          | 0         | 0         | 490200 Delivered Orders -<br>Pd                    |         | 210,000 |  |
| TOTALS                                   |           |           |                                                    |         |         |  |
|                                          |           |           | TOTALS                                             | 495,000 | 495,000 |  |
|                                          |           |           |                                                    |         |         |  |
|                                          |           |           |                                                    |         |         |  |
|                                          |           |           |                                                    |         |         |  |
| Proprietary                              |           |           | Proprietary                                        |         |         |  |
|                                          |           |           | 101000(G099)<br>Fund Balance with Treasury         | 285,000 |         |  |
| 222500(F016) Unfunded FECA Liability     |           | 415,000   | 1321(F030) Unfunded Employee Benefit Contributions | 415,000 |         |  |
|                                          |           |           | Receivable                                         |         |         |  |
| 265000N Actuarial FECA Liability         |           | 5,500,000 | 331000 Cumulative Results of Operations            |         | 700,000 |  |
| 331000 Cumulative Results of Operations  | 3,205,000 |           | 5405(F030) Unfunded Benefit Program revenue        |         | 210,000 |  |
| 685000(F016) Employer Contributions to   | 210,000   |           | 640000N Benefits Expense                           | 210,000 |         |  |
| Employee Benefit Programs Not Requiring  |           |           |                                                    |         |         |  |
| Current-Year Budget Authority            |           |           |                                                    |         |         |  |
| (Unobligated)                            |           |           |                                                    |         |         |  |
| 760000N Changes in Actuarial Liability   | 2,500,000 |           |                                                    |         |         |  |
|                                          |           |           |                                                    |         |         |  |
| TOTALS                                   | 5,915,000 | 5,915,000 | TOTALS                                             | 910,000 | 910,000 |  |

#### **CLOSING ENTRIES FOR END OF YEAR 3**

**C1. To record the closing of revenue, expense, and other financing source accounts to cumulative results of operations.**

| Agency (030)                                 | DOL (016) |           |      |                                            |         |         |      |
|----------------------------------------------|-----------|-----------|------|--------------------------------------------|---------|---------|------|
| USSGL Account                                | Debit     | Credit    | TC   |                                            | Debit   | Credit  | TC   |
| Budgetary                                    |           |           |      | Budgetary                                  |         |         |      |
| None                                         |           |           |      | None                                       |         |         |      |
|                                              |           |           |      |                                            |         |         |      |
| Proprietary                                  |           |           |      | Proprietary                                |         |         |      |
| 331000<br>Cumulative Results of Operations   | 2,500,000 |           | F340 | 540500(F030)<br>Unfunded Benefit           | 210,000 |         | F336 |
| 760000<br>(N) Changes in Actuarial Liability |           | 2,500,000 |      | Program Revenue                            |         |         |      |
|                                              |           |           |      | 331000<br>Cumulative Results of Operations | 0       |         |      |
| 331000<br>Cumulative Results of Operations   | 210,000   |           | F336 | 640000(N)<br>Benefit Expense               |         | 210,000 |      |
| 685000<br>(F016) Employer Contributions to   |           | 210,000   |      |                                            |         |         |      |
| Employee Benefit Programs Not Requiring      |           |           |      |                                            |         |         |      |
| Current-Year Budget Authority (Unobligated)  |           |           |      |                                            |         |         |      |

**C2. To record the closing of unobligated balance to no year funds.** 

| Debit |         |         |
|-------|---------|---------|
|       | Credit  | TC      |
|       |         |         |
|       |         | F308    |
|       |         |         |
|       |         |         |
|       |         |         |
|       |         |         |
|       | 285,000 | 285,000 |

**C3. To record the closing of paid delivered orders to total actual resources.** 

| Agency (030)                             |       |        | DOL (016) |                                                                                                                             |         |         |      |
|------------------------------------------|-------|--------|-----------|-----------------------------------------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account                            | Debit | Credit | TC        |                                                                                                                             | Debit   | Credit  | TC   |
| Budgetary<br>None<br>Proprietary<br>None |       |        |           | Budgetary<br>490200<br>Delivered Orders-Obligations Pd<br>420100<br>Total Actual Resources-Collected<br>Proprietary<br>None | 210,000 | 210,000 | F314 |

#### **POST-CLOSING TRIAL BALANCE YEAR 3**

| Agency (030)                            |           |           | DOL (016)                                  |         |         |  |
|-----------------------------------------|-----------|-----------|--------------------------------------------|---------|---------|--|
| Budgetary                               | DR        | CR        | Budgetary                                  | DR      | CR      |  |
| 420100 Total Actual Resource Realized - | 0         |           | 420100 Total Actual Resources-Collected    | 285,000 |         |  |
| Collection                              |           |           |                                            |         |         |  |
| 445000 Unapportioned Authority          |           | 0         | 445000 Unapportioned Authority             |         | 285,000 |  |
|                                         |           |           | TOTALS                                     | 285,000 | 285,000 |  |
|                                         |           |           |                                            |         |         |  |
| Proprietary                             |           |           | Proprietary                                |         |         |  |
|                                         |           |           | 101000(G099)<br>Fund Balance with Treasury | 285,000 |         |  |
| 222500(F016) Unfunded FECA Liability    |           | 415,000   | 132100(F030) Unfunded Employee Benefit     | 415,000 |         |  |
|                                         |           |           | Contributions Receivable                   |         |         |  |
| 265000N Actuarial FECA Liability        |           | 5,500,000 | 331000 Cumulative Results of Operations    |         | 700,000 |  |
| 331000 Cumulative Results of Operations | 5,915,000 |           |                                            |         |         |  |
|                                         |           |           |                                            |         |         |  |
|                                         |           |           |                                            |         |         |  |
|                                         |           |           |                                            |         |         |  |
| TOTALS                                  | 5,915,000 | 5,915,000 | TOTALS                                     | 700,000 | 700,000 |  |

#### **BALANCE SHEET YEAR 3**

|                                                                         | Agency (030) | DOL(016) |
|-------------------------------------------------------------------------|--------------|----------|
| Assets                                                                  |              |          |
| Intragovernmental<br>1. Fund Balance With Treasury (101000)             |              | 285,000  |
| 3. Accounts Receivable (132100E)                                        | 0            | 415,000  |
| 6.<br>Total Intragovernmental                                           |              | 700,000  |
| 15. Total Assets                                                        | 0            | 700,000  |
| Liabilities                                                             |              |          |
| Intragovernmental                                                       |              |          |
| 17 Accounts Payable (222500E)                                           | 415,000      |          |
| 20 Total Intragovernmental                                              | 415,000      |          |
| Liabilities with Public                                                 |              |          |
| 24. Federal Employee and Veteran Benefits (265000)                      | 5,500,000    |          |
| 28 Total Liabilities                                                    | 5,915,000    |          |
| Net Position                                                            |              |          |
| 31. Unexpended Appropriation –<br>Other Funds                           | 0            | 0        |
| 33. Cumulative Results of Operations-Other Funds(6400000,685000,760000) | (5,915,000)  | 700,000  |
| 34. Total Net Position                                                  | (5,915,000)  | 700,000  |
| 35. Total Liabilities and Net Position                                  | 0            | 700,000  |

#### **STATEMENT OF NET COST YEAR 3**

|    | Program Costs                                      | Agency (030) | DOL(016)  |
|----|----------------------------------------------------|--------------|-----------|
|    | Program A:                                         |              |           |
|    | 1. Gross Cost :                                    |              |           |
|    | (685000E, 640000N)                                 | 210,000      | 210,000   |
|    | (760000E)                                          | 2,500,000    |           |
|    | 2. Less: Earned Income(540500E)                    | 0            | (210,000) |
|    | 3. Net Program Costs                               | 2,710,000    | 0         |
| 5. | Net Program Costs including Assumption Changes:    | 2,710,000    | 0         |
|    |                                                    |              |           |
| 6. | Costs Not Assigned to Programs(685000,640000)      |              |           |
| 7. | Less: Earned Revenues Not Attributable to Programs |              |           |
| 8. | Net Cost of Operations                             | 2,710,000    | 0         |

### **USSGL 2108 YEAR-END CLOSING STATEMENT YEAR 3**

|   | DOL(016)          |
|---|-------------------|
|   | 285,000           |
|   |                   |
| 0 | 285,000           |
|   | Agency (030)<br>0 |

### **Statement of Changes In Net Position YEAR 3**

| Cumulative Results of Operations<br>1. Beginning Balance<br>2. Adjustments | Agency (030)<br>(3,205,000) | DOL(016)<br>700,000 |
|----------------------------------------------------------------------------|-----------------------------|---------------------|
| 3. Beginning Balances, as Adjusted                                         | (3,205,000)                 | 700,000             |
| Budgetary Financing Sources                                                |                             |                     |
| 4. Other Adjustments                                                       |                             |                     |
| 5. Appropriations Used                                                     |                             | 0                   |
| 6. Nonexchange Revenue                                                     |                             |                     |
| 9. Other                                                                   |                             |                     |
| Other Financing Sources:<br>12. Imputed Financing                          |                             |                     |
| 13. Other                                                                  |                             |                     |
| 14. Total Financing Sources                                                |                             |                     |
| 15. Net Cost of Operations                                                 | (2,710,000<br>)             | 0                   |
| 16. Net Change                                                             | (2,710,000)                 |                     |
| 17. Cumulative Results of Operations                                       | (5,915,000)                 | 700,000             |
| Unexpended Appropriations                                                  |                             |                     |
| 18. Beginning Balance                                                      | 0                           |                     |
| 19. Adjustments                                                            |                             |                     |
| 20. Beginning Balance, as adjusted                                         | 0                           |                     |
| Budgetary Financing Sources                                                |                             |                     |
| 21. Appropriations Received (310100)                                       |                             |                     |
| 22. Appropriations Transferred in/out                                      |                             |                     |
| 23. Other Adjustments                                                      |                             |                     |
| 24. Appropriations Used (310700)                                           |                             |                     |
| 25. Total Budgetary Financing Sources                                      |                             |                     |
| 26. Total Unexpended Appropriations                                        |                             |                     |
| 27. Net Position                                                           | (5,915,000)                 | 700,000             |

### **STATEMENT OF BUDGETARY RESOURCES**

|                                                                                     | TAFS (030) | TAFS (16 1521) |
|-------------------------------------------------------------------------------------|------------|----------------|
| BUDGETARY RESOURCES                                                                 |            |                |
| 1000<br>Unobligated balance<br>brought forward, October (420100B,)                  | 0          | 495,000        |
| 1890 Spending Authority from Offsetting Collection                                  | 0          | 0              |
| 1910 Total Budgetary Resources (sum of SBR lines 1000, 1020, 1021, 1043, 1290,      |            |                |
| 1490, 1690, and 1890.)                                                              | 0          | 495,000        |
| STATUS OF BUDGETARY RESOURCES                                                       |            |                |
| 2190 Obligation Incurred (490200E)                                                  | 0          | 210,000        |
| 2204 Apportioned (461000E)                                                          | 0          | 285,000        |
| 2490 Unobligated balance brought forward, end of year (sum of SBR lines 2204, 2304, |            |                |
| and 2404.)                                                                          | 0          | 285,000        |
| 2500 Total Budgetary Resources (sum of SBR lines 2190 and 2490)                     | 0          | 495,000        |

#### **SF133: REPORTING ON BUDGET EXECUTIONS AND BUDGETARY RESOURCES AND BUDGET PROGRAM & FINANCING (P&F) SCHEDULE YEAR 3**

|                                                                              | Agency (030) |     | DOL(016)  |           |
|------------------------------------------------------------------------------|--------------|-----|-----------|-----------|
| BUDGETARY RESOURCES                                                          | SF 133       | P&F | SF133     | P&F       |
| All Accounts:                                                                |              |     |           |           |
| 0900 Total New Obligations (490200E)                                         |              |     | N/A       | 210,000   |
| Unobligated Balance                                                          |              |     | 495,000   | 495,000   |
| 1000 Unobligated Balances Brought Forward 10/1 (420100E)                     |              |     |           |           |
| 1200 Appropriation (411900E)                                                 |              |     | 0         | 0         |
| 1800 Spending<br>Authority from Offsetting Collections (Mandatory) (425200)  |              |     | 0         | 0         |
| 1801Change in Uncollected Customer Payments from Federal Sources (422100E-B) |              |     | 0         | 0         |
| 1910 Total budgetary resources (calc. line 1800-1842)                        |              |     | 495,000   | N/A       |
| 1930 Total budgetary resources available (calc. line 1000,1800)              |              |     | N/A       | 495,000   |
|                                                                              |              |     |           |           |
| STATUS OF BUDGETARY RESOURCES                                                |              |     |           |           |
| 2102 Reimbursable (490200)                                                   |              |     | 210,000   | N/A       |
| 2104 Reimbursable Obligations (total)                                        |              |     | 210,000   | N/A       |
|                                                                              |              |     |           |           |
| Unobligated balance:                                                         |              |     | 285,000   | N/A       |
| 2201 Available in Current pd (461000)                                        |              |     |           |           |
| 2500 Total budgetary resources                                               |              |     | 495,000   | N/A       |
| CHANGE IN OBLIGATED BALANCE                                                  |              |     |           |           |
| Changes in obligated balance during the year:                                |              |     |           |           |
| 3010 Obligations incurred, unexpired accounts (490200E)                      |              |     | 210,000   | 210,000   |
| 3020 Outlays (gross) (-) (490200E)                                           |              |     | (210,000) | (210,000) |
| 3060 Uncollected Payments, Fed Sources brought forward Oct 1(422100B)        |              |     | 0         | 0         |
| 3070 Change in Uncollected Payments, Fed Sources, unexpired accounts (+or-)  |              |     | (210,000) | (210,000) |
| 3090 Uncollected Payments from Federal Sources (422100E) (-)                 |              |     | 0         | 0         |
| 3100 Obligated balance, start of year (calc. lines)                          |              |     | (205,000) | (205,000) |
| 3200 Obligated balance, end of year (calc. lines)                            |              |     | (415,000) | (415,000) |
| BUDGET AUTHORITY AND OUTLAYS, NET                                            |              |     |           |           |
| Mandatory:                                                                   |              |     |           |           |
| Gross budget authority and outlays:                                          |              |     |           |           |

| 4090 Budget authority gross (calc. lines 1800-1821)                                  | 0       | 0       |
|--------------------------------------------------------------------------------------|---------|---------|
| 4100 Outlays from mandatory balances (490200)                                        | 210,000 | 210,000 |
| 4110 Total outlays, gross (calc. line 4100)                                          | 210,000 | 210,000 |
| 4120 Offsets against gross budget authority and outlays (425200) (-)                 | 0       | 0       |
| 4140 Change in Uncollected Customer Payments from Federal sources (Unexpired)        | 0       | 0       |
| 4160 Budget authority, net (mandatory) (Cal line 4090 and 4120)                      | 210,000 | 210,000 |
| 4170 Outlays, net (mandatory) (Calc line 4110+ 4120 through 4124)                    |         |         |
|                                                                                      | 210,000 | 210,000 |
| Budget authority and outlays, net (total):                                           | 210,000 | 210,000 |
| 4180 Budget authority, net (discretionary and mandatory) (Sum of line 4070 and 4160) |         |         |
| 4190 Outlays, net (discretionary and mandatory) (calc. line 4080 and 4170)           | 210,000 | 210,000 |

# **FECA Calculations Provided by DOL for 20X4**

### **Calculation Table:**

| Funded/Unfunded FECA Liability/FECA                  | Chargeback        | Amounts | Funded/Unfunded FECA Expense/FECA       | Chargeback        | Amounts |
|------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Receivable                                           | Period or FY      |         | Revenue                                 | Period or FY      |         |
| Year X1                                              |                   |         | Year X1                                 |                   |         |
| Annual Chargeback                                    | 07/01/X0-06/30/X1 | 0       | Annual Chargeback                       | 07/01/X0-06/30/X1 | 0       |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Total Unfunded Liability\<br>Receivable Year X1      | 10/01/X0-09/30/X1 | 0       | Total Unfunded FECA Exp/Revenue Year X1 | 10/01/X0-09/30/X1 | 0       |
| Cumulative Unfunded Liability\<br>Receivable Year X1 | 10/01/X0-09/30/X1 | 0       |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X2                                              |                   |         | Year X2                                 |                   |         |
| Quarter 4, Year X1 07/01/X1-09/30/X1                 |                   | 0       | Quarter 4, Year X1 07/01/X1-09/30/X1    |                   | 0       |
| Quarter 1, Year X2 10/01/X1-12/31/X1                 |                   | 60,000  | Quarter 1,<br>Year X2 10/01/X1-12/31/X1 |                   | 60,000  |
| Quarter 2, Year X2 01/01/X2-03/31/X2                 |                   | 70,000  | Quarter 2, Year X2 01/01/X2-03/31/X2    |                   | 70,000  |
| Quarter 3, Year X2 04/01/X2-06/30/X2                 |                   | 40,000  | Quarter 3, Year X2 04/01/X2-06/30/X2    |                   | 40,000  |
| Annual Chargeback                                    | 07/01/X1-06/30/X2 | 170,000 | Annual Chargeback                       | 07/01/X1-06/30/X2 | 170,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Total Unfunded Liability\<br>Receivable Year X2      | 10/01/X1-09/30/X2 | 205,000 | Total Unfunded FECA Exp/Revenue Year X2 | 10/01/X1-09/30/X2 | 205,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X2 | 10/01/X0-09/30/X2 | 205,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X3                                              |                   |         | Year X3                                 |                   |         |
| Quarter 4, Year X2 07/01/X2-09/30/X2                 |                   | 35,000  | Quarter 4, Year X2 07/01/X2-09/30/X2    |                   | 35,000  |
| Quarter 1, Year X3 10/01/X2-12/31/X2                 |                   | 45,000  | Quarter 1, Year X3 10/01/X2-12/31/X2    |                   | 45,000  |
| Quarter 2, Year X3 01/01/X3-03/31/X3                 |                   | 60,000  | Quarter 2, Year X3 01/01/X3-03/31/X3    |                   | 60,000  |
| Quarter 3, Year X3 04/01/X3-06/30/X3                 |                   | 50,000  | Quarter 3, Year X3 04/01/X3-06/30/X3    |                   | 50,000  |
| Annual Chargeback                                    | 07/01/X2-06/30/X3 | 190,000 | Annual Chargeback                       | 07/01/X2-06/30/X3 | 190,000 |
|                                                      |                   |         |                                         |                   |         |
| Quarter 4, Year X3 07/01/X3-09/30/X3                 |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |
| Total Unfunded Liability\<br>Receivable Year X3      | 10/01/X2-09/30/X3 | 210,000 | Total Unfunded FECA Exp/Revenue Year X3 | 10/01/X2-09/30/X3 | 210,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X3 | 10/01/X0-09/30/X3 | 415,000 |                                         |                   |         |
|                                                      |                   |         |                                         |                   |         |
| Year X4                                              |                   |         | Year X4                                 |                   |         |
| Quarter 4, Year X3 07/01/X3-09/30/X3                 |                   | 55,000  | Quarter 4, Year X3 07/01/X3-09/30/X3    |                   | 55,000  |

| Quarter 1, Year X4 10/01/X3-12/31/X3                     |                   | 50,000  | Quarter 1, Year X4 10/01/X3-12/31/X3    |                   | 50,000  |
|----------------------------------------------------------|-------------------|---------|-----------------------------------------|-------------------|---------|
| Quarter 2, Year X4 01/01/X4-03/31/X4                     |                   | 65,000  | Quarter 2, Year X4 01/01/X4-03/31/X4    |                   | 65,000  |
| Quarter 3, Year X4 04/01/X4-06/30/X4                     |                   | 80,000  | Quarter 3, Year X4 04/01/X4-06/30/X4    |                   | 80,000  |
| Annual Chargeback                                        | 07/01/X3-06/30/X4 | 250,000 | Annual Chargeback                       | 07/01/X3-06/30/X4 | 250,000 |
|                                                          |                   |         |                                         |                   |         |
| Quarter 4, Year X4 07/01/X4-09/30/X4                     |                   | 45,000  | Quarter 4, Year X4 07/01/X4-09/30/X4    |                   | 45,000  |
| Total Unfunded Liability\<br>Receivable Year X4          | 10/01/X3-09/30/X4 | 240,000 | Total Unfunded FECA Exp/Revenue Year X4 | 10/01/X3-09/30/X4 | 240,000 |
| Cumulative Unfunded Liability\<br>Receivable Year X4     | 10/01/X0-09/30/X4 | 485,000 | Net Unfunded FECA Exp/Revenue Year X4   | 10/01/X3-09/30/X4 | 70,000  |
| +205,000 + 210,000 +240,000 = 655,000 -170,000 = 485,000 |                   |         | +240,000 –<br>170,000 = 70,000          |                   |         |
| Total Funded Liability\<br>Receivable Year X4            | 10/01/X1-09/30/X2 | 170,000 | Total Funded FECA Exp/Revenue Year X4   | 10/01/X1-09/30/X2 | 170,000 |

# **Year 4**

1) DOL receives apportionment and allotment on unobligated balance carried forward from PY. Assume it is available for obligation.

| Agency (030) Transaction                 | TC | DOL (016 1521) Transaction                                                                                      |                                          | TC           |
|------------------------------------------|----|-----------------------------------------------------------------------------------------------------------------|------------------------------------------|--------------|
| Budgetary<br>None<br>Proprietary<br>None |    | Budgetary<br>445000 Unapportioned Authority<br>451000 Apportionment<br>451000 Apportionment<br>461000 Allotment | 700,000<br>700,000<br>700,000<br>700,000 | A116<br>A120 |
|                                          |    | Proprietary<br>None                                                                                             |                                          |              |

2) DOL anticipates reimbursement from agency 030 for 10/01/X3-09/30/X4.

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                                                  |      |  |
|--------------------------|-------------|-----------------------------------------------------------------------------|------|--|
|                          | Code        |                                                                             |      |  |
| Budgetary                |             | Budgetary                                                                   |      |  |
| None                     |             | 421000 Anticipated Reimbursements and Other Income<br>170,000               | A702 |  |
|                          |             | 445000 Unapportioned Authority<br>170,000                                   |      |  |
| Proprietary              |             | 445000 Unapportioned Authority<br>170,000                                   | A118 |  |
| None                     |             | 459000<br>Apportionment –<br>Anticipated Resources –<br>Programs Subject to |      |  |
|                          |             | Apportionment<br>170,000                                                    |      |  |
|                          |             |                                                                             |      |  |
|                          |             | Proprietary                                                                 |      |  |
|                          |             | None                                                                        |      |  |

3) Agency 030 receives its appropriation and is able to pay FECA chargeback from 7/1/X1 – 6/30/X2, assume Agency 030's appropriation is apportioned and allotted. (Pursuant to the FECA law, once funding is received the FECA bill should be paid within 30 days. FECA bills that are still outstanding after the 30-day period are considered delinquent and should be reflected as a funded liability with a footnote disclosure.)

| Agency (030) Transaction                  |                     | TC   | DOL (016 1521) Transaction | TC |
|-------------------------------------------|---------------------|------|----------------------------|----|
| Budgetary                                 |                     |      | Budgetary                  |    |
| 411900 Other Appropriations Realized      | 170,000             |      | None                       |    |
| 445000 Unapportioned Authority            | 170,000             | A104 |                            |    |
| 445000 Unappropriated Authority           | 170,000             |      |                            |    |
| 451000 Apportionments                     | 170,000             |      | Proprietary                |    |
| 451000 Apportionments                     | 170,000             | A116 | None                       |    |
| 461000 Allotments –<br>Realized Resources | 170,000             |      |                            |    |
|                                           |                     |      |                            |    |
| Proprietary                               |                     | A120 |                            |    |
| 101000(G099) Fund Balance with Treasury   | 170,000             |      |                            |    |
| 310100(G099) Unexpected Appropriations –  | Received<br>170,000 |      |                            |    |
|                                           |                     |      |                            |    |

<span id="page-52-0"></span>4) To reclassify unfunded liability and expense to funded liability and expense[11.](#page-52-0) At this time, the DOL will record a budgetary federal receivable from agency 030. When a unfunded proprietary receivable was recorded by DOL, the paying account did not have budgetary resource to record an obligation to DOL, therefore, DOL should not record a budgetary receivable until the paying account records obligations to DOL (see OMB A11 section 20.4).

| Agency (030) Transaction                                       | TC    | DOL (016 1521) Transaction                                               | TC      |
|----------------------------------------------------------------|-------|--------------------------------------------------------------------------|---------|
| Budgetary                                                      |       | Budgetary                                                                |         |
| 461000 Allotments –<br>Realized Resources<br>170,000           |       | 422100 Unfilled Customer Order without Advance<br>170,000                | A706    |
| 490100 Delivered Orders –<br>Obligations, Unpaid<br>170,000    | E106  | 421000 Anticipated Reimbursements and Other Income<br>170,000            |         |
| Proprietary                                                    |       | 425100 Reimbursements and Other Inc Earned-Receivable 170,000            | A715    |
| 222500 (F016) Unfunded FECA Liability<br>170,000               | B422R | 422100 Unfilled Customer Order without Advance<br>170,000                |         |
| 685000 (F016) Employer Contributions to Employee               |       |                                                                          |         |
| Benefit Programs Not Requiring Current Year Budget Authority   |       | 459000 Apportionment –<br>Anticipated Resources –<br>Programs Subject to | A122    |
| (Unobligated)<br>170,000                                       |       | Apportionment<br>170,000                                                 |         |
|                                                                |       | 461000 Allotments –<br>Realized Resources<br>170,000                     |         |
| 640000 (F016) Benefit Expense<br>170,000                       |       |                                                                          |         |
| 221500 (F016) Other Post Employment Benefits Due               | E106  | Proprietary                                                              |         |
| and Payable<br>170,000                                         |       | 132000(F030) Funded Employment Benefit Contributions                     |         |
|                                                                |       | Receivable<br>170,000                                                    |         |
| 310700(G099)<br>Unexpended Appropriations –<br>Used<br>170,000 |       | 540000(F030) Funded Benefit Program Revenue<br>170,000                   |         |
| 570000(G099)<br>Expended Appropriations                        | B134  |                                                                          |         |
| 170,000                                                        |       |                                                                          |         |
|                                                                |       | 540500(F030) Unfunded Benefit Program Revenue<br>170,000                 | Reverse |
|                                                                |       | 132100(F030) Unfunded Employment Benefit Contributions                   | C421    |
|                                                                |       | Receivable<br>170,000                                                    |         |
|                                                                |       |                                                                          |         |
|                                                                |       |                                                                          |         |

<sup>11</sup> When the agencies receive appropriations to pay DOL for the accrued FECA costs, the unfunded FECA liability and unfunded expense should be reclassified to funded liability and benefit expense.

5) Agency 030 makes the payments to DOL from 7/1/X1 – 6/30/X2.

| Agency (030) Transaction                                                                                                                           | TC   | DOL (016 1521) Transaction                                                                                                                            | TC             |
|----------------------------------------------------------------------------------------------------------------------------------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Budgetary<br>490100 Delivered Orders –<br>Obligations, Unpaid<br>170,000<br>490200 Delivered Orders –<br>Obligations, paid<br>170,000              | B110 | Budgetary<br>425200 Reimbursements and Other Inc Earned-<br>Collected 170,000<br>425100 Reimbursements and Other Inc Earned-Receivable 170,000        | Revise<br>C186 |
| Proprietary<br>221500 (F016) Other Post Employment Benefits Due<br>and Payable<br>170,000<br>101000(G099)<br>Fund Balance with Treasury<br>170,000 |      | Proprietary<br>101000(G099)<br>Fund Balance with Treasury<br>170,000<br>132000(F030) Funded Employment Benefit Contributions<br>Receivable<br>170,000 |                |

6) DOL pays workers' compensation to employees of agency 030 from Qtr 1, Year 4(10/1/X3-12/31/X3).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |        |      |
|--------------------------|-------------|---------------------------------------------|--------|--------|------|
|                          | Code        |                                             |        |        |      |
| Budgetary                |             | Budgetary                                   |        |        |      |
| None                     |             | 461000 Allotment                            | 50,000 |        | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd |        | 50,000 | B110 |
| Proprietary              |             |                                             |        |        |      |
| None                     |             | Proprietary                                 |        |        |      |
|                          |             | 640000(N)<br>Benefit expense                | 50,000 |        |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  |        | 50,000 |      |

7) DOL notifies agency 030 of \$50,000 which reflects its workers' compensation paid out during Qtr 1, Year 4(10/1/X3-12/31/X3). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not |      | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>50,000       | B422 | 132100(F030) Unfunded Employee Benefit Contrib Rec 50,000 |      |
| 222500(F016) Unfunded FECA Liability<br>50,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>50,000   |      |

8) DOL pays workers' compensation to employees of agency 030 from Qtr 2, Year 4(01/01/X4-03/31/X4).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |      |
|--------------------------|-------------|---------------------------------------------|--------|------|
|                          | Code        |                                             |        |      |
| Budgetary                |             | Budgetary                                   |        |      |
| None                     |             | 461000 Allotment                            | 65,000 | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd | 65,000 | B110 |
| Proprietary              |             | Proprietary                                 |        |      |
| None                     |             | 640000(N)<br>Benefit expense                | 65,000 |      |
|                          |             | 101000(G099)<br>Fund Balance with Treasury  | 65,000 |      |

9 DOL notifies agency 030 of \$65,000 which reflects its workers' compensation paid out during Qtr 2, Year 4(01/01/X4-03/31/X4). DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not | B422 | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>65,000       |      | 132100(F030) Unfunded Employee Benefit Contrib Rec 65,000 |      |
| 222500(F016) Unfunded FECA Liability<br>65,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>65,000   |      |

10) DOL pays workers' compensation to employees of agency 030 from Qtr 3, Year 4(04/01/X4-06/30/X4).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                                      |                  |              |
|--------------------------|-------------|-----------------------------------------------------------------|------------------|--------------|
|                          | Code        |                                                                 |                  |              |
| Budgetary                |             | Budgetary                                                       |                  |              |
| None                     |             | 461000 Allotment<br>490200 Delivered Orders –<br>Obligations Pd | 80,000<br>80,000 | E106<br>B110 |
| Proprietary              |             | Proprietary                                                     |                  |              |
| None                     |             | 640000(N)<br>Benefit expense                                    | 80,000           |              |
|                          |             | 101000(G099)<br>Fund Balance with Treasury                      | 80,000           |              |

11) DOL notifies agency 030 of \$80,000 which reflects its workers' compensation paid out during Qtr 3, Year 4(04/01/X4-06/30/X4).. DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not | B422 | Proprietary                                               |      |
| Requiring Current-Year<br>Budget Authority (Unobligated)<br>80,000    |      | 132100(F030) Unfunded Employee Benefit Contrib Rec 80,000 |      |
| 222500(F016) Unfunded FECA Liability<br>80,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>80,000   |      |

12) Before 8/15/X4, the Department of Labor issues FECA annual chargeback bill (7/1/X3-6/30/X4) to agency 030 for the actual amount of workers' compensation DOL has paid on behalf of agency 030 from 7/1/X3 to 6/30/X4. No accounting entry is needed when the annual chargeback is sent to the agencies. Both Agency 030 and DOL have already recorded their unfunded liability/receivable and unfunded expense/revenue when the quarterly chargebacks were sent at each quarter. Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the following quarter. Assume for illustration purpose the sum of the quarterly amounts and the annual chargeback amounts are equal. Approximately after 15 months (fiscal year 20X6), agency 030 receives funding to reimburse DOL.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

**Note:** Any agency that identifies a discrepancy on their chargeback bill should communicate the need for the adjustment to DOL. Once the validity of the adjustment is confirmed, DOL will make the correction to its records which will then be reflected on the next Chargeback bill. No adjusting entries should be made preemptively on the part of the agency; otherwise, the correction will be reflected twice on that agency's financial statements.

13) DOL pays workers' compensation claim of \$45,000 to agency 030's employees from Qtr 4, Year 4(7/1/X4-9/30/X4).

| Agency (030) Transaction | Transaction | DOL (016 1521) Transaction                  |        |        |      |
|--------------------------|-------------|---------------------------------------------|--------|--------|------|
|                          | Code        |                                             |        |        |      |
| Budgetary                |             | Budgetary                                   |        |        |      |
| None                     |             | 461000 Allotment                            | 45,000 |        | E106 |
|                          |             | 490200 Delivered Orders –<br>Obligations Pd |        | 45,000 | B110 |
| Proprietary              | B422        |                                             |        |        |      |
| None                     |             | Proprietary                                 |        |        |      |
|                          |             | 640000(N)<br>Benefit expense                | 45,000 |        |      |
|                          |             | 101000(G099)Fund Balance with Treasury      |        | 45,000 |      |

14) DOL notifies agency 030 of \$45,000 which reflects its workers' compensation paid out during Qtr 4, Year 4(7/1/X4-9/30/X4). Any difference between the actual amount from the annual chargeback and the sum of quarterly chargebacks are adjusted in the 4th quarter. Assume there are no differences. DOL records unfunded FECA receivable and FECA revenue and agency 030 records unfunded FECA liability and FECA expense.

| Agency (030) Transaction                                              | TC   | DOL (016 1521) Transaction                                | TC   |
|-----------------------------------------------------------------------|------|-----------------------------------------------------------|------|
| Budgetary                                                             |      | Budgetary                                                 |      |
| None                                                                  |      | None                                                      | C421 |
| Proprietary                                                           |      |                                                           |      |
| 685000 (F016) Employer Contributions to Employee Benefit Programs Not | B422 | Proprietary                                               |      |
| Requiring Current-Year Budget Authority (Unobligated)<br>45,000       |      | 132100(F030) Unfunded Employee Benefit Contrib Rec 45,000 |      |
| 222500(F016) Unfunded FECA Liability<br>45,000                        |      | 540500(F030) Unfunded Benefit Program Revenue<br>45,000   |      |

15) Agency 030 submits annual budget estimates for the fiscal year beginning in the next calendar year to request for an appropriation for unfunded FECA cost.

| Agency (030) Transaction | TC | DOL (016 1521) Transaction | TC |
|--------------------------|----|----------------------------|----|
| Budgetary                |    | Budgetary                  |    |
| None                     |    | None                       |    |
|                          |    |                            |    |
| Proprietary              |    | Proprietary                |    |
| None                     |    | None                       |    |

16) Department of Labor provides FECA actuarial liability to agency 030. This entry is made at the Fiscal-Year-end only and there is no budgetary impact.

| Agency (030) Transaction                                  | TC   | DOL (016 1521) Transaction | TC |
|-----------------------------------------------------------|------|----------------------------|----|
| Budgetary                                                 |      | Budgetary                  |    |
| None                                                      |      | None                       |    |
|                                                           |      |                            |    |
| Proprietary                                               |      | Proprietary                |    |
| 760000 (N) Changes in Actuarial<br>Liability<br>2,700,000 | B426 | None                       |    |
| 265000 (N) Actuarial FECA Liability<br>2,700,000          |      |                            |    |

### **PRE-CLOSING TRIAL BALANCE**

#### **YEAR 4**

| Agency (030)                             |           |           | DOL (016 1521)                                     |         |         |  |  |  |
|------------------------------------------|-----------|-----------|----------------------------------------------------|---------|---------|--|--|--|
| Budgetary                                | DR        | CR        | Budgetary                                          | DR      | CR      |  |  |  |
| 411900<br>Other Appropriation Realized   | 170,000   |           | 420100<br>Total Actual Resources-Collected         | 285,000 |         |  |  |  |
| 490200 Delivered Orders -<br>Pd          |           | 170,000   | 425200 Reimbursements and Other Income Earned -    | 170,000 |         |  |  |  |
|                                          |           |           | Collections                                        |         |         |  |  |  |
| TOTAL                                    | 170,000   | 170,000   | 461000 Allotment                                   |         | 215,000 |  |  |  |
|                                          |           |           | 490200 Delivered Orders -<br>Pd                    |         | 240,000 |  |  |  |
|                                          |           |           | TOTAL                                              | 455,000 | 455,000 |  |  |  |
| Proprietary                              |           |           | Proprietary                                        |         |         |  |  |  |
| 221500(F016) OPEB Payable                |           | 0         | 101000(G099)<br>Fund Balance with Treasury         | 215,000 |         |  |  |  |
| 222500(F016) Unfunded FECA Liability     |           | 485,000   | 1321(F030) Unfunded Employee Benefit Contributions | 485,000 |         |  |  |  |
|                                          |           |           | Receivable                                         |         |         |  |  |  |
| 265000N Actuarial FECA Liability         |           | 8,200,000 | 331000 Cumulative Results of Operations            |         | 700,000 |  |  |  |
| 310100(G099)<br>Unexpended Appropriation |           | 170,000   | 540000(F030) Funded Benefit Program Revenue        |         | 170,000 |  |  |  |
| –<br>Appr received                       |           |           |                                                    |         |         |  |  |  |
| 310700(G099)<br>Unexpendded              | 170,000   |           | 5405(F030) Unfunded Benefit Program revenue        |         | 70,000  |  |  |  |
| Appropriation –<br>Appr Used             |           |           |                                                    |         |         |  |  |  |
| 331000 Cumulative Results of Operations  | 5,915,000 |           | 640000(N) Benefits Expense                         | 240,000 |         |  |  |  |
| 570000(G099)<br>Appropriation Used       |           | 170,000   |                                                    |         |         |  |  |  |
| 640000(F016) Benefits Expense            | 170,000   |           |                                                    |         |         |  |  |  |
| 685000(F016) Employer Contributions to   | 70,000    |           |                                                    |         |         |  |  |  |
| Employee Benefit Programs Not Requiring  |           |           |                                                    |         |         |  |  |  |
| Current-Year Budget Authority            |           |           |                                                    |         |         |  |  |  |
| (Unobligated)                            |           |           |                                                    |         |         |  |  |  |
| 760000N Changes in Actuarial Liability   | 2,700,000 |           |                                                    |         |         |  |  |  |
|                                          |           |           | TOTAL                                              | 940,000 | 940,000 |  |  |  |
| Total                                    | 8,925,000 | 8,925,000 |                                                    |         |         |  |  |  |

#### **CLOSING ENTRIES FOR END OF YEAR 4**

**C1. To record the closing of revenue, expense, and other financing source accounts to cumulative results of operations.**

| Agency (030)                                                                                                                                                                                                                                                                                                                 | DOL (016 1521)       |                                |              |                                                                                                                                                                                                       |                   |              |      |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|--------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|--------------|------|
| USSGL Account                                                                                                                                                                                                                                                                                                                | Debit                | Credit                         | TC           |                                                                                                                                                                                                       | Debit             | Credit       | TC   |
| Budgetary<br>None                                                                                                                                                                                                                                                                                                            |                      |                                |              | Budgetary<br>None                                                                                                                                                                                     |                   |              |      |
| Proprietary<br>331000<br>Cumulative Results of Operations<br>760000<br>(N) Changes in Actuarial Liability<br>331000 Cumulative Results of Operations<br>685000<br>(F016) Employer Contributions to<br>Employee Benefit Programs Not Requiring<br>Current-Year Budget Authority (Unobligated)<br>640000(F016) Benefit expense | 2,700,000<br>240,000 | 2,700,000<br>70,000<br>170,000 | F340<br>F336 | Proprietary<br>540000(F030)<br>Funded Benefit<br>Program<br>Revenue<br>540500(F030) Unfunded Benefit Program<br>Revenue<br>331000 Cumulative Results of<br>Operations<br>640000(N)<br>Benefit expense | 170,000<br>70,000 | 0<br>240,000 | F336 |
| 570000(G099)<br>Appropriation Used<br>331000<br>Cumulative Results of Operations                                                                                                                                                                                                                                             | 170,000              | 170,000                        |              |                                                                                                                                                                                                       |                   |              |      |

**C2. To record the closing of budgetary resources.** 

| Agency (030)                                                                                                             | DOL (016 1521) |         |      |                                                                                                                                                      |         |         |      |
|--------------------------------------------------------------------------------------------------------------------------|----------------|---------|------|------------------------------------------------------------------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account                                                                                                            | Debit          | Credit  | TC   |                                                                                                                                                      | Debit   | Credit  | TC   |
| Budgetary<br>420100<br>Total Actual Resources-Collected<br>411900<br>Other Appropriation Realized<br>Proprietary<br>None | 170,000        | 170,000 | F302 | Budgetary<br>420100<br>Total Actual Resources<br>Collected<br>425200 Reimbursements and<br>Other Income Earned –<br>Collected<br>Proprietary<br>None | 170,000 | 170,000 | F302 |

**C3. To record the closing of paid undelivered orders to total actual resources.** 

| Agency (030)                                                                                         | DOL (016 1521) |         |      |                                                                                                      |         |         |      |
|------------------------------------------------------------------------------------------------------|----------------|---------|------|------------------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account                                                                                        | Debit          | Credit  | TC   |                                                                                                      | Debit   | Credit  | TC   |
| Budgetary<br>490200<br>Delivered Orders-Obligations Pd<br>420100<br>Total Actual Resources-Collected | 170,000        | 170,000 | F314 | Budgetary<br>490200<br>Delivered Orders-Obligations Pd<br>420100<br>Total Actual Resources-Collected | 240,000 | 240,000 | F314 |
| Proprietary<br>None                                                                                  |                |         |      | Proprietary<br>None                                                                                  |         |         |      |

**C4. To record the closing of unobligated balance to no year fund.**

| Agency (030)                             |       |        | DOL (016 1521) |                                                                                              |         |         |      |
|------------------------------------------|-------|--------|----------------|----------------------------------------------------------------------------------------------|---------|---------|------|
| USSGL Account                            | Debit | Credit | TC             |                                                                                              | Debit   | Credit  | TC   |
| Budgetary<br>None<br>Proprietary<br>None |       |        |                | Budgetary<br>461000<br>Allotment<br>445000<br>Unapportioned Authority<br>Proprietary<br>None | 215,000 | 215,000 | F308 |

**C5. To record the closing of fiscal year activities to unexpended appropriation.**

| Agency (030)                                                                                                                                                                                         |         |              |      | DOL (016 1521)                           |       |        |    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|--------------|------|------------------------------------------|-------|--------|----|
| USSGL Account                                                                                                                                                                                        | Debit   | Credit       | TC   |                                          | Debit | Credit | TC |
| Budgetary<br>310100(G099)<br>Unexpended Appropriation-Appr<br>Received<br>310700(G099)<br>Unexpended Appropriations-Used<br>310000<br>Unexpended Appropriation-<br>Cumulative<br>Proprietary<br>None | 170,000 | 170,000<br>0 | F342 | Budgetary<br>None<br>Proprietary<br>None |       |        |    |

#### **POST-CLOSING TRIAL BALANCE YEAR 4**

| Agency (030)                       |           |           | DOL (016 1521)                             |         |         |
|------------------------------------|-----------|-----------|--------------------------------------------|---------|---------|
| Budgetary                          | DR        | CR        | Budgetary                                  | DR      | CR      |
| 420100<br>Total Actual Resources   | 0         |           | 420100<br>Total Actual Resources-Collected | 215,000 |         |
| Collected                          |           |           |                                            |         |         |
| 445000 Unapportioned Authority     |           |           | 445000 Unapportioned Authority             |         | 215,000 |
| TOTAL                              | 0         | 0         | TOTAL                                      | 215,000 | 215,000 |
|                                    |           |           |                                            |         |         |
|                                    |           |           |                                            |         |         |
| Proprietary                        |           |           | Proprietary                                |         |         |
| 221500(F016) OPEB Payable          |           | 0         | 101000(G099)<br>Fund Balance with Treasury | 215,000 |         |
| 222500(F016) Unfunded FECA         |           | 485,000   | 132100(F030) Unfunded Employee Benefit     | 485,000 |         |
| Liability                          |           |           | Contributions Receivable                   |         |         |
| 265000(N) Actuarial FECA Liability |           | 8,200,000 | 331000 Cumulative Results of Operations    |         | 700,000 |
| 310000Unexpended Appropriation     |           | 0         |                                            |         |         |
| 331000Cumulative Results of        | 8,655,000 |           |                                            |         |         |
| Operations                         |           |           |                                            |         |         |
| TOTAL                              | 8,685,000 | 8,685,000 | TOTAL                                      | 700,000 | 700,000 |

#### **BALANCE SHEET YEAR 4**

|                                                                                                                                                                 | Agency<br>(030)                 | DOL(016)                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|------------------------------------------|
| Assets<br>Intragovernmental<br>1. Fund Balance with Treasury (101000)<br>3. Accounts Receivable (132100E)<br>6. Total Intragovernmental<br>15. Total Assets     | 0                               | 215,000<br>485,000<br>700,000<br>700,000 |
| Liabilities<br>Intragovernmental<br>17 Accounts Payable<br>19. Other (221500,222500)<br>20. Total Intragovernmental                                             | 0<br>485,000<br>485,000         |                                          |
| Liabilities with Public<br>24. Federal Employee and Veteran Benefits (265000)<br>28. Total Liabilities                                                          | 8,200,000<br>8,685,000          |                                          |
| Net Position<br>31. Unexpended Appropriation –<br>Other Funds (310000E)<br>33. Cumulative Results of Operations-Other Funds (331000E)<br>34. Total Net Position | 0<br>(8,685,000)<br>(8,685,000) | 700,000<br>700,000                       |
| 35. Total Liabilities and Net Position                                                                                                                          | 0                               | 700,000                                  |

#### **STATEMENT OF NET COST YEAR 4**

|    | Program Costs                                      | Agency (030) | DOL(016)  |
|----|----------------------------------------------------|--------------|-----------|
|    | Program A:                                         |              |           |
|    | 1. Gross Cost :                                    |              |           |
|    | (685000E, 640000N)                                 | 240,000      | 240,000   |
|    | (760000E)                                          | 2,700,000    |           |
|    | 2. Less: Earned Income(540000E, 540500E)           |              | (240,000) |
|    | 3. Net Program Costs                               | 2,940,000    | 0         |
| 5. | Net Program Costs Including Assumption Changes     | 0            | 0         |
| 6. | Costs Not Assigned<br>to Programs                  | 0            | 0         |
| 7. | Less: Earned Revenues Not Attributable to Programs |              |           |
| 8. | Net Cost of Operations                             | 2,940,000    | 0         |

### **USSGL 2108 YEAR-END CLOSING STATEMENT YEAR 4**

| Column 5 (101000E)  | Agency (030)<br>0 | DOL(016)<br>215,000 |
|---------------------|-------------------|---------------------|
| Column 11 (461000E) | 0                 | 215,000             |

### **Statement of Changes In Net Position YEAR 4**

| Cumulative Results of Operations<br>1. Beginning Balance | Agency (030)<br>(5,915,000) | DOL(016)<br>700,000 |
|----------------------------------------------------------|-----------------------------|---------------------|
| 2. Adjustments<br>3. Beginning Balances, as Adjusted     | (5,915,000)                 | 700,000             |
| Budgetary Financing Sources                              |                             |                     |
| 4. Other Adjustments                                     |                             |                     |
| 5. Appropriations Used (570000)                          | 170,000                     |                     |
| 6. Nonexchange Revenue                                   |                             |                     |
| 7. Donations and Forfeitures                             |                             |                     |
| 8. Transfers in/out<br>without reimbursements            |                             |                     |
| 9. Other                                                 |                             |                     |
| Other Financing Sources:<br>13. Other (599400)           |                             |                     |
| 14. Total Financing Sources                              | 170,000                     | 0                   |
| 15. Net Cost of Operations                               | (2,940,000)                 | 0                   |
|                                                          |                             |                     |
| 16. Net Change                                           | (2,770,000)                 | 0                   |
| 17. Cumulative Results of Operations                     | (8,685,000)                 | 700,000             |
| Unexpended Appropriations                                |                             |                     |
| 18. Beginning Balance                                    | 0                           | 0                   |
| 19. Adjustments                                          |                             |                     |
| 20. Beginning Balance, as adjusted                       | 0                           | 0                   |
| Budgetary Financing Sources                              |                             |                     |
| 21. Appropriations Received (310100)                     | 170,000                     | 0                   |
| 22. Appropriations Transferred in/out                    |                             |                     |
| 23. Other Adjustments                                    |                             |                     |
| 24. Appropriations Used (310700)                         | (170,000)                   | 0                   |
| 25. Total Budgetary Financing Sources                    | 0                           | 0                   |
| 26. Total Unexpended Appropriations                      | 0                           | 0                   |
| 27. Net Position                                         | (8,685,000)                 | 700,000             |

### **STATEMENT OF BUDGETARY RESOURCES**

|                                                                                                                                                                                                           | TAFS (030)        | TAFS (16 1521)                |  |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|-------------------------------|--|
| BUDGETARY RESOURCES<br>1000<br>Unobligated balance<br>brought forward, October (420100B,)<br>1290 Appropriation (411900E)<br>1890 Spending Authority from Offsetting Collection ( 425200E)                | 170,000           | 285,000<br>170,000            |  |
| 1910 Total Budgetary Resources (sum of SBR lines 1000, 1020, 1021, 1043, 1290,<br>1490, 1690, and 1890.)                                                                                                  | 170,000           | 455,000                       |  |
| STATUS OF BUDGETARY RESOURCES<br>2190 Obligation Incurred (490200E)<br>2204 Apportioned<br>(461000E)<br>2490 Unobligated balance brought forward, end of year (sum of SBR lines 2204, 2304,<br>and 2404.) | 170,000<br>0<br>0 | 240,000<br>215,000<br>455,000 |  |
| 2500 Total Budgetary Resources (sum of SBR lines 2190 and 2490)                                                                                                                                           | 170,000           | 455,000                       |  |

#### **SF133: REPORTING ON BUDGET EXECUTIONS AND BUDGETARY RESOURCES AND BUDGET PROGRAM & FINANCING (P&F) SCHEDULE YEAR 4**

| BUDGETARY RESOURCES                                                          | Agency (030) |           | DOL<br>(016) |           |
|------------------------------------------------------------------------------|--------------|-----------|--------------|-----------|
|                                                                              | SF 133       | P&F       | SF133        | P&F       |
| All Accounts:                                                                |              |           |              |           |
| 0900 Total New Obligations (490200E)                                         | N/A          | 170,000   | N/A          | 240,000   |
| Unobligated Balance                                                          | 0            | 0         | 285,000      | 285,000   |
| 1000 Unobligated Balances Brought Forward 10/1 (420100B, 422100B)            |              |           |              |           |
| 1200 Appropriation (411900E)                                                 | 170,000      | 170,000   | 0            | 0         |
| 1800 Spending Authority from Offsetting Collections (Mandatory) (425200)     |              |           | 170,000      | 170,000   |
| 1801Change in Uncollected Customer Payments from Federal Sources (422100E-B) |              |           | 0            | 0         |
| 1910 Total budgetary resources (calc. line 1800-1840)                        | 170,000      | N/A       | 455,000      | N/A       |
| 1930 Total budgetary resources available (calc. line 1000,1800)              | N/A          | 170,000   | N/A          | 455,000   |
| STATUS OF BUDGETARY RESOURCES                                                |              |           |              |           |
| Obligation Incurred Direct:                                                  |              |           |              |           |
| 2001Obligation Incurred, Direct (490200)                                     | 170,000      | N/A       |              |           |
| 2004 Direct obligations (total)                                              | 170,000      | N/A       |              |           |
| 2102 Reimbursable (490200)                                                   |              |           |              |           |
|                                                                              |              |           | 240,000      | N/A       |
| 2104 Reimbursable Obligations (total)                                        |              |           | 240,000      | N/A       |
|                                                                              |              |           |              |           |
| Unobligated balance:                                                         |              |           |              |           |
| 2201 Available in Current pd (461000)                                        |              |           | 215,000      | N/A       |
| 2500 Total budgetary resources                                               | 170,000      | N/A       | 455,000      | N/A       |
| CHANGE IN OBLIGATED BALANCE                                                  |              |           |              |           |
| Changes in obligated balance during the year:                                |              |           |              |           |
| 3010 Obligations incurred, unexpired accounts (490200E)                      | 170,000      | 170,000   | 240,000      | 240,000   |
| 3020 Outlays (gross) (-) (490200E)                                           | (170,000)    | (170,000) | (240,000)    | (240,000) |
| 3060 Uncollected Payments, Fed Sources brought forward Oct 1(422100B)        |              |           | 0            | 0         |
| 3070 Change in Uncollected Payments, Fed Sources, unexpired accounts (+or-)  |              |           | (70,000)     | (70,000)  |
| 3090 Uncollected Payments Federal sources (422100E) (-)                      | 0            | 0         | 0            | 0         |
| 3100 Obligated balance, start of year (calc. lines)                          |              |           | (415,000)    | (415,000) |

| 3200 Obligated balance, end of year (calc. lines)                                    | 0       | 0       | (485,000) | (485,000) |
|--------------------------------------------------------------------------------------|---------|---------|-----------|-----------|
|                                                                                      |         |         |           |           |
| BUDGET AUTHORITY AND OUTLAYS, NET                                                    |         |         |           |           |
| Mandatory:                                                                           |         |         |           |           |
| Gross budget authority and outlays:                                                  |         |         |           |           |
| 4090 Budget authority gross (calc. lines 1800)                                       | 170,000 | 170,000 | 240,000   | 240,000   |
| 4100 Outlays from new mandatory authority (490200)                                   | 170,000 | 170,000 | 240,000   | 240,000   |
| 4110 Total outlays, gross (calc. line 4100)                                          | 170,000 | 170,000 | 240,000   | 240,000   |
| 4120 Offsets against gross budget authority and outlays (425200) (-)                 | 0       | 0       | (170,000) | (170,000) |
| 4140 Change in Uncollected Customer Payments from Federal sources (Unexpired)        |         |         | 0         | 0         |
| 4160 Budget authority, net (mandatory) (Cal line 4090 and 4120)                      | 170,000 | 170,000 | 0         | 0         |
| 4170 Outlays, net (mandatory) (Calc line 4110+ 4120 through 4124)                    | 170,000 | 170,000 | 70,000    | 70,000    |
| Budget authority and outlays, net (total):                                           |         |         | 0         | 0         |
| 4180 Budget authority, net (discretionary and mandatory) (Sum of line 4070 and 4160) | 170,000 | 170,000 |           |           |
| 4190 Outlays, net (discretionary and mandatory) (calc. line 4080 and 4170)           | 170,000 | 170,000 | 70,000    | 70,000    |
|                                                                                      |         |         |           |           |
|                                                                                      |         |         |           |           |

### **Appendix:**

TITLE 5--GOVERNMENT ORGANIZATION AND EMPLOYEES

PART III--EMPLOYEES

Subpart G--Insurance and Annuities

CHAPTER 81--COMPENSATION FOR WORK INJURIES

SUBCHAPTER I--GENERALLY

Sec. 8147. Employees' Compensation Fund

- (a) There is in the Treasury of the United States the Employees' Compensation Fund which consists of sums that Congress, from time to time, may appropriate for or transfer to it, and amounts that otherwise accrue to it under this subchapter or other statute. The Fund is available without time limit for the payment of compensation and other benefits and expenses, except administrative expenses, authorized by this subchapter or any extension or application thereof, except as otherwise provided by this subchapter or other statute. The Secretary of Labor shall submit annually to the Office of Management and Budget estimates of appropriations necessary for the maintenance of the Fund. For the purpose of this subsection, ``administrative expenses'' does not include expenses for legal services performed by or for the Secretary under sections 8131 and 8132 of this title.
- (b) Before August 15 of each year, the Secretary shall furnish to each agency and instrumentality of the United States having an employee who is or may be entitled to compensation benefits under this subchapter or any extension or application thereof a statement showing the total cost of benefits and other payments made from the Employees' Compensation Fund during the preceding July 1 through June 30 expense period on account of the injury or death of employees or individuals under the jurisdiction of the agency or instrumentality. Each agency and instrumentality shall include in its annual budget estimates for the fiscal year beginning in the next calendar year a request for an appropriation in an amount equal to the costs. Sums appropriated pursuant to the request shall be deposited in the Treasury to the credit of the Fund within 30 days after they are available. An agency or instrumentality not dependent on an annual appropriation shall make the deposit required by this subsection from funds under its control during the first fifteen days of October following the furnishing of the statement. If an agency or instrumentality (or part or function thereof) is transferred to another agency or instrumentality, the cost of compensation benefits and other expenses paid from the Fund on account of the injury or death of employees of the transferred agency or instrumentality (or part or function) shall be included in costs of the receiving agency or instrumentality.
- (c) In addition to the contributions for the maintenance of the Employees' Compensation Fund required by this section, the United States Postal Service, or a mixed ownership corporation as defined by section 9101(2) of title 31, or any other corporation or agency or instrumentality (or activity thereof) which is required by statute to submit an annual budget pursuant to or as provided by chapter 91 of title 31, shall pay an additional amount for its fair share of the cost of administration of this subchapter as determined by the Secretary. With respect to these corporations,

agencies, and instrumentalities, the charges billed by the Secretary under this section shall include an additional amount for these costs, which shall be paid into the Treasury as miscellaneous receipts from the sources authorized and in the manner otherwise provided by this section.