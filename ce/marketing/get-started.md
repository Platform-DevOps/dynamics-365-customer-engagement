---
title: "Get started with outbound and real-time marketing (Dynamics 365 Marketing) | Microsoft Docs"
description: "Learn how to get up and running quickly with outbound and real-time marketing features in Dynamics 365 Marketing."
ms.date: 01/19/2022
ms.service: dynamics-365-marketing
ms.custom: 
  - dyn365-marketing
ms.topic: article
author: alfergus
ms.author: alfergus
manager: shellyha
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365Mktg
---

# Get started with outbound and real-time marketing

This article provides checklists to get your Dynamics 365 Marketing implementation up and running quickly. The first checklist offers basic steps and articles to follow during the initial setup process. The second checklist ventures into more advanced tasks, including subscription lists and subscription center setup.

## Dynamics 365 Marketing basic setup

Follow these steps to expedite the Dynamics 365 Marketing setup process.

| Task | Related information |
|---|---|
| Gather and document use cases and marketing requirements | Determine your business requirements for bulk mailings, automation, surveys, event management, etc. |
| Determine licensing requirements | Licensing is done on a tenant level. Learn more: [Dynamics 365 Marketing licensing options](purchase-setup.md#dynamics-365-marketing-licensing-options). |
| Determine company geographical address | Visible on all emails (regulatory requirement). Learn more about entering your organization's postal address: [Use content settings to set up repositories of standard and required values for email messages](dynamic-email-content.md#use-content-settings-to-set-up-repositories-of-standard-and-required-values-for-email-messages). |
| Determine if Power Apps portals are needed | Learn more: [Integrate Marketing with a CMS system, Dynamics 365 Portals, or Power Apps portals](portal-optional.md). |
| Install Dynamics 365 Marketing app on all Dynamics 365 organizations (dev and production) | Update Dynamics 365 tenants first. Learn more: [Purchase and set up Dynamics 365 Marketing](purchase-setup.md). |
| Grant access to superusers for Dynamics 365 Marketing training | Later, give access to all users. Learn more: [Manage user accounts, user licenses, and security roles](admin-users-licenses-roles.md). |
| Customize your Dynamics 365 Sales app if needed (merge new tabs, attributes) | Example: [View and edit which lists each contact subscribes to](set-up-subscription-center.md#view-and-edit-which-lists-each-contact-subscribes-to). |
| Authenticate your company domains on the production environment | Learn more: [Authenticate your domains](mkt-settings-authenticate-domains.md). |
| Configure insights sync settings | Learn more: [Sync entities and track insights using Dataset configuration](mkt-settings-sync.md). |
| Configure content settings. If there are multiple subsidiaries or legal entities with different brands, create multiple settings. | Learn more: [Use content settings to set up repositories of standard and required values for email messages](dynamic-email-content.md#use-content-settings-to-set-up-repositories-of-standard-and-required-values-for-email-messages), [Configure your social media accounts](mkt-settings-social-media.md), [Configure landing pages](mkt-settings-landing-pages.md). |
| Configure default marketing settings. If there are multiple subsidiaries or legal entities with different brands, create multiple settings. | Learn more: [Settings overview](marketing-settings.md), [Set up global double opt-in for new subscriptions and consent changes](double-opt-in.md), [Set up subscription lists and subscription centers](set-up-subscription-center.md). |

## Set up bulk mailings, manage subscriptions and the double opt-in process

Follow these steps to set up subscription lists, configure your subscription center, and create a journey to email marketing mailings to your subscribers.

| Task | Related information |
|---|---|
| Define and create subscription lists | Lists that a client can subscribe to such as a newsletter. Learn more: [Create a subscription list](set-up-subscription-center.md#create-a-subscription-list). |
| Upload your company logo as a digital asset | Resize before uploading to use in emails, forms, etc. Learn more: [Upload and use images and files in online content](upload-images-files.md). |
| Design your subscription form for each subscription list | It is recommended to use a separate form instead of only using the subscription center. Learn more: [Add a subscription list to a subscription form](set-up-subscription-center.md#add-a-subscription-list-to-a-subscription-form). |
| Design your subscription center | Learn more: [Create a subscription center marketing page](set-up-subscription-center.md#create-a-subscription-center-marketing-page), [Create a landing page with a form](create-landing-page.md). |
| Design the main email template for your company | Learn more: [Work with email, page, and form templates](email-templates.md). |
| Design a double opt-in confirmation email and landing page | Learn more: [Create an increase content confirmation request message](double-opt-in.md#create-an-increase-consent-confirmation-request-message), [Create a thank you page for each type of confirmation](double-opt-in.md#create-a-thank-you-page-for-each-type-of-confirmation). |
| Configure double opt-in settings | Learn more: [Set up global double opt-in for new subscriptions and consent changes](double-opt-in.md). |
| Prepare data migration of existing email subscription lists | From Mailchimp, for example. Learn more: [Import and email all contacts from a spreadsheet](email-excel.md), [Create a subscription list](set-up-subscription-center.md#create-a-subscription-list). |
| Embed forms and subscription center into CMS (if Power Apps portals are not used) | Learn more: [Embed forms on external websites](embed-forms.md). |
| Design a customer journey for subscription mailings | This will be a simple two or three step journey (send mail to subscribers). Learn more: [Create a simple customer journey with email messaging](create-simple-customer-journey.md). |
| Test and go live with marketing mailings | Learn more: [Check for errors, go live, and deliver the messages](email-check-golive.md). |