# 4 Returns

# **Overview**

This chapter describes the return process for federal payments.

# In this chapter...

| A: General Information on Returns                                          | 4-2 |
|----------------------------------------------------------------------------|-----|
| Return Reason Codes (ACH Credits)                                          | 4-2 |
| Death Notification Entry                                                   | 4-3 |
| Effect of Returning a Payment                                              |     |
| Notice of Misdirected Payment                                              |     |
| Manual Posting of Payments                                                 | 4-4 |
| No Holding of Payments in Suspense Accounts                                | 4-4 |
| Recipients Without Current Accounts                                        |     |
| B: Returning Payments Through the ACH                                      | 4-5 |
| ACH Correct Preparation of Returns                                         | 4-5 |
| Claim Number Structure Table                                               | 4-5 |
| C: Returning Partial Payments in Response to Notices of Reclamation        | 4-6 |
| D: Dishonored Returns                                                      | 4-7 |
| Most Common Errors                                                         | 4-7 |
| E: Payments Returned in Error; Obtaining a Refund due from the Government  | 4-8 |
| What to do if a Payment was Returned in Error                              |     |
| Additional Information on Treasury Direct Payments made in Error/Duplicate |     |
| SSA Program Service Centers                                                |     |
| What to do if there are Duplicate Returns                                  |     |
| Restoring Funds                                                            |     |

# **A: General Information on Returns**

All ACH Payments must be returned in accordance with Nacha Operating Rules & Guidelines. An ACH payment must be returned if:

- x An enrollment has been terminated and a new enrollment for the same recipient has not been completed,
- x The financial institution receives a benefit payment after it has actual or constructive knowledge of the death or legal incapacity of a recipient, including a representative payee,
- x The financial institution is honoring a Death Notification Entry (DNE) or other notification of death from a federal agency,
- x The account has been closed by the recipient, or the financial institution has closed an account to which benefit payments are being delivered after giving the recipient 30 days written notice (except where fraud is suspected; then the account may be closed immediately),
- x There is no current account for the recipient, and
- x For any other reason the financial institution is unable to credit the payment to the account.

## **Return Reason Codes (ACH Credits)**

The government can accept all Nacha-approved return reason codes. Following is a list of some of the more common return reason codes that RDFIs use to return government credits:

- x R02 Account Closed
- x R03 No Account/Unable to Locate Account
- x R04 Invalid Account Number Structure
- x R06 Returned per ODFI's Request
- x R14 Representative Payee Deceased or Unable to Continue in that Capacity
- x R15 Beneficiary or Account Hold (Other Than a Representative Payee) Deceased
- x R16 Account Frozen/Entry Returned Per OFAC Instruction
- x R17 File Record Edit Criteria (Specify)/Entry with Invalid Account Number Initiated Under Questionable Circumstances/Return of Improperly-Initiated Reversal
- x R20 Non-Transaction Account

If you must return a federal payment for any reason not listed, use reason code "R20" on the return.

RDFIs that learn of the death of a recipient of benefit payments from a source other than the agency are encouraged to use reason code R15 (Beneficiary or Account Holder Deceased) or R14 (Representative Payee Deceased) to notify government agencies of the death. By using these return

codes, the RDFI will satisfy both the requirement to return post-death payments that it receives after actual or constructive knowledge of the death, and the requirement to notify the agency of the death of the recipient.

RDFIs are able (but not required) to use Return Reason Code R17 – (File Record Edit Criteria / Entry with Invalid Account Number Initiated Under Questionable Circumstances / Return of Improperly-Initiated Reversal) to indicate that the RDFI believes an ACH Credit containing invalid account information was initiated under questionable circumstances. This use of R17 is optional at the discretion of the RDFI. Those RDFIs that elect to use R17 for this purpose are required to use the description "QUESTIONABLE" in the Addenda Information field of the return. This description in an R17 return differentiates returns that appear to be suspicious to the RDFI from those due to routine account number issues.

