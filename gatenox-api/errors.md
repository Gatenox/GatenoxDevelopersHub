---
description: >-
  Leverage the power of Gatenox API to create integrations with your company's
  tools and services.
---

# Errors

{% hint style="info" %}
The Gatenox API is currently in **beta** version. This means you should not rely on its availability, and that it may change without prior warning.
{% endhint %}

Gatenox API uses conventional HTTP response codes to indicate the success or failure of an API request.

As a general rule:

* Codes in the `2xx` range indicate success
* Codes in the `4xx` range indicates incorrect or incomplete parameters (e.g. a required parameter was omitted, or an operation failed with a 3rd party, etc.)
* Codes in the `5xx` range indicates an error with Gatenox's servers.

Gatenox API also outputs an error message and an error code formatted in JSON:

```json
{
    "error": {
        "code": 404,
        "message": "Page not found in this space"
    }
}
```
