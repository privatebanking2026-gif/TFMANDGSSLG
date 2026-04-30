# 6 Notification of Change

## In this chapter...

| A: Introduction to Notification of Change                                    | 6-2 |
|------------------------------------------------------------------------------|-----|
| When to use NOCs                                                             | 6-2 |
| Benefit Payments                                                             | 6-2 |
| Other Payment Types                                                          | 6-2 |
| When to use NOCs, ENRs, or Other Ways to Change Recipient Information        |     |
| Processing Timeframes                                                        | 6-3 |
| What to do if an agency does not respond to a NOC within two payment cycles: |     |
| Change Reason Codes                                                          | 6-3 |
| Claim Number Structure                                                       |     |
| Claim Number Structure Table                                                 | 6-4 |
| B: Other Change Methods                                                      | 6-4 |
| Financial Institution Actions                                                |     |
| C: Refused Notification of Change                                            |     |
| Federal Agencies Using Refused NOCs                                          | 6-7 |
| Processing Timeframes                                                        | 6-7 |
| Refused NOC Codes                                                            | 6-7 |

# **A: Introduction to Notification of Change**

Notification of Change (NOC), which is the name for Nacha's Standard Entry Class (SEC) code COR, is a method used by a financial institution to notify a federal agency to correct or change account information in an entry the federal agency processed through the ACH. Refer to current Nacha Operating Rules & Guidelines for formats and instructions.

**Note:** *ENRs should not be used in place of NOCs to correct account information. Please see Chapter 1, Section F, Enrollment Guidance, for more information about when ENRs can be used.* 

#### **When to use NOCs**

NOCs are used for federal government (both civil and military) payments that are made on a recurring basis. Examples are:

#### *Benefit Payments*

- x Benefit payments issued by Department of Veterans Affairs,
- x Civil service retirement payments issued by Office of Personnel Management,
- x Benefit payments issued by Railroad Retirement Board,
- x Social Security benefit payments, and
- x Supplemental Security Income payments.

#### *Other Payment Types*

- x Federal salary,
- x TreasuryDirect, and
- x Vendor and miscellaneous.

## **When to use CORs, ENRs, or Other Ways to Change Recipient Information**

| To change                                                        | Recipient would                                           |
|------------------------------------------------------------------|-----------------------------------------------------------|
| Title/ownership of account                                       |                                                           |
| Interest of the recipient or beneficiary in the account          | Complete a new enrollment                                 |
| From one financial institution to another                        |                                                           |
| New bank account number at the existing financial<br>institution | Submit ENR or COR                                         |
| Name of recipient or change of mailing address                   | Contact the federal agency that authorized the<br>payment |
| Account information for one-time payments                        | One-time payments require a new authorization             |

## **Processing Timeframes**

Generally, CORs will be processed for the next ACH transaction. Due to operational limitations, it may take two payment cycles for some CORs to be processed.

## **What to do if an agency does not respond to a COR within two payment cycles:**

- Verify that the COR was properly formatted. Make sure that the COR contained the correct original RDFI routing number.
- If the COR was correctly formatted, contact Fiscal Service. See Contact information below. Fiscal Service will work with the agency for resolution.
- Make sure that rejected CORs are acknowledged and resolved (See below).

If you have any questions, contact the Fiscal Service Payment Management Call Center, at 855-868-0151, Option 1.

### **Change Reason Codes**

The federal government's disbursing systems are only able to process the following six authorized COR/Change codes: C01, C02, C03, C05, C06, and C07. The federal agencies will not process any others.

The following table shows when to use the Change Reason Codes.

| Change Reason Code                                                                 | When to Use                                                                                                          |
|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| C01 - Incorrect Account Number                                                     | Correct data entry errors in the account information.                                                                |
|                                                                                    | Issue a new number to an existing account.                                                                           |
|                                                                                    | Modify the account numbering system (e.g. to drop a branch code).                                                    |
| C02 - Incorrect RTN                                                                | Accommodate a merger or system consolidation.                                                                        |
|                                                                                    | Change the RTN to the preferred RTN for the financial institution.                                                   |
| C03 - Incorrect RTN and Incorrect<br>Account Number                                | Accommodate a merger or system consolidation.                                                                        |
| C05 - Incorrect Transaction Code                                                   | Change from checking to savings or savings to checking.                                                              |
| C06 - Incorrect Account Number<br>and Incorrect Transaction                        | Correct a data entry error in the account information and change<br>from checking to savings or savings to checking. |
| Code                                                                               | Issue a new account number and transaction code.                                                                     |
| C07 - Incorrect RTN, Incorrect<br>Account Number and<br>Incorrect Transaction Code | Accommodate a merger or system consolidation.                                                                        |

