# Risk score recalculation

On the "Review" screen, Compliance Officers can find the "Request risk score recalculation" button. This button allows you to request an externally calculated risk score for the case.

{% hint style="info" %}
The integration with the external risk score calculation system can be configured in the Settings [company-information.md](../../general-settings/company-information.md "mention") and uploaded using Gatenox API [#upload-externally-calculated-risk-score](../../gatenox-api/api-reference/corporate-verifications.md#upload-externally-calculated-risk-score "mention")
{% endhint %}

<figure><img src="../../.gitbook/assets/Review company - request for risk score.png" alt=""><figcaption><p>Review - request for risk score calculation</p></figcaption></figure>

After confirming the request, the case will change the status to "Risk score recalculation".

<figure><img src="../../.gitbook/assets/Corporate verifications - risk score recalculation.png" alt=""><figcaption><p>Corporate verifications list - request for risk score recalculation</p></figcaption></figure>

Following the response from the external system (including risk score recalculation data), the status reverts to "In Progress," and the "Last Update" field is automatically populated with the date and time of the latest update.

In case, when you want to resign from waiting for risk score recalculation, you may revoke the request using the "Revoke risk score recalculation".&#x20;

<figure><img src="../../.gitbook/assets/Review company - revoke requestfor risk score.png" alt=""><figcaption></figcaption></figure>