*Note: The existing Nacha-coordinated opt-in programs with federal and state tax agencies that allow RDFIs to return questionable tax refund ACH credits using R17 will continue unchanged. These programs will not be impacted by this additional optional use of the R17 Return Reason Code. Fiscal Service and the IRS participate with Nacha in this program for IRS tax refund credit entries returned as questionable. The Return Reason Code R17 will also continue to be used in its standard form for returns involving required field errors. For more information- https://www.nacha.org/content/irsrefund-return-opt-program*

# **Death Notification Entry**

The Death Notification Entry (DNE) allows federal agencies to notify financial institutions of a benefit recipient's death. Only an agency of the federal government may originate a DNE. Currently, SSA, OPM, and RRB originate DNEs. Other federal benefit agencies may originate DNEs at a future date. The DNE is a zero-dollar entry with an addenda record. The addenda record contains the date of death, the deceased individual's SSN, and the amount of the next scheduled benefit payment.

Upon receipt of a DNE, the financial institution is encouraged to "flag" the deceased recipient's account to prevent accepting further post-death federal benefit payments. See below form common errors with flagging.

#### *Example: Flagging Joint Accounts*

A married couple own a joint account. One spouse dies. A DNE is sent from the federal benefit agency to the RDFI. The RDFI receives the DNE and the account is "flagged". The surviving spouse becomes eligible for surviving spousal's benefits, and a benefit payment is sent to the joint account. Since the account is "flagged," the RDFI improperly returns the surviving spousal's benefits with a reason code of R15 (beneficiary or account holder deceased). The agency receives the returned benefit and processes an improper death termination for the surviving spouse. The agency also sends an improper DNE for the surviving spouse to the RDFI.

**Solution:** *To protect joint account holders, the account should be "flagged" with another piece of identifying information (i.e., deceased name, SSN). This allows the joint account holder to continue receiving their own payments. If this is not possible, a new account with a new Direct Deposit authorization should be established.* 

#### *Example: Flagging Erroneous Report of Death*

A recipient is receiving benefits. An erroneous report of death is received by the federal benefit agency for the recipient. A DNE is sent from the agency to the RDFI and the account is "flagged". The recipient discovers the problem and presents proof to the agency and the RDFI of the error in the fact of death. The RDFI fails to remove the flagging from the account. The agency resends the benefit payment to the recipient's account, which is still "flagged". The RDFI returns benefits with a

reason code for death of R15 (beneficiary or account holder deceased) to the agency based on the erroneous flagging. The agency receives the returned benefit and re-processes the death termination. The agency sends an improper DNE once again to the RDFI.

**Solution:** *Always remember to remove any "flagging" on an account when a report of death proves to be erroneous.* 

**Note***: If a financial institution needs to correct errors in their use of return reason codes when returning funds, they should contact the agency receiving the return. Please see Chapter 7, Contacts, for major paying agency contact information.* 

## **Effect of Returning a Payment**

Any returned payment automatically revokes the Direct Deposit authorization and may stop further payments from the federal agency to a recipient's account. The recipient should contact the authorizing federal agency to resume payments.

## **Notice of Misdirected Payment**

In accordance with 31 CFR part 210, if an RDFI becomes aware that an agency has originated an ACH credit entry to an account that is not owned by the payee whose name appears in the ACH payment information, the RDFI shall promptly notify the agency. An RDFI that originates a NOC entry with the correct account and/or RTN information or returns the original ACH credit entry to the agency with the appropriate return reason code, shall be deemed to have satisfied this requirement.

# **Manual Posting of Payments**

Financial institutions may conduct a manual search of their unpostable ACH payments to determine if the payment can be posted.

RDFIs may be held liable for ACH payments not processed timely or correctly. If the federal government sustains a loss as a result of a financial institution's improper handling of an entry, the financial institution is liable to the federal government for the loss, up to the amount of the entry.

# **No Holding of Payments in Suspense Accounts**

