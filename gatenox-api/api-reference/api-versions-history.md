---
description: >-
  Here, we provide a comprehensive record of the evolution of our API
  specifications.
---

# API versions - history

Explore the timeline to gain insights into the enhancements, updates, and optimizations that have been meticulously implemented to ensure a seamless and robust experience for our users and developers.

Stay informed about the continuous evolution of Gatenox Hub's API capabilities.

{% hint style="info" %}
If you are looking for information about new features on the Gatenox Hub platform please check[whats-new.md](../../gatenox-guide/whats-new.md "mention")
{% endhint %}

## API version 1.10.0

:date: Publish date: **2024-09-06**

:notebook: Release notes:

1. Allow to get case data in the "new" status
2. Get the list of verification profiles [#get-the-list-of-all-your-verification-profiles](corporate-verifications.md#get-the-list-of-all-your-verification-profiles "mention")
3. Upload externally calculated risk score [#upload-externally-calculated-risk-score](corporate-verifications.md#upload-externally-calculated-risk-score "mention")
4. Set verification profile within the invitation [#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb](corporate-verifications.md#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb "mention")

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_10_0.yaml" %}



## API version 1.9.1

:date: Publish date: **2024-08-14**

:notebook: Release notes:

1. Updated endpoint to check crypto address allowing to receive sync answer and limit the response to c-score only [#crypto-address-verification-blockchain-analytics](comprehensive-screening.md#crypto-address-verification-blockchain-analytics "mention").

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_9_1 (1).yaml" %}

## API version 1.8.0

:date: Publish date: **2024-07-24**

:notebook: Release notes:

1. Allow uploading of company profile data before creating a company profile. [#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb](corporate-verifications.md#get-the-link-for-your-client-to-start-the-corporate-verification-process-kyb "mention")
2. Allow the change of the scope of data requested from the corporate customer during the review process. [#change-the-profile-of-gathered-data-during-the-review-process](corporate-verifications.md#change-the-profile-of-gathered-data-during-the-review-process "mention")

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_8_0.yaml" %}

## API version 1.6.0

:date: Publish date: **2024-06-19**

:notebook: Release notes:

1. Allow uploading externally calculated risk scores to the case:&#x20;
   1. Settings [company-information.md](../../general-settings/company-information.md "mention")
   2. Corporate [#upload-externally-calculated-risk-score](corporate-verifications.md#upload-externally-calculated-risk-score "mention")
   3. Individual [#upload-externally-calculated-risk-score](individual-verifications.md#upload-externally-calculated-risk-score "mention")

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_6_0.yaml" %}

## API version 1.5.3

:date: Publish date: **2024-05-10**

:notebook: Release notes:

1. Bugfix - include "invitation\_url" in the response to /invite/corporates
2. Allow API users to decide, if Gatenox Hub should send an invitation email to the corporate customer. By default, it is set to false.

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_5_3.yaml" %}

## API version 1.5.1

:date: Publish date: **2024-04-25**

:notebook: Release notes:

1. Add "customer\_id" to connect invitations and verifications with external systems ( [corporate-verifications.md](corporate-verifications.md "mention")).

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" %}

## API version 1.4.0

:date: Publish date: **2024-04-10**

:notebook: Release notes:

1. Allow requesting for crypto address reports from AMLBot.

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_4_0.yaml" %}

## API version 1.3.5

:date: Publish date: **2024-01-11**

:notebook: Release notes:

1. Add "customer\_id" to connect invitations and verifications with external systems ( [individual-verifications.md](individual-verifications.md "mention")).

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_3_5.yaml" %}

## API version 1.3.4

:date: Publish date: **2023-11-30**

:notebook: Release notes:

1. Add "personal\_verification\_id" to connect invitations with verifications ( [individual-verifications.md](individual-verifications.md "mention")).

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_3_4 .yaml" %}

## API version 1.3.2

:date: Publish date: **2023-11-23**

:notebook: Release notes:

1. Add API support for sanctions / PEP / criminal records check without creating the case.
2. Add API support for crypto address verification (report) without creating the case.
3. Add audit log information to the details in the individual verification endpoint.

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_3_2.yaml" %}

## API version 1.3.1

:date: Publish date: **2023-10-11**

:notebook: Release notes:

1. Allow to define redirect URL at the end of individual KYC process.

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_1_3_1.yaml" %}

## API version 1.3.0

:date: Publish date: **2023-06-15**

:notebook: Release notes:

1. API support for invite to individual KYC verification process.

:file\_folder: File:

{% file src="../../.gitbook/assets/gatenox_api_v1.3.0.yaml" %}