**Note:** *The only Transaction Codes recognized by the federal government for CORs are:* 

| For checking (demand) | For savings | For General Ledger |
|-----------------------|-------------|--------------------|
| 22 (credit)           | 32 (credit) | 42 (credit)        |
| 27 (debit)            | 37 (debit)  |                    |

#### **Claim Number Structure**

Federal agencies have special structures for their claim numbers (Individual ID number). The claim number is important to identifying the payment recipient whose payment information must be changed.

Accurate formatting of the claim number is critical for processing changes. Note that pattern differences exist between federal agencies. These claim numbers must include all spaces, hyphens, prefixes, suffixes, alphanumeric characters, and trailing or leading zeros that accompanied the original payment information.

#### **Claim Number Structure Table**

The following table represents correct claim number structures used in formatting CORs.

| Agency                         | Claim Number Structure                                | Example                                              |
|--------------------------------|-------------------------------------------------------|------------------------------------------------------|
| Social Security Administration | 999999999XX<br>999999999X<br>999999999                | 123456789C1<br>123456789A<br>123456789               |
| Office of Personnel Management | Xb9999999bXb<br>Xb9999999b9b                          | F_1234567_W_<br>A_1234567_0_                         |
| Department of Veterans Affairs | 999999999b99b99<br>99999999b99b99                     | 162306890_10_01<br>12345678_00_06                    |
| Railroad Retirement Board      |                                                       |                                                      |
| Retirement/Annuity             | XXX999999999b9b<br>Xbb999999bbbb9b<br>XXbZZZZZ9bbbb9b | WCA123456789_7_<br>A 123456<br>1_<br>WD_000006<br>8_ |
| Unemployment/Sickness          | bbb999999999                                          | 123456789                                            |
| Department of Labor            | 999999999XXbXXb                                       | 123456789LW_MB_                                      |
| Key:<br>X = alphanumeric,      | 9 = numeric,<br>b = blank,                            | Z = zero filled,<br>_ = space                        |

# **B: Other Change Methods**

Financial institutions not using CORs may continue to submit:

- corrected Direct Deposit Sign-Up Forms (FS Form 1199As) to federal agencies, or
- letters to federal agencies requesting changes.

#### **Financial Institution Actions**

The table below contains instructions for financial institutions not using CORs.

