---
description: Get notification from Compliance Cloud about your data
---

# Webhooks

Gatenox webhooks are an important feature that allows downstream systems to receive notifications of the status of Customer KYC Applications.&#x20;

The webhook notifications are highly customizable, allowing you to choose the types of events you want to receive notifications for (new application received, changes made, process completed). This means that you can tailor the notifications to your specific needs and preferences, ensuring that you receive the information you need in a timely and effective manner.

Gatenox webhooks are a simple, yet powerful way to stay informed about the status of your review requests, enabling you to work more efficiently and effectively.

To register your webhook endpoint please follow the guide here: [company-information.md](../general-settings/company-information.md "mention").

Below you can find an example of the webhook endpoint.

## Webhook endpoint example

<mark style="color:green;">`POST`</mark> `https://example.com/webhook`

An example of a webhook endpoint.

#### Request Body

| Name                                               | Type   | Description                                          |
| -------------------------------------------------- | ------ | ---------------------------------------------------- |
| event<mark style="color:red;">\*</mark>            | string | Event type.                                          |
| new\_state<mark style="color:red;">\*</mark>       | string | New status of the review process.                    |
| prev\_state<mark style="color:red;">\*</mark>      | string | Previous status of the review process.               |
| verification\_id<mark style="color:red;">\*</mark> | string | Id of verification (review) related to notification. |

{% tabs %}
{% tab title="200: OK " %}
```json
{
  "event": "state_change",
  "new_state": "qa",
  "prev_state": "in_progress",
  "verification_id": "21c1a29c-68e0-40a5-b6c8-6f85350213b8"
}
```
{% endtab %}
{% endtabs %}
