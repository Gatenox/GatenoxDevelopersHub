# Business Financials

The "Business Financials" screen is where users can enter and manage various financial information related to their company.

On this screen, users can update their company's financial information as needed. They may need to make changes if their sources of funding change, or if they start accepting cryptocurrency payments. Keeping this information up-to-date is important for tax reporting purposes and for maintaining accurate financial records. It's important to note that the information entered on this screen is typically sensitive and should be kept confidential.

#### Fields

{% hint style="warning" %}
The fields listed in documentation may differ from those displayed in your profile. The specific fields required by the company you are onboarding with depend on their specific data needs.
{% endhint %}

Here is a brief description of each field:

1. TAX number: This field allows users to enter their company's tax identification number, which is typically assigned by the government.
2. Company sources of funds: This field allows users to specify the various sources of funding for their company, such as investments, loans, or revenue from sales.
3. Crypto Addresses: This field allows users to enter any cryptocurrency addresses associated with their company. This may include addresses for Bitcoin, Ethereum, or other digital currencies.
4. "Bank account" section:
   * Bank's name: This field refers to the name of the bank where the account is held. It represents the financial institution that provides the banking services and holds the funds in the account.
   * Bank's address: This field specifies the physical address of the bank where the account is held. It includes details such as the street address, city, state/province, and postal code. The bank's address is important for identification and communication purposes.
   * &#x20;Is IBAN: This field indicates whether the provided bank account number is in the International Bank Account Number (IBAN) format. IBAN is a standardized format used for identifying bank accounts internationally. If this field is marked as "Yes," it means the provided bank account number is in IBAN format.
   * Account number: This field refers to the unique identification number assigned to a bank account. It is a combination of digits that identifies the specific account held with a financial institution.
   * Account holder: This field represents the name of the individual or entity that owns or holds the bank account. It could be an individual's name or the name of a company or organization.

<figure><img src="../../../.gitbook/assets/BusinessFinancialsNW.png" alt="Business Financials"><figcaption><p>Business Financials</p></figcaption></figure>

#### Crypto currency address verification

In addition to entering crypto addresses on the "Business Financials" screen, users can also verify ownership of crypto currency addresses for NEAR blockchain ([https://near.org](https://near.org)) by connecting wallet and signing a message.

<figure><img src="../../../.gitbook/assets/NEAR_1.png" alt=""><figcaption><p>NEAR - add and check NEAR address</p></figcaption></figure>

For NEAR crypto addresses, before adding a crypto address to the list, we verify if the address exists on the NEAR blockchain. This is important to ensure that the address is valid and can be used for transactions. To perform the verification, we use the NEAR blockchain explorer to check if the address has any associated transactions or balance.

If the address is found on the blockchain, users can proceed to add it to their financial records. If the address is not found, users will receive an error message and will not be able to proceed with adding it. This verification step helps to ensure the accuracy and reliability of the financial records stored on our platform.

Currently, we support the "Meteor" wallet for this process ([https://meteorwallet.app/](https://meteorwallet.app/)). However, we plan to support more wallets as their owners implement the "verifyOwner" method from NEAR (more information on the "verifyOwner" method can be found here: [https://docs.near.org/tools/wallet-selector#verify-owner](https://docs.near.org/tools/wallet-selector#verify-owner)).

<figure><img src="../../../.gitbook/assets/NEAR_2.png" alt=""><figcaption><p>NEAR - choose wallet using Wallet Selector</p></figcaption></figure>

To verify ownership using the "Meteor" wallet, users can follow the instructions provided by the wallet provider.

<img src="../../../.gitbook/assets/NEAR_3.png" alt="Meteor wallet - confirm connecting the wallet to Gatenox Hub" data-size="original">

The process involves connecting their wallet to the NEAR blockchain and signing a message that confirms ownership of the address.

<figure><img src="../../../.gitbook/assets/NEAR_4.png" alt=""><figcaption><p>NEAR - the wallet is connected</p></figcaption></figure>

Then the signed message is verified in Gatenox Hub. By doing so, users can provide proof that they are the rightful owners of the address, which may be useful for various purposes such as investment reporting or auditing.

<img src="../../../.gitbook/assets/NEAR_5.png" alt="Meteor wallet - confirm message signature" data-size="original">

It's important to note that the exact steps for verifying ownership may vary depending on the specific wallet and blockchain being used.

<figure><img src="../../../.gitbook/assets/NEAR_6.png" alt="NEAR - the address is verified"><figcaption><p>NEAR - the address is verified</p></figcaption></figure>



Users should always follow the instructions provided by their wallet and blockchain providers to ensure a secure and accurate verification process.
