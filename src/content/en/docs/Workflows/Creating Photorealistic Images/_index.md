---
title: Creating Photorealistic Images
weight: 4
categories: [Images, Presentation]
tags: [ChatGPT, SlackGPT, Midjourney]
description: >
  How can you combine ChatGPT and Midjourney to create photorealistic images?
---

|Responsible AI Checklist|
|---|---|
|Can be used with customer data input| ❌ No this tool is not safe to use|
|Can output be used at customer | ❓ TODO check this|
|Can be used with Xebia Internal secret data| ❌ No this tool is not safe to use|
|Can output be used commercially by Xebia | ❓ TODO check this|
|Is data being stored in the region you use it | ❌ No, no policy on this|
|Do we have a Xebia license / managed solution for this tool | ❌ No|
|Tools used in workflow | [Midjourney](/docs/ai-tools/midjourney), [ChatGPT](/docs/ai-tools/chatgpt) / [SlackGPT](/docs/ai-tools/slackgpt) |

## Introduction

Do you want to create photorealistic images with Midjourney, but get stuck when you need to specify your prompt? You can teach ChatGPT/SlackGPT to generate prompts for you. The generated prompt include style, camera type and even camera settings. This document describes the process, but the initial script can be changed to create other styles of images.

## Important: Credit

The steps described on this page were designed by the YouTube channel [AI Foundations][1]. The author created a [video][2] on this subject that improves the Midjourney experience quite a bit.

## Steps

### Step 1: Add the introduction script to ChatGPT

Download [the script][3] on the original author's website. You can paste this script into ChatGPT, or even SlackGPT. After you've sent the script, the AI assistant will respond with a resounding "YES".

### Step 2: Tell the assistant about your subject

What kind of picture do you need? I wanted to generate a 'A photo of a rubber duck sitting on a monitor'. SlackGPT responded with:
> Realistic photograph of a cheerful yellow rubber duck, playfully perched on top of a computer monitor in a cozy office setting, soft ambient lighting, blurred background showcasing office desk and accessories, Nikon D850, 50mm lens, f/1.8, natural light --ar 3:2 --v 5 --q 1

### Step 3: Give the prompt to Midjourney

To get started with Midjourney, [start here][5]. Currently, Midjourney is only accessible through Discord.
Copy the prompt, and prefix it with `/imagine`. Paste this into Midjourney on Discord and it will generate options for you. Here's the result:
![duckies][4]

Note: All Midjourney prompts and results are publicly visible, unless you have a premium subscription with Stealth Mode enabled.

## Licenses needed

### SlackGPT
You can use this on the Xebia Slack. It's a a great alternative for ChatGPT.

### Midjourney
You need a personal license.


[1]: https://www.youtube.com/@ai-foundations
[2]: https://www.youtube.com/watch?v=EJez32MtfWU
[3]: https://aiwealth.vip/midjourney-training-sheet/
[4]: ./duckies.png
[5]: https://docs.midjourney.com/docs/quick-start