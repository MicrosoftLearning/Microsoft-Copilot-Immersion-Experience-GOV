---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Copilot Immersion Experiences for US Government

## Content Directory

The demos for this course are based on the demos from the accelerator kit <a href="https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG" target="_blank">Demo Guide and Talking Points.docx</a>.

It is important that you familiarize yourself with the demos prior to delivering this training. For several labs, you'll utilize sample documents and pre-created Teams meetings and emails.

<ul>
  <li>Pre-download all sample documents <a href="https://github.com/MicrosoftLearning/Microsoft-Copilot-Immersion-Experience-GOV/tree/master/Resourcefiles" target="_blank">here</a>.</li>
  <li>Setup Teams meetings and email threads by following the instructions <a href="https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG" target="_blank">here</a>.</li>
  <li>Familiarize yourself with the Interactive experience found <a href="https://aka.ms/CopilotWebEE" target="_blank">here</a>.</li>
</ul>

## Immersion Experiences (Customer facing)

### <a href="https://microsoftlearning.github.io/Microsoft-Copilot-Immersion-Experience-GOV/Instructions/Labs/Gov_Licensed/index_1.html" target="_blank">MS-4008: Microsoft 365 Copilot Interactive Experience (US Gov - Licensed):</a>


In this interactive experience, you'll get inspired and use Microsoft 365 Copilot to streamline tasks such as research, drafting documents, drafting emails, and more.

You will perform four tasks:

- Task 1: Streamline Data Analysis & Insights with Microsoft 365 Business Chat
- Task 2: Draft a document using Microsoft 365 Copilot in Word
- Task 3: Gathering Insights and Drafting a Follow-up Email
- Optional Task: Collaborate using Pages


### <a href="https://microsoftlearning.github.io/Microsoft-Copilot-Immersion-Experience-GOV/Instructions/Labs/Gov_Unlicensed/index_1.html" target="_blank">MS-4012: Microsoft Copilot Interactive Experience (US Gov - Unlicensed)</a>


In this interactive module, you'll experience firsthand how Microsoft Copilot can streamline your workflow. Through a series of exercises, you'll learn to use Microsoft Copilot to generate innovative ideas, create compelling branding, and analyze the competitive landscape, all while boosting productivity and strategic insights.

You will perform three tasks:

- Task 1: Brainstorm innovative ideas
- Task 2: Create brand identity and marketing assets
- Task 3: Analyze the competitive landscape

## Demos

Demos are shared between both MS-4008 & MS-4012 courses. 

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}