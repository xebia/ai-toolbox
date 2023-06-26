---
title: Creating Presentations from scratch
weight: 4
categories: [Presentation]
tags: [PowerPoint, SlackGPT]
description: >
  How can SlackGPT help you with creating your presentations?
---

|Responsible AI Checklist|
|---|---|
|Can be used with customer data input| ❌ No this tool is not safe to use|
|Can output be used at customer | ❓ TODO check this|
|Can be used with Xebia Internal secret data| ✅ yes|
|Can output be used commercially by Xebia | ✅ yes |
|Is data being stored in the region you use it | ❌ No, no policy on this|
|Do we have a Xebia license / managed solution for this tool | ✅ [SlackGPT](/docs/ai-tools/slackgpt)|
|Tools used in workflow | [SlackGPT](/docs/ai-tools/slackgpt) |

## Introduction
Creating a presentation can be hard. Especially the initial part. This workflow gets you going from nothing to a full presentation in powerpoint in a couple of minutes from which you can start adding styles and extra content.

## Step 1: Open the Visual Basic Editor

Windows:

Go to Developer[^enable-developer] > Visual Basic

Mac:

Go to Tools > Macro > Visual Basic Editor

Next insert a Module: Insert > Module

## Step 2: Ask SlackGPT to do your homework

Next up we are going to ask SlackGPT to generate a Visual Basic script that will generate a presentation for us. This is mostly Prompt engineering.

Wether you know or you don't know your presentation out-line your prompt should probably start with something like this:
```
    Generate VBA script in PowerPoint that on execution generates slides.
    The Topic of the slide deck is: [The benefits of having ChatGPT do you work]
    The length of the slide deck is: [Minimum of 10 slides]
    
    Think like a C# developer that is trying to save his job by giving this presentation
    make sure to generate sub points on all the slides
```

Run the script.

## Step 3: Style it

All that is left is to style your slides, if you don't have a house-style design you can use the Integrated feature of PowerPoint "Designer" that should be located on the Home Ribbon.

[^enable-developer]: If you don't see the Developer "Ribbon" follow these steps:

    - Go to File > Options
    - Customize Ribbon
    - Main Tabs > Developer
    - Ok