| Type of Payment                                                                                                                                                                                      | Fewer than 100 payments<br>(mail corrected SF119As or letters)                                                                                                     | More than 100<br>payments (call) |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| Air Force<br>Active Duty Reserve                                                                                                                                                                     | Defense Finance and Accounting Service<br>6760 E. Irvington Place                                                                                                  | (303) 676-4326                   |
| Air National Guard                                                                                                                                                                                   | Building 444/JMS                                                                                                                                                   |                                  |
| Active Duty Allotments                                                                                                                                                                               | Denver, CO 80279-3000                                                                                                                                              | (303) 676-7213                   |
| Army                                                                                                                                                                                                 | DFAS - Indianapolis Center                                                                                                                                         | (888) 332-7411                   |
| Active Duty Reserve                                                                                                                                                                                  | 8899 E. 56th Street                                                                                                                                                |                                  |
| Active Duty Allotments                                                                                                                                                                               | Indianapolis, IN 46249-2801                                                                                                                                        |                                  |
| Coast Guard<br>Active Duty<br>(Code PS)<br>Reserves<br>(Code RES)<br>Retired<br>(Code RPD)                                                                                                           | Commanding Officer (Code )<br>US Coast Guard<br>Pay and Personnel Center<br>444 SE Quincy Street<br>Topeka, KS 66683-3591                                          | (785) 339-3506                   |
| Department of Veterans Affairs<br>Veterans Compensation, Pension or Education<br>(MGIB)                                                                                                              | VA Regional Office that maintains the<br>veteran's records                                                                                                         | (877) 838-2778                   |
| Veterans Life Insurance                                                                                                                                                                              |                                                                                                                                                                    | (215) 842-2000<br>ext. 14270     |
| Fiscal Service                                                                                                                                                                                       |                                                                                                                                                                    |                                  |
| Federal Housing Administration<br>Debenture Payments<br>State and Local Government Series Securities<br>Payments<br>United States Mortgage Guaranty Insurance<br>Company and Tax Loss Bonds Payments | Bureau of the Fiscal Service<br>Special Investments Branch Warehouse<br>and Operations Center, Dock 1<br>257 Bosley Industrial Park Drive<br>Parkersburg, WV 26101 | (304) 480-5299                   |
| TreasuryDirect                                                                                                                                                                                       | Bureau of the Fiscal Service<br>Treasury Retail Securities Services<br>P.O. Box 9150<br>Minneapolis, MN 55480-9150                                                 | (844) 284-2676                   |
| pay the Treasury and security owners for any losses resulting from errors made by the institution. (31 CFR part 370.12)                                                                              | Note: Financial institutions should submit systemwide changes to TreasuryDirect with the understanding that they agree to                                          |                                  |
| Savings Bonds                                                                                                                                                                                        | Federal Reserve<br>Bank of Pittsburgh<br>P.O. Box 299                                                                                                              | (800) 322-1909                   |
|                                                                                                                                                                                                      | Pittsburgh, PA 15230-0299                                                                                                                                          |                                  |
| Federal Salary and Allotment payments<br>Federal salary and Allotment payments<br>(including payments by the military to civilian<br>employees) (FED SALARY)                                         | Federal employing agency authorizing the payment (address<br>where original FS Form 1199As were mailed). If address is<br>unknown, contact recipient/member.       |                                  |
| Marine Corps                                                                                                                                                                                         | DFAS - Kansas City Center                                                                                                                                          | (888) 332-7411                   |

#### **Green Book** *6. Notification of Change*

| Type of Payment                                                                          | Fewer than 100 payments<br>(mail corrected SF119As or letters)                                        | More than 100<br>payments (call)                                               |
|------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| Active Duty/Reserve<br>Active Duty Allotment                                             | 1500 E. 95th Street<br>Kansas City, MO 64197-0001                                                     |                                                                                |
| Military Retirement Pay<br>Army, Air Force, Navy and Marine Corps                        | DFAS - Cleveland Center Retired Pay<br>Operations<br>P.O. Box 99191<br>Cleveland, OH 44199-1126       | (800) 321-1081<br>fax: (800) 469-6559<br>DC Metro Area ONLY:<br>(202) 606-0500 |
| Navy<br>Active Duty<br>Reserve                                                           | DFAS - Cleveland Center/JFECA<br>1240 East Ninth Street<br>Cleveland, OH 44199-2055                   | (216) 522-5855                                                                 |
| Office of Personnel Management<br>Civil Service Retirement<br>(Annuity)<br>(CIVIL SERVE) | Office of Personnel Management<br>Retirement Operations Center<br>P.O. Box 45<br>Boyers, PA 16017     | (888) 767-6738<br>fax: (724) 794-6633                                          |
| Railroad Retirement Board<br>Railroad Retirement<br>(RR RET)                             | Railroad Retirement Board<br>Direct Deposit Coordinator<br>844 North Rush Street<br>Chicago, IL 60611 | (312) 751-4704                                                                 |

# **C: Refused Notification of Change**

Refused Notification of Change is an automated method used by a federal agency to notify the originating financial institution that the COR information initiated cannot be processed.

#### **Federal Agencies Using Refused CORs**

The Social Security Administration (SSA), the Railroad Retirement Board (RRB), and the Office of Personnel Management (OMB) are the only federal agencies processing Refused CORs at this time.

#### **Processing Timeframes**

CORs that cannot be processed are usually refused to the financial institution before the next payment is submitted.

#### **Refused COR Codes**

There are six refused COR codes authorized for federal government ACH entries:

| Code | Reason                                                       |
|------|--------------------------------------------------------------|
| C64  | Incorrect individual identification                          |
| C65  | Incorrectly formatted corrected data                         |
| C66  | Incorrect discretionary data                                 |
| C67  | Routing Transit Number not from original Entry Detail Record |
| C68  | DFI Account Number not from original Entry Detail Record     |
| C69  | Incorrect Transaction Code                                   |