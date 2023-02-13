---
description: >-
  The aim is to ensure we tell the world who we are and what we do, ensure 24/7
  access and presence, build credibility, keep customers informed, generate
  business, target a wider audience, & marketing.
cover: .gitbook/assets/psg-financial-services.png
coverY: 0
---

# 👋 Introduction!

{% hint style="info" %}
**Purpose:** The purpose of the documentation is my full understanding of the code and layout of the PFW (Front End, Content API, Back End Umbraco Service, DB etc.)
{% endhint %}

For **team members**, this space will be helpful during first days of the current performance testing, technical review and functionality review, to better learn about the current website and how it works.

For **long-term**, this space will be used to note all the suggestions for improvements to make the website more interactive and dynamic than only being a static site that only provides information. Clients must be able to perform tasks they can perform via the **Mobile App** even on the Website and the development teams must collaborate to ensure consumption of the same webservices to render services.

<details>

<summary>Current Web Pages Structure (Public Facing/Front-End)</summary>

### Menu/Navigation Bar

The website contains a navigation menu that has all offerings (Advice, Invest, Insure), About, News & Publications, Careers, Contacts, Privacy, forms and fact sheets, find advisors, login and office locations (Southern Africa and Global).

### Content

The body contains a slider and content that is captured with a CMS (Umbraco), a messaging tool and latest news

### Footer

Office Contacts, location and links to major portfolios, support, FAQs, legal and enabling customers to subscribe to newsletters

### Login for External/Internal Systems

Redirect Login to myPSG, Wealth Funds, PSG Online and All platform access

</details>

<details>

<summary>Current Functionality</summary>

The current website has the below functionality from the user perspective (Front-End).&#x20;

### Financial Advice

Visitors are able to find an advisor for self or business by either a search by _**product, an advisor name or location**._ For location, my thinking is I enter my location, which is not the case but rather the office location, would be ideal to re-label it to Office Location or allow a user to enter their location then suggest nearly offices.

### Save, Invest and Insurance

This menu item lists all investment products from Savings, local and global funds, retirement, stockbroking and different calculators.

As a user when I want to either start my investment journey as a new user or an existing PSG Customer, I have to fill the same Google Form for callback. The form asks from Name and Surname, contact number and Email (One Input Box), whether new/existing, and choice of a specific product(s) and any comments.

_**As a business how do we get insight/visibility of this data saved through Google form?**_ It is possible to build this form to partially/fully save this user data in a system that will at the end of the day have an admin dashboard available to both advisors and any other users just like they do in the current spreadsheet that stores this information and automatically report from it.

If users abandons the application process having already entered their email/phone number, regularly remind them to complete the application (using predefined email templates) or call/SMS them to confirm if they still need to proceed or automatically remove incomplete applications after a set auto-delete threshold. This applies across all products/services that can be bought/requested by PSG Mobile App/Web.

The image below illustrates what appears when I click a retirement options, the **How do I Invest button takes a user to talk to an adviser which in return shows Find an adviser/Call me back which both their functionality needs to be redesigned by having a product catalog that can enable users to straight away start application process if they want to or talk to an adviser.**

![](<.gitbook/assets/image (2).png>)

It would be so to have a button that says **Invest Now,** then start **An Onboarding Process.**

### Careers

Careers redirect to [myFocus](https://myfocus.psg.co.za/CareerFocus/Vacancy/HRF\_VACANCY\_SEARCH\_CAREERS\_BLOCK.aspx) which in return only needs to show only Active Vacancies for users to browse. If a user have applied through the portal, _is there a visibility of the application status, (**Not yet reviewed, Under Consideration, Interviewing, Failed technical assessment, etc.**) and notify users on stage/status change until the applications goes into achieves for the user._



</details>
