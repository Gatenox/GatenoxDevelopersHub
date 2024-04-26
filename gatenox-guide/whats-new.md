---
description: >-
  Information about new features implemented and bug fixes corrected within each
  release
---

# What's new?

{% hint style="info" %}
If you are looking for a list of changes in our API please check [api-versions-history.md](../gatenox-api/api-reference/api-versions-history.md "mention")
{% endhint %}

### 2024-04-25

1. Allow to add customer ID to corporate KYC invitations sent to clients via API [#api-version-1.5.1](../gatenox-api/api-reference/api-versions-history.md#api-version-1.5.1 "mention") and [#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb](../gatenox-api/api-reference/corporate-verifications.md#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb "mention")
2. Display the list of corporate invitations sent  [#how-do-you-send-an-invitation-to-the-corporate-client](../compliance-cloud-how-to/cases-management/corporate-verifications.md#how-do-you-send-an-invitation-to-the-corporate-client "mention")
3. Verification lists (individual[#risk-assessment-process](../compliance-cloud-how-to/cases-management/individual-verifications.md#risk-assessment-process "mention") and corporate [#risk-assessment-process](../compliance-cloud-how-to/cases-management/corporate-verifications.md#risk-assessment-process "mention") ) now display the business owner's email in the "Name" field, allowing search using this data.

Bug fixes:

1. Login/logout/"401 unauthorized" error problems after inactivity time.
2. "Business email" field visibility.
3. Disable the "Continue" button when a person/company is added to business representatives/shareholders/UBOs lists.
4. Refresh the tabs in the menu after the context is changed.
5. Other minor fixes.

### 2024-04-10

1. Integrate new crypto address report provider - AMLBot ( [#check-crypto-addresses](../compliance-cloud-how-to/comprehensive-screening/#check-crypto-addresses "mention") )
2. Show the brand name in the profile subtitle ( [manage-company-details](../id-node-how-to/create-and-complete-company-profile/manage-company-details/ "mention") )
3. Order context list alphabetically ( [multiple-company-profiles.md](../compliance-cloud-how-to/multiple-company-profiles.md "mention") )
4. Allow to turn on / off email notifications about case status changes ( [account-information.md](../general-settings/account-information.md "mention") ).

Bug fixes:

1. "Add assessment" was not displayed upon opening the case for the first time.
2. The ToDo list did not display "at\_least" rules (for example "Provide at least one director").

### 2024-03-25

1. Allow the Compliance Officer to mark the sanctions / PEP / criminal records as relevant/irrelevant. [identified-issues.md](../compliance-cloud-how-to/risk-assessment/identified-issues.md "mention")
2. Allow the Compliance Officer to upload additional files related to the case. [files-1.md](../compliance-cloud-how-to/risk-assessment/files-1.md "mention")
3. Filters are now cleared after a new request for an entity or crypto address check is performed. [check-crypto-addresses.md](../compliance-cloud-how-to/comprehensive-screening/check-crypto-addresses.md "mention") [check-sanctions-pep-criminal-records.md](../compliance-cloud-how-to/comprehensive-screening/check-sanctions-pep-criminal-records.md "mention")

### 2024-03-13

1. Allow to mark section as reviewed during the risk assessment process [#review-progress](../compliance-cloud-how-to/risk-assessment/#review-progress "mention")
2. Allow to return the case from QA for additional analysis [#risk-assessment-process](../compliance-cloud-how-to/cases-management/corporate-verifications.md#risk-assessment-process "mention") and[#assessment-with-qa](../compliance-cloud-how-to/risk-assessment/final-assessment.md#assessment-with-qa "mention")
3. The industry list has been expanded  [#fields](../id-node-how-to/create-and-complete-company-profile/manage-company-details/business-details.md#fields "mention")
4. Add a button to refresh the crypto address wallet report list [check-crypto-addresses.md](../compliance-cloud-how-to/comprehensive-screening/check-crypto-addresses.md "mention")

Bug fixes:

* Performance optimized,
* Updated RWD design to correctly display Gatenox Hub on mobile devices,
* Show the "Identified issues" tab, even if no entity is found on sanctions lists,
* Hide the "Continue" button, while adding a person/company to the list,
* Other minor fixes.

### 2024-02-28

New data can be collected for individuals: email address and crypto wallet.

### 2024-02-21

The new KYC provider has been integrated [kyc-process](../id-node-how-to/kyc-process/ "mention")

### 2024-02-09

1. Allow the User to remove unfinished onboarding from the list [#delete-onboarding](../id-node-how-to/share-company-profile/start-onboarding.md#delete-onboarding "mention")
2. Add Terms\&Conditions consent during individual KYC process [#welcome-to-the-kyc-process](../id-node-how-to/i-received-email-from-gatenox/invitation-for-kyc.md#welcome-to-the-kyc-process "mention")

### 2024-02-02

Bug fixes:

* crypto address reports - fix to simplified and standard reports [check-crypto-addresses.md](../compliance-cloud-how-to/comprehensive-screening/check-crypto-addresses.md "mention")

### 2024-01-31

Show a list of companies/individuals invited to the onboarding process [#invitation-and-data-gathering-process-onboarding](../compliance-cloud-how-to/cases-management/corporate-verifications.md#invitation-and-data-gathering-process-onboarding "mention")

Bug fixes:

* correct layouts and added loading screens

### 2024-01-10

Allow to add customer ID to individual KYC invitations sent to clients via API [#api-version-1.3.5](../gatenox-api/api-reference/api-versions-history.md#api-version-1.3.5 "mention")

### 2023-12-14

Referral program [referral-code.md](../compliance-cloud-how-to/start-onboarding-customers-with-gatenox/referral-code.md "mention")

### 2023-12-05

1. Allow Users to check sanctions / PEP / criminal records without the case [check-sanctions-pep-criminal-records.md](../compliance-cloud-how-to/comprehensive-screening/check-sanctions-pep-criminal-records.md "mention")
2. Allow Users to check a crypto address without the case [check-crypto-addresses.md](../compliance-cloud-how-to/comprehensive-screening/check-crypto-addresses.md "mention")

### 2023-11-30

CEIDG (Polish sole proprietorship register) integration

### 2023-10-26

Ongoing monitoring of clients - recurring reviews [company-information.md](../general-settings/company-information.md "mention")

### 2023-09-21

Experimental feature: Document's AI - summarizes the document content and chats with AI about the document [document-ai.md](../compliance-cloud-how-to/risk-assessment/document-ai.md "mention")

### 2023-08-01

Communication Tool - allow Compliance Teams to ask questions to the cases and receive answers from Business Users [in-app-communication-tool.md](../compliance-cloud-how-to/risk-assessment/in-app-communication-tool.md "mention")

### 2023-06-23

The new KYC provider has been integrated [kyc-process](../id-node-how-to/kyc-process/ "mention")

### 2023-05-23

Allow to invite and review individuals' profiles (KYC process) [#how-to-send-an-invitation-to-the-client](../compliance-cloud-how-to/cases-management/individual-verifications.md#how-to-send-an-invitation-to-the-client "mention")

### 2023-03-20

Gatenox Hub revamp - new service design

### 2023-02-01

Integration with crypto address reports provider (Coinfirm) [#crypto-address-verification](../compliance-cloud-how-to/risk-assessment/company-details.md#crypto-address-verification "mention")

### 2023-01-13

Multi-user and multi-context accounts [users-management.md](../general-settings/users-management.md "mention")

### 2022-12-28

Internal KYC process [complete-kyc-details.md](../id-node-how-to/kyc-process/complete-kyc-details.md "mention")
