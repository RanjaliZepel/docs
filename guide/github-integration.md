---
layout: default
nav_order: 1
parent: Integrations
has_children: false
title: Integrating Github with Zepel
description: Integrate your Zepel account with Github to link items to pull requests.
permalink: guide/integrations/github/
---
# How to integrate Github with Zepel?

{: .no_toc }

Sometimes your dev team can merge and close a pull request, but forget to complete the task. That can leave you with outdated information. With Zepel's Github integration, your developers can now simply close a pull request and Zepel will complete the task for them.

In this article, we'll see how you can set up your Zepel account to integrate with your Github repository.

## Integrate Zepel with Github

* Once you're in your Zepel account, on the top left corner, click on your Account's name.
* From the dropdown, click on "**Account Settings**".

![Click on Settings & Members from Accounts dropdown](/assets/uploads/account-settings.png "Account Settings")

* In the "**Account Settings**" popup, head over to the "**Integrations**" tab. You'll find a list of all Integrations available in Zepel in this tab.

![Head over to Integrations tab in Account Settings](/assets/uploads/integrations-tab.png "Integrations tab in Account Settings")

* Click on the "**Enable**" button next to Github.

[IMG]

* Now, login to your Github account and visit the repository you want to connect with your Zepel account.
* From your repository's settings, visit Webhooks tab.
* Click on "**Add webhook**" button.

[IMG]

* Copy the "**Webhook URL**" that is generated in your Zepel account and paste it in the "**Payload URL**" field in Github.
* Copy the "**Webhook Secret**" that is generated in your Zepel account and paste it in the Secret field in Github.

[IMG]

* Since Zepel integrates only with pull request closed event, under "**Which events would you like to trigger this webhook?**", select "**Let me select individual events**".
* Now, uncheck "**Pushes**" and select "**Pull requests**".

[IMG]

* Click on "**Add Webhook**".

Your Zepel account is now integrated with your Github repository. Read how you can complete tasks every time you close a pull request.