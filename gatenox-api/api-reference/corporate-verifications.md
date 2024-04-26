# Corporate verifications

### Get the link for your client to start the corporate verification process (KYB)

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1/invites/corporates" method="post" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

The endpoint's body requires the following values to be included in the request:

<table><thead><tr><th width="203">Parameter</th><th width="109">Values</th><th width="316">Info</th><th>Required?</th></tr></thead><tbody><tr><td>email</td><td></td><td></td><td>Yes</td></tr><tr><td>redirect_url_success</td><td></td><td></td><td>No</td></tr><tr><td>redirect_url_failure</td><td></td><td></td><td>No</td></tr><tr><td>customer_id</td><td></td><td>external id to be used to match invitation with verification</td><td>No</td></tr></tbody></table>

### Get the list of all your company verifications and their details

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1/verifications" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1/verifications/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

### Get details about the company, which sent the application

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/company_details" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1/verifications/{verification_id}/graph" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

### The list of all people (directors, UBOs, individual shareholders, company representatives, others)

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/people" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/people/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/companies" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/companies/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

### The list of company directors

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/directors" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/directors/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

### The list of UBOs

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/ubos" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/ubos/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

### Company documents

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/company_documents" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_5_1.yaml" path="/api/v1//verifications/{verification_id}/company_documents/{id}" method="get" %}
[gatenox_api_1_5_1.yaml](../../.gitbook/assets/gatenox_api_1_5_1.yaml)
{% endswagger %}
