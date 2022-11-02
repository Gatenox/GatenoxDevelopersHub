Welcome to the Gatenox wiki! You can find here the following documents related to our product:

1. User guide for beta testers: [Beta tester user guide](https://github.com/Gatenox/GatenoxDevelopersHub/wiki/Gatenox-Beta-User-Guide)
2. Quick info - how to start onboarding clients with Gatenox: [Verifier guide to Gatenox services](https://github.com/Gatenox/GatenoxDevelopersHub/wiki/How-to-onboard-your-clients-with-Gatenox%3F)

# Guide to the Gatenox Hub

This document explains the Gatenox Hub interface and possible usage scenarios. 

The application caters to two roles:
* **User** who, while going through the Corporate KYC process, onboards to other companies
* **Verifier** who reviews submitted Corporate KYC applications
As a **Verifier**, you are also a **User**, so you have access both to Verifier and User functionalities. If you'd like to quickly jump into User or Verifier's shoes and see the potential possibilities, check out the [Tutorial Video for both roles](https://beta.gatenox.com/gatenox-beta-video-explainer). 

## Introduction
To save you time and maximize your user experience, we have populated your profile with sample company data. For BETA testing, you don't have to worry about filling in these necessary data. Feel free to edit them if you want to get the experience of filling the data in yourself.
 
The company profile you get out of the box consists of:
* **Company details data** (Jurisdiction, Company Name, Company Registration Number, Date of Incorporation, Company Type, Brand Name, Proof of Incorporation, Registered Address, Office Address, Proof of Office Address, Industry)
* **One Company Director** (and UBO) with KYC data
* **One Individual Shareholder** (the same person as the Director)
* **One Corporate Shareholder**

## Interface overview

1. Log in to the application using the login information you received in the email.

2. After logging in, you will hit your company profile screen. We have prepared a profile of the company named **Verifier LTD** for you. As you can see in the following screenshot, the profile contains several sections related to Verifier LTD company details (_Company Details, Directors, Documents, UBOs, Company Structure_) and _Message Panel_, and _Other Gatenox Partners_.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/profile.png"></img>

3. Click _Edit_ to modify your Company Details. You may notice that optional data is missing. Editing and data entry are done through an intuitive and simple wizard. More detailed instructions are provided in the latter sections of this guide.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/company_detials.png"></img>

4. Click _Edit_ to modify your Company Directors.  For now, you have only one Director (Joe Allen), but you can add as many directors as you need. For each of them, you can provide all required data, in particular, KYC data. 

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/directors.png"></img>

5. In the section below, you can view all of your Company's Documents that you have previously added.

<img src="./Images/documents.png"></img>

6. Click _Edit_ to modify your Company UBOs.  For now, you have only one UBO (Joe Allen). For each of your UBOs, you can provide all required data, in particular, KYC data. Adding UBOs is done in the Company Structure section, but here (by clicking Edit) you can go straight to the appropriate place in the form.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/UBOs.png"></img>

7. Click _Edit_ to modify your Company Structure. The company's structure includes the mentioned UBOs as well as Individual and Corporate Shareholders.

By adding individual entities to the structure, a graph is dynamically generated to illustrate the connections between the various entities. Below you can see a simple structure consisting of only two shareholders.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/company_structure.png"></img>

8. On the right, you can see two panels. _Message Panel_ is where messages from the Compliance Officer who is reviewing your application will appear.

_Other Gatenox Partners_ is the section with a list of other Gatenox Partners who offer one-click onboarding.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/meet_our_partners.png"></img>

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/message_panel.png"></img>

9. In the left sidebar, you can switch between your _Company Profile_ and _Verifications_. Verifications contain all Corporate KYC applications available for review (from potential clients who want to onboard to your company).

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/menu.png"></img>

10. After clicking _Verifications_ you will be taken to the list of applications that are ready to review.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/verifications.png"></img>

# Onboarding Process (User Journey)
A significant part of the onboarding process is filling in all your company data required by the company you want to onboard to.

In the Gatenox Hub, the data collection process has been divided into 3 main parts, ie Company Details, Directors, and Company Structure (including UBOs).

Each part has an easy-to-use wizard that guides you throughout the process.

## Creating new company

To create a new company profile you need to open the context menu in the upper right corner and click on the “Add company” link.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/settings_manage.png"></img>

You will see an “Add new company” screen. In order to facilitate the process of creating a new company profile (entering selected data for you), you must specify exactly what company you mean by entering the jurisdiction and number.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/company_add.png"></img>

Now you can use the “Find your company” button to search for the name of your company. The result will be displayed in the “Company name” field. In case your company will not be found, you can enter “Company name” manually and press the “Continue” button. If the company was not found, then we will not be able to facilitate the process for you.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/company_add2.png"></img>

Now you can press the “Continue” button to go through the company setup wizard. The “Company details” preparation screen will be displayed.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/company_add4.png"></img>


## Company Details
This part is divided into 5 main steps (some steps contain more than one screen):
* **Preparation** - displays information about the data and documents that are required,
* **Basic Data** - asks data related to incorporation,
* **Addresses** - asks data related to Registered Address and Office Address,
* **Business Activity** - asks data about the nature of your business,
* **Additional Data** - asks about any additional information that may be required.

**Preparation**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/preparation.png"></img>

**Basic Data > Incorporation Details**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/basic_data.png"></img>

**Basic Data > Proof of Incorporation Details** (upload each document with one click)

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/proof_of_incorp.png"></img>

**Addresses > Registered Address**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/reg_address.png"></img>

**Addresses > Office Address**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/office_addr.png"></img>

**Basic Data > Proof of Office Address** (upload each document with one click)

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/proof_of_office_addr.png"></img>

Business Activity > Description

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/business_act.png"></img>

Business Activity > Financials

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/finanscials.png"></img>

Additional Information

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/add_info.png"></img>

## Directors
This part is divided into 4 main steps:
1. **Preparation** - displays information about the data and documents that are required
2. **List of Directors** - asks data regarding directors’ basic personal information such as date of birth
3. **Verify your list of directors** - provide a document proofing previously entered list of directors
4. **Verification** - asks Know Your Customer (KYC) data for each director

**Preparation**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_prep.png"></img>

**List of Directors > Add Directors**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_add.png"></img>

**List of Directors > Personal Data**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_personal.png"></img>

**List of Directors > Verify your list of directors**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_proof_list.png"></img>

**Verification > Personal Data**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_personal2.png"></img>

**Verification > Address**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_address.png"></img>

**Verification > Identity Verification**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_verif.png"></img>

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/dir_verif2.png"></img>

## Company Structure
This part is divided into 4 main steps:
1. **Preparation** - displays information about the data and documents that are required
2. **Shareholders** - asks data regarding the structure of your company (you can build any structure by adding Individual and Corporate shareholders)
3. **UBOs** - displays information regarding UBOs (taken from the company structure)
4. **Verification** - asks data regarding Individual and Corporate shareholders

**Preparation**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/cs_prep.png"></img>

**Shareholders**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/cs_shareholders.png"></img>

**UBOs - list**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/cs_UBO.png"></img>

**UBOs - justification**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/cs_UBO2.png"></img>

**Verification** (add detailed data regarding Individual and Corporate shareholders)

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/cs_verif.png"></img>

Once the required company data is completed, you will be able to send it to the Gatenox Partner by clicking on the _Send for Review_ button.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/send_review.png"></img>

When your data has been sent, your application will appear in the _Your Applications_ panel on the Company profile screen. 

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/send_review2.png"></img>

# Verification Process (Verifier Journey)

To review applications, click on the Verifications tab and select one of the applications in the list.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/applic.png"></img>

From this screen, you can also send a verification invitation to another company. As soon as the other party accepts your invitation to the Corporate KYC process, the application will appear in the mentioned list.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/appli_invitation.png"></img>

## Review Process
Each application is divided into 6 main parts:
* **Company Details** - displays all details related to company incorporation data, addresses, etc.
* **Directors** - displays all details related to company directors (including required KYC information)
* **UBOs** - displays all details related to company UBOs (including required KYC information)
* **Company Structure** - displays all shareholders (this part is connected with the company structure graph that you can see at the top of the review page)
* **Identified Issues** - displays all identified potential issues, e.g. presence of company entities or individuals on sanction, PEP or criminal lists
* **Assessment** - section where you can accept or reject the application and include summary notes

Before the mentioned sections are displayed, a summary of any identified potential issues will appear at the top of the page e.g. presence of company entities or individuals on sanction, PEP or criminal lists in **a red section**. 

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_issues.png"></img>

If no potential issues are found, a green section will be displayed at the top of the page. 

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_issues2.png"></img>

In addition, you can view the whole structure of the company in the form of a **fully interactive graph** (it is possible to open the graph in a new browser tab).

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_graph.png"></img>

After having an overview of the company's structure, you can proceed to the process of viewing the data.

**Company Details**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_comp_detials.png"></img>

**Directors**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_dir.png"></img>

**UBOs**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_UBO.png"></img>

**Company Structure - tree view** (you can view the entire structure by expanding the selection - in this case, clicking the down arrow next to PETROPARS UK LIMITED)

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_cs.png"></img>

**Identified issues**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_ubo2.png"></img>

**Assessment**

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/review_assesment.png"></img>

## Extended verification

The basic sanctions check in Gatenox involves verification of individuals and companies on the internal sanctions list, which currently includes the OFAC database.

If you require to verify individuals and companies within a myriad of sanction lists, PEP, and criminal watchlists you can buy additional search by selecting an entity on directors, UBOS and company structure tabs. They will be added to the entity's verification basket on the right side of the webpage. 

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/entities_verification.png"></img>

Now you can press the “Verify” button and additional verification will be performed. The results will be presented in the same way as internal checks.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/entities_verification_result.png"></img>

# Settings

The settings menu can be access using "Settings" tab on menu placed on left side of the portal or by clicking on "Manage your account" button in context menu in the upper right corner.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/settings_manage.png"></img>

The settings tab consist of 2 tabs:
1. **Account information** - where user can review and (in the future) update personal data
2. **Company information** - where user can update company profile settings like: update company logo, add services description or change referral code 

**Account information**
Here you can currently see your individual account details. In the nearby future we are planning to add more features in the section.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/settings_personal.png"></img>

**Company information**
The tab is split into 2 sections:
1. Basic settings:
   * you can upload your company logo, to present it on portal
   * about company - a brief description about your company and its services. It is used on welcome screen, when you invite users using your referral code
   * check available amount of credits - credits are used in Gatenox to buy additional services, such as extend verification on sanctions and PEP lists or to ask users to provide an external KYC verification. To add more credits please contact our sales department at sales@gatenox.com.

2. Verification settings:
   * Verification link - consist of a link + your company referral code. The code can be modified to fit your company name or other requirements,
   * Required fields - a complete set of required data + documents, that need to be provided by other companies during the verification process. This data can be configured in the setup phase, when you will be using Gatenox as a corporate KYC verification tool.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/settings_company.png"></img>

# Feedback

We encourage you to take the opportunity to leave feedback. Click on the blue GIVE US FEEDBACK button pinned to the bottom of the page and leave your opinion.

<img src="https://github.com/Gatenox/GatenoxDevelopersHub/blob/main/Images/feedback.png"></img>
