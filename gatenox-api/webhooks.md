---
description: Get notification from Compliance Cloud about your data
---

# Webhooks

Gatenox webhooks are an important feature that allows downstreem systems to receive notifications of the status of Customer KYC Applications.&#x20;

The webhook notifications are highly customizable, allowing you to choose the types of events you want to receive notifications for (new application received, changes made, process completed). This means that you can tailor the notifications to your specific needs and preferences, ensuring that you receive the information you need in a timely and effective manner.

Gatenox webhooks are a simple, yet powerful way to stay informed about the status of your review requests, enabling you to work more efficiently and effectively.

To register your webhook endpoint please follow the guide here: [company-information.md](../general-settings/company-information.md "mention").

Below you can find an example of webhook endpoint.

{% swagger method="post" path="/webhook" baseUrl="https://example.com" summary="Webhook endpoint example" %}
{% swagger-description %}
An example of a webhook endpoint.
{% endswagger-description %}

{% swagger-parameter in="body" name="verification_id" type="string" required="true" %}
Id of verification (review) related to notification.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="event" required="true" type="string" %}
Event type.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="new_state" type="string" required="true" %}
New status of the review process.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="prev_state" type="string" required="true" %}
Previous status of the review process.
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "event": "state_change",
  "new_state": "qa",
  "prev_state": "in_progress",
  "verification_id": "21c1a29c-68e0-40a5-b6c8-6f85350213b8"
}
```
{% endswagger-response %}
{% endswagger %}
