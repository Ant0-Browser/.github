# Ant0 CLA privacy notice

Version 1.0, 2026-11-23. This notice explains what personal data we collect when you sign an Ant0 Contributor Licence Agreement (CLA), or are listed in an organisation's CLA, and what we do with it. It is given under Articles 13 and 14 of the UK GDPR.

## Who we are

**RENEWBYTE LABS LTD**, Company No. 17257779, 128 City Road, London, EC1V 2NX, is the controller of your CLA data. It is registered with the Information Commissioner's Office (ICO) as a controller. Contact: cla@ant0.link.

The hosted CLA Assistant service, run by SAP SE, also holds the data it collects for its own service. For that copy, SAP is an independent controller, not a joint controller with us, and handles the data under its own terms (https://gist.github.com/CLAassistant/3a73e4cd729c9d0a6e30).

## What we collect

**If you sign the individual CLA:**
- the full name you type;
- your GitHub username and numeric user ID;
- your email address (read from your GitHub account through the CLA Assistant app's email permission, or entered by you);
- the date and time you signed;
- the CLA version you signed, with a hash of its text;
- the pull request that asked you to sign.

**If an organisation lists you in its entity CLA (Schedule A):**
- your name, GitHub username, work email and role;
- the dates you were added and removed.

We get this data from your organisation, not from you. That is why Article 14 applies.

**If you sign the entity CLA for an organisation:** your name, title, email and signature.

When you sign, we also record your confirmation that you are 18 or over. Only people aged 18 or over can sign.

## Why we use it, and our legal basis

| Purpose | Legal basis (UK GDPR) |
|---|---|
| To make and keep a record of the licence you grant, and to check on each pull request that a CLA covers it | Art 6(1)(b): the contract (the CLA) with you |
| To record the people an organisation authorises in Schedule A, and to check their pull requests | Art 6(1)(f): our legitimate interest, and the organisation's, in knowing who is covered by its licence |
| To record who signed an entity CLA for an organisation, and their authority | Art 6(1)(f): our legitimate interest in a valid, provable agreement with the organisation |
| To defend or bring legal claims about contributed code | Art 6(1)(f): legitimate interest in establishing, exercising or defending legal claims |

**Signing is a condition of merge.** We can't merge a pull request to ant0-mcp, ant0-sdk or ant0-cli unless a CLA covers it. You don't have to sign, but if you don't, we can't accept your contribution. The ant0-examples repository needs no CLA.

## Who receives it

- **SAP SE**, which runs CLA Assistant. Its data is stored in a database on Microsoft Azure in the EU.
- **GitHub, Inc.** The signing status shows on your pull request, and GitHub processes your account data under its own privacy statement.
- **Microsoft (Azure)**, as SAP's hosting provider.
- **Our professional advisers**, and a buyer of our business or of the project, if that happens (CLA clause 9 / entity clause 8).

We don't sell this data, and we don't use it for marketing.

**Where our own copies are kept.**
- Our exports of signature records (CSV files from CLA Assistant) and signed entity CLAs (PDF copies) are kept in private, access-controlled storage.
- Only the people at the Company who need them to manage contributions can reach them.

**No automated decisions.** We make no decisions about you based solely on automated processing, including profiling, that have legal or similarly significant effects (Art 13(2)(f)). The CLA bot only checks whether a signature exists. Maintainers decide whether to merge.

## Transfers outside the UK

- CLA Assistant data is stored in the EU, which the UK treats as adequate.
- SAP's terms say it may transfer data outside the EEA under standard contractual clauses. You can ask SAP (cla_assistant@sap.com) for details of these safeguards, including how they apply to UK data.
- GitHub, Inc. is in the US and processes your GitHub account data as a separate controller under its own privacy statement (https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), including how it protects transfers. Apart from the CLA check status shown on your pull request, your CLA data is not sent to GitHub.

## How long we keep it

We keep your signature record for as long as we distribute code containing your contribution, plus 6 years. This lets us show the licence if a claim is made (Limitation Act 1980).

Schedule A entries are kept on the same basis, counted from the person's last contribution.

## Your rights

You have the right to:
- access your data;
- have it corrected;
- object to processing based on legitimate interests;
- ask for restriction;
- ask for erasure;
- data portability, where it applies.

**Limits on erasure.** We may refuse to erase a signature record while we still need it to show the licence for code we distribute, or to establish or defend legal claims (Art 17(3)(e)). If you stop the CLA applying to future contributions, the record for past contributions stays.

To use your rights, email cla@ant0.link. For data SAP holds, you can also contact cla_assistant@sap.com.

## Complaints

You can complain to the Information Commissioner's Office (ICO), https://ico.org.uk/make-a-complaint/, phone 0303 123 1113. Please contact us first so we can try to help.

## Changes

We'll publish any change to this notice at https://github.com/Ant0-Browser/.github/blob/main/legal/cla-privacy-notice.md and update the version above.
