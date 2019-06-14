---
layout: default
nav_order: 2
parent: Integrations
has_children: false
title: Autocomplete items through Github
description: Autocomplete items in Zepel when you merge pull requests in Github.
permalink: guide/integrations/complete-items-with-github/
---
# Complete items in Zepel with Github integration

{: .no_toc }

Every time you close a pull request in Github, Zepel can automatically complete its respective task on Zepel so you don't have to switch back and forth. 

* Once you've connected your Zepel account with your Github repository, head over to the task in your Zepel project.
* Click on the task's "Edit details" icon.

[IMG]

* On the top-right corner of the task's details page, click on the "Copy item link".

[IMG]

* Head over to your Github repository and create a new pull request.
* In the pull request's description, paste the item's link.

[IMG]

* Click "Create pull request"

When you close this pull request, its respective task in Zepel will automatically get completed. And if your team has Slack integration enabled, they'll automatically be notified too.
