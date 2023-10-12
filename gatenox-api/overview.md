---
description: >-
  Leverage the power of Gatenox API to create integrations with your company's
  tools and services.
---

# Overview

{% hint style="info" %}
The Gatenox API is currently in **beta** version. This means you should not rely on its availability, and that it may change without prior warning.
{% endhint %}

### Welcome to the Gatenox API!

Gatenox API is a powerful tool that allows you to easily access and manage verification data.

Our API is designed with simplicity and ease of use in mind. Whether you're a developer building a new application or a business owner looking for a streamlined way to manage verification data, Gatenox API has you covered.

So why wait? Start using Gatenox API today and experience the power of our verification data services for yourself!

#### Cases management

With our API, you can quickly check the status and result of incoming verifications (both individual and corporate), giving you the ability to make informed decisions in real-time.

In addition to status and result information, Gatenox API provides access to detailed verification data, including company details, business representatives' data, shareholders' structure, and all documents attached to the verification. This information is invaluable for making informed decisions and mitigating risk.

#### Verified cryptocurrency addresses

The function checks whether a specified cryptocurrency address is included in a list of approved and verified cryptocurrency addresses, also known as a whitelist.

The whitelist comprises cryptocurrency addresses that have undergone a verification process (case management) and the user has set the risk score for the case.

If the address is found on the whitelist, the function returns a positive verification status and also provides additional information. The positive result includes a list of reviews in which the cryptocurrency address has been previously verified, as well as a score associated with the address (optional) and risk score associated with the case, indicating the level of confidence in the verification. Furthermore, the company name responsible for the verification and the date of the most recent verification are also provided.

These details can be useful in assessing the credibility and reliability of the cryptocurrency address and can help prevent fraudulent or malicious activities.

### Authentication

Authentication is provided through a Bearer Token, which ensures that only authorized users have access to the API. This added layer of security helps to protect sensitive data and ensure that your information remains secure.&#x20;

### Rate limits

Gatenox API is designed with scalability in mind, which means that you can use it to process large amounts of verification data quickly and efficiently. However, to ensure that our service remains available to all users, we do have rate limits in place.

Currently, there are no rate limits for our beta version, which means that you can use Gatenox API to its full potential without worrying about restrictions. However, as we continue to refine and improve our service, we may implement rate limits to ensure that all users have fair access to our platform.

### Errors

In the event that you do encounter an error while using Gatenox API, our platform provides detailed error messages that can help you quickly identify and resolve the issue. Additionally, our API documentation provides detailed information on how to use our platform, as well as code examples and links to other resources that can help you get the most out of our service.

### Webhooks

Webhooks are an essential feature of modern software and applications that enable seamless communication between different systems. GatenoxAPI's webhook functionality empowers businesses to automate their workflows and receive real-time updates when specific events occur.

Using our webhooks, your business can connect its applications and receive immediate notifications when specific events happen, such as a new incoming case, finished assessment, or result of a sanctions check. This functionality allows businesses to react quickly to important events and take immediate action to serve their customers better.

In summary, GatenoxAPI's webhook feature is a powerful tool that enables businesses to automate their workflows, stay informed of critical events, and provide better customer service.

### API Reference

We invite you to explore our API documentation to learn more about Gatenox API's features and capabilities. With our powerful verification data services, you can take your business to the next level and make informed decisions with confidence.

### Support

If you encounter any issues while using Gatenox API, our dedicated support team is here to help. You can contact us directly through our support channel, and we'll work with you to resolve any problems you encounter as quickly as possible. If you have any questions or issues, please contact the [Gatenox Support](mailto:support@gatenox.com).

<table data-card-size="large" data-view="cards"><thead><tr><th data-type="content-ref"></th><th></th><th data-hidden data-type="content-ref"></th><th data-hidden data-type="rating" data-max="5"></th><th data-hidden data-type="content-ref"></th><th data-hidden data-type="files"></th></tr></thead><tbody><tr><td><a href="authentication.md">authentication.md</a></td><td>Create an API access token and authenticate your API requests.</td><td><a href="authentication.md">authentication.md</a></td><td>null</td><td><a href="authentication.md">authentication.md</a></td><td></td></tr><tr><td><a href="rate-limiting.md">rate-limiting.md</a></td><td>Understand how API requests are rate limited.</td><td><a href="rate-limiting.md">rate-limiting.md</a></td><td>null</td><td><a href="rate-limiting.md">rate-limiting.md</a></td><td></td></tr><tr><td><a href="errors.md">errors.md</a></td><td>Learn about API errors, how they're structured and how to handle them.</td><td></td><td>null</td><td><a href="errors.md">errors.md</a></td><td></td></tr><tr><td><a href="webhooks.md">webhooks.md</a></td><td>Configure Gatenox Hub to notify your system about important events</td><td></td><td>null</td><td></td><td></td></tr><tr><td><a href="api-reference/">api-reference</a></td><td>Read the reference documentation for the exposed API resources and their operations.</td><td></td><td>null</td><td><a href="api-reference/">api-reference</a></td><td></td></tr></tbody></table>

