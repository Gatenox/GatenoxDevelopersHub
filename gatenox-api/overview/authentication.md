---
description: >-
  Leverage the power of Gatenox API to create integrations with your company's
  tools and services.
---

# Authentication

The Gatenox API uses company access tokens to authenticate requests. You can view and manage your access tokens in the [Company information](broken-reference) tab in the Settings menu of your Gatenox company account.

API requests are authenticated using the [Bearer Auth scheme](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication#authentication\_schemes). To authenticate a request, provide the token in the `Authorization` header of the request:

{% code overflow="wrap" %}
```bash
curl -H "Authorization: Bearer <your_access_token>" https://api.app.gatenox.com/api/v1/verifications
```
{% endcode %}

Access tokens are tied to the Gatenox company account for which they were created. A token provides full level of access to its associated Gatenox company account.

{% hint style="warning" %}
Please be sure to keep your API access tokens secure! Do not share them in emails, chat messages, client-side code, or publicly accessible sites.

If you have accidentally shared an API access token publicly, you can revoke it in the [Company information](broken-reference) of your Gatenox company account by clicking the "<mark style="color:red;">**Block API key**</mark>" link next to the token.
{% endhint %}
