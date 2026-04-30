## **FUNDS HELD OUTSIDE OF TREASURY – NON-BUDGETARY FISCAL YEAR 2016**

### **PREPARED BY:**

**UNITED STATES STANDARD GENERAL LEDGER ADVISORY DIVISION GOVERNMENTWIDE ACCOUNTING BUREAU OF THE FISCAL SERVICE U.S. DEPARTMENT OF THE TREASURY**

| Version<br>Number | Date       | Description of Change | Effective<br>USSGL TFM |
|-------------------|------------|-----------------------|------------------------|
| 1.0               | 06/25/2015 | Original Version      | TFM S2 15-01           |

**NOTE**: This scenario follows USSGL TFM S2 15-01 (June 2015) Part 1.

#### **Overview**

During the initial reporting periods where agencies started using the Governmentwide Treasury Account Symbol Adjusted Trial Balance System (GTAS) it was discovered that agencies that had Funds Held Outside of Treasury (FHOT) that are non-budgetary didn't have a USSGL account that they were able to use so that they can record their FHOT non-budgetary in order to pass GTAS edit 5 - Funds Held Outside of Treasury Business Line Balances. After a datacall to agencies and discussions with the Bureau of the Fiscal Service Cash Accounting Division it was determined that the best solution would be to create a new USSGL account for agencies to use when they have non-budgetary FHOT that is recorded in the Central Accounting Reporting System (CARS).

#### **New USSGL Account**

**Account Title:** Funds Held Outside of Treasury – Non-Budgetary

**Account Number**: 113500 **Normal Balance:** Debit

**Definition:** The amount of cash deposited in accounts outside of the U.S. Treasury, in non-Treasury General Accounts

(non-TGAs) held by the public that the Office of Management and Budget has determined will not be included

in the Budget of the United States Government. This account does not close at yearend.

### **Listing of USSGL Accounts Used in This Scenario**

| Account<br>Number | Account Title                                                        |
|-------------------|----------------------------------------------------------------------|
|                   |                                                                      |
|                   |                                                                      |
| Budgetary         |                                                                      |
| None              |                                                                      |
|                   |                                                                      |
| Proprietary       |                                                                      |
|                   |                                                                      |
| 113500            | Funds Held Outside of Treasury<br>–<br>Non-Budgetary                 |
| 240000            | Liability for Nonfiduciary Deposit Funds and Undeposited Collections |

#### **Attribute Table**

| No.     | USSGL Account Title                                 | Anticipated | Budg/Prop | Norm<br>Bal | Begin/End | Debit/Credit | Auth<br>Type<br>Code | Apport<br>Cat | Apport<br>Cat B |
|---------|-----------------------------------------------------|-------------|-----------|-------------|-----------|--------------|----------------------|---------------|-----------------|
| 1135000 | Funds Held Outside of<br>Treasury<br>-Non-Budgetary | N           | P         | D           | B/E       | D/C          |                      |               |                 |

Attribute Table (continued)

| Avail<br>Time | BEA<br>Cat | Borrow<br>Source | Budgetary<br>Impact<br>Indicator | Cohort<br>Yr | Cust/<br>Noncust | Exch/<br>Nonexch | Fed/<br>NonFed | Trading<br>Ptnr | Trading<br>Ptnr Main | PY<br>Adj | Program<br>Indicator |
|---------------|------------|------------------|----------------------------------|--------------|------------------|------------------|----------------|-----------------|----------------------|-----------|----------------------|
|               |            |                  |                                  |              |                  |                  | N              |                 |                      |           |                      |

Attribute Table (continued)

| Program Rpt<br>Cat | Reimb Flag | Year of<br>BA | Reduction Type | Fund Type | Reporting<br>Type Code | Financing<br>Account<br>Code | TAS<br>Status | Trans.<br>Code |
|--------------------|------------|---------------|----------------|-----------|------------------------|------------------------------|---------------|----------------|
|                    |            |               |                | DF        | E/F/U                  | N                            | U/E           | X/K/N          |

#### **CrosswalksImpacted**

| USSGL<br>Account | Balance<br>Sheet | Net<br>Cost | Net<br>Position | Custodial<br>Activity | P&F/<br>SF133 | SBR | Reclassified<br>Balance | Reclassified<br>Net Cost | Reclassified Net<br>Position |
|------------------|------------------|-------------|-----------------|-----------------------|---------------|-----|-------------------------|--------------------------|------------------------------|
|                  |                  |             |                 |                       |               |     |                         |                          |                              |
| Number           |                  |             |                 |                       |               |     | Sheet                   |                          |                              |

#### <span id="page-6-0"></span>**USSGL Scenario**

A beginning trial balance is not applicable in this scenario.

#### **Illustrative Transactions**

1. To record \$100 for total amount received and deposited in a Non-Treasury General Account at a bank. These funds are held temporarily by the Government until ownership is determined.

| Deposit fund (FHOT)                        |     |     |      |        |
|--------------------------------------------|-----|-----|------|--------|
|                                            | DR  | CR  | TC   | BETC1  |
| Budgetary Entry                            |     |     |      |        |
| None                                       |     |     |      |        |
|                                            |     |     |      |        |
| Proprietary Entry                          |     |     |      |        |
| 113500 Funds Held Outside of Treasury<br>– |     |     |      |        |
| Non                                        | 100 |     | C108 |        |
| Budgetary                                  |     |     |      | FHOTXD |
| 240000 Liability for Nonfiduciary          |     | 100 |      |        |
| Deposit Funds and Undeposited Collections  |     |     |      |        |

complete and appropriate list of the most current TAS BETC information

<sup>1</sup> The Business Event Type Codes (BETCs) referenced in this transaction are very high-level examples which purposely focus on a limited number of BETCs due to the extent of the many possible BETC combinations based on the Treasury Account Symbol (TAS). The scenario is not meant to address all the BETCs, please refer to the Shared Accounting Module (SAM) public website at<https://www.sam.fms.treas.gov/sampublic>for a 

<span id="page-7-0"></span>2. To disburse \$100 after ownership has been determined.

| Deposit fund (FHOT)                                                                                                                                                                              |     |     |      |        |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|-----|------|--------|
|                                                                                                                                                                                                  | DR  | CR  | TC   | BETC1  |
| Budgetary Entry<br>None<br>Proprietary Entry<br>240000 Liability for Nonfiduciary Deposit<br>Funds and Undeposited Collections<br>113500<br>Funds Held Outside of Treasury<br>–<br>Non-Budgetary | 100 | 100 | D506 | FHOTXC |

<sup>1</sup> The Business Event Type Codes (BETCs) referenced in this transaction are very high-level examples which purposely focus on a limited number of BETCs due to the extent of the many possible BETC combinations based on the Treasury Account Symbol (TAS). The scenario is not meant to address all the BETCs, please refer to the Shared Accounting Module (SAM) public website at<https://www.sam.fms.treas.gov/sampublic>for a complete and appropriate list of the most current TAS BETC information

| Post-closing Trial Balance                    |       |        |
|-----------------------------------------------|-------|--------|
| Deposit fund (FHOT)                           | Debit | Credit |
| Budgetary                                     |       |        |
| None                                          |       |        |
|                                               |       |        |
| Proprietary                                   |       |        |
| 113500<br>Funds Held Outside of Treasury<br>– | -     |        |
| Non-Budgetary                                 |       |        |
|                                               |       |        |
| 240000 Liability for Nonfiduciary Deposit     |       | -      |
| Funds and Undeposited Collections             |       |        |
| Total                                         | -     | -      |