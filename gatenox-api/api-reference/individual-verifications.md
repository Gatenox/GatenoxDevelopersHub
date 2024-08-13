# Individual verifications

### Get the link for your client to start the individual verification process (KYC)

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/invites/individuals" method="post" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

The endpoint's body requires the following values to be included in the request:

<table><thead><tr><th width="203">Parameter</th><th width="109">Values</th><th width="316">Info</th><th>Required?</th></tr></thead><tbody><tr><td>email</td><td></td><td>The customer's email address, where the invitation will be sent. I will also be displayed on the "Individual verifications" tab on the lists.</td><td>Yes</td></tr><tr><td>redirect_url_success</td><td></td><td>The URL, where the customer will be redirected if the KYC process finishes successfully.</td><td>No</td></tr><tr><td>redirect_url_failure</td><td></td><td>The URL, where the customer will be redirected if the KYC process fails.</td><td>No</td></tr><tr><td>customer_id</td><td></td><td>external id to be used to match invitation with verification</td><td>No</td></tr></tbody></table>

### Get the list of all your individual verifications and their details

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals/{id}" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals/{verification_individual_id}/people" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals/{verification_individual_id}/addresses" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals/{verification_individual_id}/addresses/{id}" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/verification_individuals/{id}/audit_log" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

### Individual documents&#x20;

{% swagger src="../../.gitbook/assets/gatenox_api_1.5.1.yaml" path="/api/v1/attachments/{rest}" method="get" %}
[gatenox_api_1.5.1.yaml](../../.gitbook/assets/gatenox_api_1.5.1.yaml)
{% endswagger %}

### Upload externally calculated risk score

{% swagger src="../../.gitbook/assets/gatenox_api_1_9_1.yaml" path="/api/v1/webhooks/external_risk_score" method="post" %}
[gatenox_api_1_9_1.yaml](../../.gitbook/assets/gatenox_api_1_9_1.yaml)
{% endswagger %}
