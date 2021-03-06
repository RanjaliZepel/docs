---
layout: default
nav_order: 2
has_children: false
grand_parent: Streams
parent: Sources Catalog
title: Connect Intercom with Zepel
page_title: Intercom
description: How to send customer requests from Intercom to Streams in Zepel
permalink: streams/sources-catalog/intercom/
---

# How to Connect Intercom With Zepel
{: .no_toc }

There's a ton of product feedback your customer shares with you when they're chatting with your support team.

Wouldn’t it be ideal to bring it all in one place? 

By integrating Intercom with Zepel, customer feedback & their requests will not only be brought into Zepel, but you'll also be able to consolidate and prioritize them. 

---

**Before you begin:** Make sure you’re logged in to your Intercom account and have Streams subscription enabled in your Zepel account.

## IN THIS PAGE
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Connecting Intercom with Zepel

- Head over to Intercom's `Settings`.  

- Under the `Developers` section, click on `Developer Hub`.

- Click `New App` and give it a name. We recommend naming it as `Zepel Streams` so you can recognize it if you ever have to re-visit it.

- Select your workspace and click the `Internal integration` radio button.

- Click `Create App`.

![Create App button in Intercom](/guide/assets/uploads/intercom-create-app-streams.png)   

- Now, on the left side bar under `Configure` section, navigate to `Authentication`. 

- Copy the `Access Token` generated by Intercom. 

![Access Token in Intercom highlighted](/guide/assets/uploads/intercom-access-token.png)

- In Zepel, navigate to the `Streams` tab. 

- Click on the `Add Source` button. 

![Streams Add Source Button](/guide/assets/uploads/streams-add-source-button.png)

- A pop-up will appear with a list of sources available. 

![Streams Sources Catalog](/guide/assets/uploads/streams-sources-catalog.png)

- Click on `Intercom` to connect it with Zepel.

- Paste the token you copied in Intercom settings under `API Access Token`. 

![Streams Intercome API Token](/guide/assets/uploads/streams-intercom-api-token.png)

- Click `Enable`.

- Copy the secret Webhook URL that is generated for your account. 

![Streams Intercome Webhook URL](/guide/assets/uploads/streams-intercom-webhook-url.png)

- Head back to Intercom settings.

- On the left sidebar under `Configure` section, navigate to `Webhooks`.

- Paste the `Webhook URL` you copied from your Zepel account under `Your request endpoint URL`.

![Webhooks in Intercom with Webhook URL box highlighted](/guide/assets/uploads/intercom-webhooks-url.png)

- Under the `Webhook Topics` section on the same page, make sure the below topics are selected:

1. `conversation.user.created`
2. `conversation_part.tag.created`
3. `user.email.updated`
4. `conversation_part.redacted`

![Webhook Topics dropdown highlighted](/guide/assets/uploads/intercom-webhook-topics.png)

- Click `Save` on the top-right corner. 

That's it! You can now send product feedback and requests from customers on Intercom to Streams in Zepel for effortless prioritization.

---

## Send a specific Intercom conversation to Zepel

You can add any conversation on Intercom as a `Request` in Zepel by adding this simple tag `zepel` to any particular conversation.

To tag a conversation: 

- Hover your mouse on a conversation in Intercom. 

- To the right of the conversation, click on the `Tag` icon.

![Tag Conversation in Intercom](/guide/assets/uploads/tag-conversation-in-intercom.png)

- In the tags pop-up, type `zepel` to search for the tag. If you haven't already created the tag, Intercom will prompt you to create it.

- Click on the tag to tag the conversation.

Once the conversation is tagged, it'll automatically be added to Streams.

---

*Tip: Use the available filters and sort options to view specific requests based on their source and status.*
