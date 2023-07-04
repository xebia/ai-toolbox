---
title: SlackGPT
weight: 4
categories: [Tools]
tags: [SlackGPT, ChatGPT]
description: >
  ChatGPT alternative with responsible use of data in Xebia Slack
---

|Responsible AI Checklist|
|---|---|
|Can be used with customer data| ℹ️ Ask Consent|
|Can the output be used at customer| ✅ Yes|
|Can be used with Xebia Internal secret data| ✅ Yes this tool is safe to use|
|Can the output be used commercially by Xebia| ❓TODO VERIFY PROOF |
|Is data being stored in the region you use it | Currently in Azure West Europe (Netherlands)|
|Do we have a Xebia license / managed solution for this tool | ✅ Yes|

## What is SlackGPT
SlackGPT was created at Xebia to offer an observable alternative to ChatGPT. The data that you send to SlackGPT is not stored anywhere, but does use the OpenAI GPT models. You can read more about the software [here][1].

Because it uses a paid endpoint, our data will not be used to train ChatGPT or the GPT models.

## How to use SlackGPT
SlackGPT is an app on the Xebia slack. You can chat with it directly. Every message will start a thread, which is the equivalent of ChatGPT's 'chat'.

## License / Costs
The costs are covered by Xebia. Please use SlackGPT to your heart's content!

## Suitable to use with clients?
It depends, if your client consents to their data being sent to the OpenAI endpoints, this is allowed. If you trigger the Microsoft content filters, the data might be viewed by humans at Microsoft.

The guidance that SlackGPT will give you when starting a new thread:

- The messages you send to SlackGPT are not stored or read by anyone within Xebia
- We log usage metrics to track cost and get insights of how many people are using SlackGPT
- Microsoft might review the messages if they suspect abuse of their API

As a rule of thumb: don't put anything in here that you wouldn't put in Google Translate.

[1]: https://xebia.com/blog/how-we-integrated-chatgpt-into-our-slack-enhancing-privacy-flexibility-and-collaboration/
