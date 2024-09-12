# Corporate verifications

### Get the link for your client to start the corporate verification process (KYB)

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/invites/corporates" method="post" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

The endpoint's body requires the following values to be included in the request:

<table><thead><tr><th width="203">Parameter</th><th width="109">Values</th><th width="316">Info</th><th>Required?</th></tr></thead><tbody><tr><td>email</td><td></td><td>The customer's email address, where the invitation will be sent. I will also be displayed on the "Corporate verifications" tab on the lists.</td><td>Yes</td></tr><tr><td>redirect_url_success</td><td></td><td>The URL, where the customer will be redirected if the KYC process finishes successfully.</td><td>No</td></tr><tr><td>redirect_url_failure</td><td></td><td>The URL, where the customer will be redirected if the KYC process fails.</td><td>No</td></tr><tr><td>customer_id</td><td></td><td>External id to be used to match invitation with verification</td><td>No</td></tr><tr><td>completeness_profile_id</td><td></td><td>The verification profile to be used to gather data during the onboarding process.</td><td>No</td></tr><tr><td>send_notification</td><td></td><td>This parameter indicates if Gatenox Hub should send the email to the customer. By default, it is set to false.</td><td>No</td></tr></tbody></table>

### Get the list of all your verification profiles

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/contexts/{context_id}/completeness_profiles" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}



### Upload externally calculated risk score

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/webhooks/external_risk_score" method="post" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### Get the list of all your company verifications and their details

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### Upload externally calculated risk score

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/webhooks/external_risk_score" method="post" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### Change the profile of gathered data during the review process

It allows to change the scope of data requested from the corporate client and automatically sends the case to the customer changing the status to "Request for data update".

You can get the "completeness\_profile\_id" from the "Settings" menu. On the "Company Information" tab, in the "Onboarding profiles" section, select a profile name, and the "profile id" will be displayed.

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/state/request_data_update" method="post" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### Get details about the company, which sent the application

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/company_details" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/graph" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### The list of all people (directors, UBOs, individual shareholders, company representatives, others)

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/people" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/people/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/companies" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/companies/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### The list of company directors

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/directors" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/directors/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### The list of UBOs

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/ubos" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/ubos/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

### Company documents

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/company_documents" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/verifications/{verification_id}/company_documents/{id}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/attachments/{rest}" method="get" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}
