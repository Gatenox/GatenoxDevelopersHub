# Integration options with Gatenox Hub

### Corporate KYC Integration

#### Integration scheme

Streamline your corporate onboarding process with Gatenox HUB's Corporate KYC integration. By embedding a referral link beneath a designated button or link on your webpage, you can effortlessly direct potential corporate clients to the Gatenox Hub. Upon clicking, these clients will be seamlessly redirected to the platform where they can establish their accounts.

You can use the following button to inform users about verification processes via Gatenox:

<figure><img src="../../.gitbook/assets/apply_via_gatenox.png" alt="&#x22;Apply via Gatenox&#x22; button"><figcaption><p>"Apply via Gatenox" button</p></figcaption></figure>

{% tabs %}
{% tab title="button.html" %}
```
<a class="GatenoxButton" href="https://app.gatenox.com/referrals/join/GATENOX">
	<div class="GatenoxButton-caption">Apply via Gatenox</div>
</a>
```

The "GATENOX" code in the href link should be replaced with your referral code. It is available to copy from the "Settings" menu, tab "Company information" ([#where-is-my-referral-code](referral-code.md#where-is-my-referral-code "mention")).
{% endtab %}
{% endtabs %}

#### Why account is created for corporate users?

This integration facilitates direct communication between Compliance Officers and Business users, enabling efficient KYC processing.

Moreover, Gatenox HUB's future updates will allow corporate clients to enhance and revise their company profiles without the need to re-submit identical documents and data. This feature simplifies the ongoing compliance relationship, saving time and effort for both your clients and your team.

### Individual KYC Integration

Simplify individual KYC processes with Gatenox HUB's Individual KYC integration. For enhanced usability, individual users are not required to create accounts. Instead, Gatenox HUB generates unique verification links for each individual. Here's how it works:

1. A user registers on your portal.
2. To fulfill KYC requirements, your portal initiates an API call [#api-v1-invites-individuals](../../gatenox-api/api-reference/individual-verifications.md#api-v1-invites-individuals "mention") to obtain a unique verification link from Gatenox.
3. The verification link is then presented to the logged-in user.
4. Upon clicking the link, the user is seamlessly redirected to Gatenox HUB, where they can provide their KYC details without setting up an account.

### Gathering results

The information submitted by individuals or companies can be efficiently downloaded into your system through Gatenox's API. The description of API can be found here:

* Corporate verifications: [#get-the-list-of-all-your-company-verifications-and-their-details](../../gatenox-api/api-reference/corporate-verifications.md#get-the-list-of-all-your-company-verifications-and-their-details "mention")
* Individual verifications: [#get-the-list-of-all-your-individual-verifications-and-their-details](../../gatenox-api/api-reference/individual-verifications.md#get-the-list-of-all-your-individual-verifications-and-their-details "mention")

You can download this data shortly after receiving it, or perform a risk assessment in Gatenox Hub and then download the finalized data to your system.

This feature ensures that the KYC data collected is easily accessible and can be utilized within your organization's processes.

By leveraging these integration options, you can enhance the efficiency and effectiveness of your KYC processes, enabling smooth interactions between your clients and compliance teams while maintaining high security and data integrity.