Under no circumstances should a financial institution hold unpostable incoming payments indefinitely in a suspense account, or by any other means, nor should payments otherwise be held if any of the conditions apply on when to return a payment. Holding payments may constitute a breach of the financial institution's warranty for the handling of federal government ACH payments under regulations codified in 31 CFR part 210.

# **Recipients Without Current Accounts**

Under normal circumstances a financial institution should not open a new account in response to an unpostable payment. If the recipient closes the account and opens a new account, the recipient must establish a new Direct Deposit authorization. If a recipient's account has been closed, the financial institution must return any subsequent payments made by the federal agency to the account. However, when an account is closed due to fraud and a new account is opened at the same financial institution to replace the account with fraudulent activity, then only an NOC is required."

# **B: Returning Payments Through the ACH**

# **ACH Correct Preparation of Returns**

It is essential that RDFI employees preparing returns have access to data in the original item originated by the government disbursing office. If a processor is used, RDFIs should be sure that the return entry is properly formatted to include the data from the original entry.

"When a Return Entry is prepared, the original Company/Batch Header Record, the original Entry Detail Record, and the Company/Batch Control Record are copied for return to the Originator" (Nacha Operating Rules & Guidelines). If accurate data is not provided in the return entry, the government disbursing office will dishonor the return.

The following four fields must be identical to the original payment data:

- 1. Trace number (provided in the entry detail record),
- 2. Effective entry date,
- 3. Amount of payment, and
- 4. Individual ID number (i.e., claim number. See the Claim Number Structure Table below).

**Note:** *Financial institutions using data processors could receive reformatted data which may contain errors or omissions. The original payment information must be used in its exact format to avoid rejections.* 

Financial institutions should carefully track returned benefit payments to ensure that the returns are not dishonored. This could create an additional liability for the financial institution in a reclamation case.

## **Claim Number Structure Table**

The following table represents correct claim number structures used in formatting returns.

| AGENCY                         | CLAIM NUMBER STRUCTURE     | EXAMPLE                       |
|--------------------------------|----------------------------|-------------------------------|
| Social Security Administration | 999999999XX                | 123456789C1                   |
|                                | 999999999X                 | 123456789A                    |
|                                | 999999999                  | 123456789                     |
| Office of Personnel Management | Xb9999999bXb               | F_1234567_W_                  |
|                                | Xb9999999b9b               | A_1234567_0_                  |
| Department of Veterans Affairs | 999999999b99b99            | 162306890_10_01               |
|                                | 99999999b99b99             | 12345678_00_06                |
| Railroad Retirement Board      |                            |                               |
| Retirement/Annuity             | XXX999999999b9b            | WCA123456789_7_               |
|                                | Xbb999999bbbb9b            | A 123456<br>1_                |
|                                | XXbZZZZZ9bbbb9b            | WD_000006<br>8_               |
| Unemployment/Sickness          | bbb999999999               | 123456789                     |
| Department of Labor            | 999999999XXbXXb            | 123456789LW_MB_               |
| Key:<br>X = alphanumeric,      | 9 = numeric,<br>b = blank, | Z = zero filled,<br>_ = space |

# **C: Returning Partial Payments in Response to Notices of Reclamation**

Payments should be returned by ACH except in limited circumstances. If a partial payment is being returned in response to a Notice of Reclamation (FS Form 133), a financial institution can elect to either have their account debited for the partial payment, or, alternatively, returned by check. In no other case should ACH returns be made by check, except as described in the Note below. Please refer to Chapter 5, Reclamations, for more information including how to request an ACH debit authorization.

**Note:** *If the original payment data is not available, a financial institution may be forced to return an ACH payment by check. The financial institution will receive credit. However, in these cases, credit will be delayed due to manual processing. Note that under Nacha Operating Rules & Guidelines, records of all entries including return and adjustment entries must be retained for six years from the date the entry was transmitted.* 

If the financial institution is returning a payment that is beyond 6 years, the financial institution may do so by mailing the check and related correspondence to the following address:

