Welcome to the Gatenox wiki!

Table of contents<br>
[Guide](https://github.com/Gatenox/GatenoxHub#guide-to-the-gatenox-hub)<br>
   [Introduction](https://github.com/Gatenox/GatenoxHub#introduction)

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

<img src="./Images/profile.png">

3. Click _Edit_ to modify your Company Details. You may notice that optional data is missing. Editing and data entry are done through an intuitive and simple wizard. More detailed instructions are provided in the latter sections of this guide.

<img src="./Images/company_detials.png">

4. Click _Edit_ to modify your Company Directors.  For now, you have only one Director (Joe Allen), but you can add as many directors as you need. For each of them, you can provide all required data, in particular, KYC data. 

<img src="./Images/directors.png">

5. In the section below, you can view all of your Company's Documents that you have previously added.

<img src="./Images/documents.png">

6. Click _Edit_ to modify your Company UBOs.  For now, you have only one UBO (Joe Allen). For each of your UBOs, you can provide all required data, in particular, KYC data. Adding UBOs is done in the Company Structure section, but here (by clicking Edit) you can go straight to the appropriate place in the form.

<img src="./Images/UBOs.png">

7. Click _Edit_ to modify your Company Structure. The company's structure includes the mentioned UBOs as well as Individual and Corporate Shareholders.

By adding individual entities to the structure, a graph is dynamically generated to illustrate the connections between the various entities. Below you can see a simple structure consisting of only two shareholders.

<img src="./Images/company_structure.png">

8. On the right, you can see two panels. _Message Panel_ is where messages from the Compliance Officer who is reviewing your application will appear.

_Other Gatenox Partners_ is the section with a list of other Gatenox Partners who offer one-click onboarding.

<img src="./Images/meet_our_partners.png">

<img src="./Images/message_panel.png">

9. In the left sidebar, you can switch between your _Company Profile_ and _Verifications_. Verifications contain all Corporate KYC applications available for review (from potential clients who want to onboard to your company).

<img src="./Images/menu.png">

10. After clicking _Verifications_ you will be taken to the list of applications that are ready to review.

<img src="./Images/verifications.png">

# Onboarding Process (User Journey)
A significant part of the onboarding process is filling in all your company data required by the company you want to onboard to.

In the Gatenox Hub, the data collection process has been divided into 3 main parts, ie Company Details, Directors, and Company Structure (including UBOs).

Each part has an easy-to-use wizard that guides you throughout the process.

## Creating new company

To create a new company profile you need to open the context menu in the upper right corner and click on the “Add company” link.

<img src="./Images/settings_manage.png">

You will see an “Add new company” screen. In order to facilitate the process of creating a new company profile (entering selected data for you), you must specify exactly what company you mean by entering the jurisdiction and number.

<img src="./Images/company_add.png">

Now you can use the “Find your company” button to search for the name of your company. The result will be displayed in the “Company name” field. In case your company will not be found, you can enter “Company name” manually and press the “Continue” button. If the company was not found, then we will not be able to facilitate the process for you.

<img src="./Images/company_add2.png">

Now you can press the “Continue” button to go through the company setup wizard. The “Company details” preparation screen will be displayed.

<img src="./Images/company_add4.png">


## Company Details
This part is divided into 5 main steps (some steps contain more than one screen):
* **Preparation** - displays information about the data and documents that are required,
* **Basic Data** - asks data related to incorporation,
* **Addresses** - asks data related to Registered Address and Office Address,
* **Business Activity** - asks data about the nature of your business,
* **Additional Data** - asks about any additional information that may be required.

**Preparation**

<img src="./Images/preparation.png">

**Basic Data > Incorporation Details**

<img src="./Images/basic_data.png">

**Basic Data > Proof of Incorporation Details** (upload each document with one click)

<img src="./Images/proof_of_incorp.png">

**Addresses > Registered Address**

<img src="./Images/reg_address.png">

**Addresses > Office Address**

<img src="./Images/office_addr.png">

**Basic Data > Proof of Office Address** (upload each document with one click)

<img src="./Images/proof_of_office_addr.png">

Business Activity > Description

<img src="./Images/business_act.png">

Business Activity > Financials

<img src="./Images/finanscials.png">

Additional Information

<img src="./Images/add_info.png">

## Directors
This part is divided into 4 main steps:
1. **Preparation** - displays information about the data and documents that are required
2. **List of Directors** - asks data regarding directors’ basic personal information such as date of birth
3. **Verify your list of directors** - provide a document proofing previously entered list of directors
4. **Verification** - asks Know Your Customer (KYC) data for each director

**Preparation**

<img src="./Images/dir_prep.png">

**List of Directors > Add Directors**

<img src="./Images/dir_add.png">

**List of Directors > Personal Data**

<img src="./Images/dir_personal.png">

**List of Directors > Verify your list of directors**

<img src="./Images/dir_proof_list.png">

**Verification > Personal Data**

<img src="./Images/dir_personal2.png">

**Verification > Address**

<img src="./Images/dir_address.png">

**Verification > Identity Verification**

<img src="./Images/dir_verif.png">

<img src="./Images/dir_verif2.png">

## Company Structure
This part is divided into 4 main steps:
1. **Preparation** - displays information about the data and documents that are required
2. **Shareholders** - asks data regarding the structure of your company (you can build any structure by adding Individual and Corporate shareholders)
3. **UBOs** - displays information regarding UBOs (taken from the company structure)
4. **Verification** - asks data regarding Individual and Corporate shareholders

**Preparation**

<img src="./Images/cs_prep.png">

**Shareholders**

<img src="./Images/cs_shareholders.png">

**UBOs - list**

<img src="./Images/cs_UBO.png">

**UBOs - justification**

<img src="./Images/cs_UBO2.png">

**Verification** (add detailed data regarding Individual and Corporate shareholders)

<img src="./Images/cs_verif.png">

Once the required company data is completed, you will be able to send it to the Gatenox Partner by clicking on the _Send for Review_ button.

<img src="./Images/send_review.png">

When your data has been sent, your application will appear in the _Your Applications_ panel on the Company profile screen. 

<img src="./Images/send_review2.png">

# Verification Process (Verifier Journey)

To review applications, click on the Verifications tab and select one of the applications in the list.

<img src="./Images/applic.png">

From this screen, you can also send a verification invitation to another company. As soon as the other party accepts your invitation to the Corporate KYC process, the application will appear in the mentioned list.

<img src="./Images/appli_invitation.png">

## Review Process
Each application is divided into 6 main parts:
* **Company Details** - displays all details related to company incorporation data, addresses, etc.
* **Directors** - displays all details related to company directors (including required KYC information)
* **UBOs** - displays all details related to company UBOs (including required KYC information)
* **Company Structure** - displays all shareholders (this part is connected with the company structure graph that you can see at the top of the review page)
* **Identified Issues** - displays all identified potential issues, e.g. presence of company entities or individuals on sanction, PEP or criminal lists
* **Assessment** - section where you can accept or reject the application and include summary notes

Before the mentioned sections are displayed, a summary of any identified potential issues will appear at the top of the page e.g. presence of company entities or individuals on sanction, PEP or criminal lists in **a red section**. 

<img src="./Images/review_issues.png">

If no potential issues are found, a green section will be displayed at the top of the page. 

<img src="./Images/review_issues2.png">

In addition, you can view the whole structure of the company in the form of a **fully interactive graph** (it is possible to open the graph in a new browser tab).

<img src="./Images/review_graph.png">

After having an overview of the company's structure, you can proceed to the process of viewing the data.

**Company Details**

<img src="./Images/review_comp_detials.png">

**Directors**

<img src="./Images/review_dir.png">

**UBOs**

<img src="./Images/review_UBO.png">

**Company Structure - tree view** (you can view the entire structure by expanding the selection - in this case, clicking the down arrow next to PETROPARS UK LIMITED)

<img src="./Images/review_cs.png">

**Identified issues**

<img src="./Images/review_ubo2.png">

**Assessment**

<img src="./Images/review_assesment.png">

## Extended verification

The basic sanctions check in Gatenox involves verification of individuals and companies on the internal sanctions list, which currently includes the OFAC database.

If you require to verify individuals and companies within a myriad of sanction lists, PEP, and criminal watchlists you can buy additional search by selecting an entity on directors, UBOS and company structure tabs. They will be added to the entity's verification basket on the right side of the webpage. 

<img src="./Images/entities_verification.png">

Now you can press the “Verify” button and additional verification will be performed. The results will be presented in the same way as internal checks.

<img src="./Images/entities_verification_result.png">

# Settings

The settings menu can be access using "Settings" tab on menu placed on left side of the portal or by clicking on "Manage your account" button in context menu in the upper right corner.

<img src="./Images/settings_manage.png">

The settings tab consist of 2 tabs:
1. **Account information** - where user can review and (in the future) update personal data
2. **Company information** - where user can update company profile settings like: update company logo, add services description or change referral code 

**Account information**
Here you can currently see your individual account details. In the nearby future we are planning to add more features in the section.

<img src="./Images/settings_personal.png">

**Company information**
The tab is split into 2 sections:
1. Basic settings:
   * you can upload your company logo, to present it on portal
   * about company - a brief description about your company and its services. It is used on welcome screen, when you invite users using your referral code
   * check available amount of credits - credits are used in Gatenox to buy additional services, such as extend verification on sanctions and PEP lists or to ask users to provide an external KYC verification. To add more credits please contact our sales department at sales@gatenox.com.

2. Verification settings:
   * Verification link - consist of a link + your company referral code. The code can be modified to fit your company name or other requirements,
   * Required fields - a complete set of required data + documents, that need to be provided by other companies during the verification process. This data can be configured in the setup phase, when you will be using Gatenox as a corporate KYC verification tool.

<img src="./Images/settings_company.png">

# Feedback

We encourage you to take the opportunity to leave feedback. Click on the blue GIVE US FEEDBACK button pinned to the bottom of the page and leave your opinion.

<img src="./Images/feedback.png">
