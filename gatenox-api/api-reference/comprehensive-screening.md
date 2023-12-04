---
description: >-
  Gatenox Hub provides Compliance Officers with a robust API, offering powerful
  screening capabilities for individuals, companies, and crypto addresses,
  ensuring comprehensive compliance checks.
---

# Comprehensive screening

### **Screening Individuals (KYC) and Companies (KYB)**

#### Instant screening

Gatenox Hub offers both individuals and companies screening against sanctions / PEP and criminal records.

* For Individuals - provide a surname, given names, and optional date of birth.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/individuals" method="post" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

* For Companies -  specifying company name.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/companies" method="post" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

Gatenox Hub offers two levels of sanctions/PEP/criminal records screening:

* Basic Screening (Free): Users with Gatenox Hub licenses can perform free basic screenings against OFAC, EU, UN, PL, UK, and Singapore sanctions lists.
* Premium Screening (Paid): A paid service, offering advanced checks against sanctions, PEP databases, and global criminal lists, providing a thorough compliance solution.

#### **Get the results of the screening**

Download a comprehensive list of checks and details from previous screenings using the following endpoints:

**Individuals**

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/individuals" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/individuals/{id}" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

**Companies**

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/companies" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/companies/{id}" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

Associated files (if any) can be downloaded via an additional endpoint.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/attachments/{rest}" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

### **Crypto Address Verification (Blockchain Analytics)**&#x20;

#### Request a report

Verify crypto addresses by providing the blockchain and the specific address.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/crypto_address" method="post" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

#### **Get the report**

Receive a comprehensive crypto address report, including risk assessment, financial analysis (historical balance), and a list of owned tokens.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/crypto_address" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/checks/crypto_address/{id}" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

Download the detailed report in PDF format for further analysis and record-keeping.

{% swagger src="../../.gitbook/assets/gatenox_api_1_3_4.yaml" path="/api/v1/attachments/{rest}" method="get" %}
[gatenox_api_1_3_4.yaml](../../.gitbook/assets/gatenox_api_1_3_4.yaml)
{% endswagger %}