U.S. Department of the Treasury Bureau of the Fiscal Service National Payment Integrity and Resolution Center P.O. Box 51318 Philadelphia, PA 19115

The table below shows how to return a partial payment by check in response to a Notice of Reclamation.

#### **STEP ACTION**

1 Send the government disbursing office a check payable as indicated on item C-3b on the Notice of Reclamation.

DO NOT SEND THE CHECK TO THE ORIGINATING FEDERAL AGENCY.

- 2 Attach a cover letter listing the following information for each payment subject to return:
  - effective entry date,
  - amount of payment,
  - individual identification number (i.e., SSN/claim number), and
  - reason for return.

If the above payment information is not available, provide the following information:

- recipient's name,
- recipient's SSN or other applicable federal government identification number,
- date of death, and
- name of originating federal agency.

The cover letter must always include:

- recipient's name, and
- name of originating federal agency.

**Provide the name, address, and telephone number of the financial institution contact.** 

# **D: Dishonored Returns**

ACH return entries will be dishonored by the government disbursing office if discrepancies exist between the data on the return item and the data on the original payment.

## **Most Common Errors**

For Treasury-disbursed payments, four fields are read on return items. If any one of these four fields are not identical to the original payment data, Treasury will dishonor the return.

The following four fields must be identical to the original payment data:

- 1. Original Entry Trace Number (provide in the addenda record),
- 2. Effective entry date (i.e., payment date),
- 3. Amount of payment, and
- 4. Individual ID number (i.e., claim number).

The discretionary data field on the return item should be left blank ONLY if it was blank in the original ACH entry. If the field contains data in the original entry, the exact same data must be included in the return entry.

Note that a VA claim number may be an 8-digit number with a blank in the leading space of the individual ID field. If the space is ignored, and the number is left-justified, the return will be dishonored. (See the claim number structure table on page 4-5.)

If a financial institution receives a dishonored return, the financial institution should correct the information in the return and originate a contested return in accordance with Nacha Operating Rules & Guidelines.

#### Dishonored Return Codes:

- x R61 Misrouted Return
- x R67 Duplicate Return
- x R68 Untimely Return
- x R69 Field Errors (the error(s) will be identified in the Addenda Information field on the dishonored file positions 59-79. The two-digit code, separated by an asterisk, will be written for each error found.)
  - 01 Return Contains Incorrect DFI Account Number
  - 02 Return Contains Incorrect Original Entry Trace Number
  - 03 Return Contains Incorrect Dollar Amount
  - 04 Return Contains Incorrect Individual Identification Number/Identification Number
  - 05 Return Contains Incorrect Transaction Code
  - 06 Return Contains Incorrect Company Identification Number
  - 07 Return Contains an Invalid Effective Entry Date
- x R70 Permissible Return Entry Not Accepted

# **E: Payments Returned in Error; Obtaining a Refund due from the Government**

If a financial institution needs to correct errors in their use of reason codes when returning funds, they should contact the agency receiving the return. Please see Chapter 7, Contacts, for major paying agency contact information. Any payment returned for "death" will cancel both the Direct Deposit authorization and the recipient's entitlement to that payment.

If you are due a refund from the government under ACH, regardless of whether you have returned too much, returned the wrong item(s), or the government debited you too much (e.g., on an ACH reclamation), follow these instructions to claim your refund.

Please note that the RDFI is not required to advance credit to the recipient for a payment returned in error. However, if the RDFI did advance credit, it should state this in any communication with the federal agency.

# **What to do if a Payment was Returned in Error**

#### **ACTION STEPS**

#### **1. Contact the federal agency that authorized the payment. Do not contact the government disbursing office.**

