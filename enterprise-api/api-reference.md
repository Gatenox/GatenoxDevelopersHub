---
description: >-
  As a Gatenox Verifier, You mind need Enterprise API to control incoming
  applications. This chapter describes all You need to know about it.
---

# API reference

## How to start?

To use Enterprise API You need to possess Gatenox API Key. Please, contact our crew to get it at: [support@gatenox.com](mailto:support@gatenox.com).

{% code title="Gatenox API Key example:" %}
```
GATENOX_API_KEY=984998a8-374d-4665-91a6-cfe042a7aa76
```
{% endcode %}

To authorize as the proper Enterprise API holder provide the above header in the request.

## Applications&#x20;

Our API provides the possibility to control all the applications, which Your company received as a Verifier.

This endpoint provides lots of filters and search helpers.

Application - package of information, which someone sends to Your company for verification; we call them also: "reviews" or "cases"

{% swagger src="../.gitbook/assets/merged.yaml" path="/reviews" method="get" %}
[merged.yaml](../.gitbook/assets/merged.yaml)
{% endswagger %}

## Single application

You can also monitor particular application if You wait for status or data changes. All You need to do is to store its ID somewhere.

{% swagger src="../.gitbook/assets/merged (2).yaml" path="/reviews/{id}" method="get" %}
[merged (2).yaml](<../.gitbook/assets/merged (2).yaml>)
{% endswagger %}

## Our swagger

Coming soon...