| Payment Type                                                       | Contact                                                                                                                                                                                            |
|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OPM Annuity<br>(formerly Civil Service Retirement)<br>"CIVIL SERV" | U.S. Office of Personnel Management<br>P.O. Box 45<br>Boyers, PA 16017<br>(724) 794-2005                                                                                                           |
| Social Security<br>"SOC SEC"                                       | SSA Program Service Center (Refer to SSA Program Service<br>Centers section in this chapter for appropriate addresses).                                                                            |
| Supplemental Social Security Income<br>"SUPP SEC"                  | Social Security Administration<br>Certification and Accounting Branch, Analyst<br>Room 3-A-2 East High Rise Building<br>6401 Security Boulevard<br>Baltimore, MD 21235<br>Email: obasa.tob@ssa.gov |
| Fiscal Service<br>"TreasuryDirect"                                 | Bureau of the Fiscal Service<br>Treasury Retail Securities Services<br>P.O. Box 9150<br>Minneapolis, MN 55480-9150<br>(844) 284-2676                                                               |

**Note:** *Include with your letter a debit advice, Return Item- Credit Form, and any other documents that confirm the duplicate or erroneous return.* 

| VA Compensation or Pension<br>"VA BENEFIT"                                                                               | None.                                                                   |  |
|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|--|
| Note: Payments returned to the VA in error cannot be recalled. They will be reissued to the recipient's<br>home address. |                                                                         |  |
| Railroad Retirement Board                                                                                                | Railroad Retirement Board Direct Deposit Coordinator<br>(312) 751-4704  |  |
| For all other payment types                                                                                              | The federal agency's local office listed in the telephone<br>directory. |  |

#### **2. Promptly notify the recipient of the error.**

If you erroneously reported death on the ACH return, advise the recipient to contact the originating federal agency immediately to reactivate payments.

Advise the recipient that the returned payment may be sent via check to their home. The recipient should contact the federal agency to ensure their current home address is on record and that payments are handled properly.

**3. Be aware that your incorrect notification of death to a federal authorizing agency (OPM, SSA, RRB) may result in a DNE being sent by the agency.** 

If a DNE is received, be sure to remove any electronic indicator or flag that would automatically return future payments to the account.

**4. Initiate a new enrollment to reactivate ACH payments. Please see Chapter 1, Enrollments, for more information.** 

**Note:** A copy of the *financial institution's original enrollment form may be sent to the federal agency if all the information is still correct.* 

# **Additional Information on TreasuryDirect Payments made in Error/Duplicate**

If a payment is made in error, or if a duplicate payment is made, the financial institution will receive either a written or electronic notice from TreasuryDirect that will include the following:

- x deposit account name,
- x deposit account number,
- x date of the improper payment, and
- x amount of the improper payment.

# **SSA Program Service Centers**

The Social Security Administration provides a listing of their regional Program Service Centers, which includes each service centers telephone number at this link: www.ssa.gov/representation/pct\_contact\_info\_54older.htm.

# **What to do if there are Duplicate Returns**

The table below shows what to do if there are duplicate returns.

| IF                                                                                                                 | THEN                                                                                                                                                                    | AND                                                                                              |
|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| two identical ACH returns are<br>made for the same payment                                                         | the government disbursing office will<br>automatically return the duplicate return                                                                                      | no further action is required<br>by the financial institution.                                   |
| an ACH return was sent, and the<br>same payment was returned by<br>check                                           | the financial institution should promptly write a<br>letter of explanation to the federal agency that<br>authorized the payment and include copies of<br>the following: | the financial institution awaits<br>further notification from the<br>authorizing federal agency. |
| the financial institution has been<br>debited (TFS, Notice of Debit) for<br>a payment that was already<br>returned | x<br>financial institution's claim for a refund<br>x<br>debit advice<br>x<br>other documentation that confirms the<br>duplicate return/debit action                     | Note: Only the federal agency<br>that authorized the payment<br>can make a refund.               |

## **Restoring Funds**

The authorizing federal agency will restore the funds after researching and verifying the request. The restoration will be made by the method agreed upon by the federal agency, the financial institution, and the recipient, with ACH being the preferred method.