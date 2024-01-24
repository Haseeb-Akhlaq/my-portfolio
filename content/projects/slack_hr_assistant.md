---
title: "HR Assistant Slackbot with OpenAI Assistant API"
description: "A revolutionary AI Chatbot for Slack, designed to enhance HR ticketing systems using the OpenAI Assistant API."
dateString: Jan 2024
draft: false
tags: ["Slack", "OpenAI", "Chatbot", "AI", "HR"]
showToc: false
weight: 99
cover:
    image: "projects/slack_hr_assistant/cover.png"
---

## Project Overview

I have developed an AI-powered chatbot for Slack, utilizing the OpenAI Assistant API, meticulously designed to transform HR ticketing systems. This chatbot integrates flawlessly with Slack, enabling HR teams to handle employee issues with greater efficiency and interactive capability.

## Working of Project

A Slack app has been developed and integrated into the Slack channel. This SlackApp is powered by a Flask application, which I have written in Python and deployed on Digital Ocean. For the language processing, I am utilizing GPT-4-turbo through the OpenAI Assistant API. The storage of newly generated tickets is handled by Airtable. The Assistant API leverages OpenAI's capabilities to interpret user intent, gather necessary information using function calling, and transmit it through API calls, ensuring that all data is efficiently stored in Airtable.

### Key Features of the Slackbot: 🤖

1. **Interactive Ticket Generation**: Employees can create tickets through user-chatbot conversations.
2. **Instant Notifications**: HR receives immediate alerts when a new ticket is created.
3. **Efficient Ticket Management**: HR can view, manage, and update ticket statuses easily by having the chat with SlackApp.

### Technologies Leveraged: 💻

1. **Python**: For the core programming language.
2. **Slack App**: Custom Slack application developed for seamless integration of the chatbot into Slack channels
3. **OpenAI Assistant API**: Powers the AI capabilities of the chatbot.
4. **Airtable**: Used for efficient record-keeping.
5. **Digital Ocean**: Ensures seamless deployment.


### Additional Resources

### 🔗 <a href="https://github.com/Haseeb-Akhlaq/Slackbot-HR-Assistant" target="_blank">GITHUB</a>

### 🔗 <a href="https://www.youtube.com/watch?v=ckUuBymrZKA&t=17s" target="_blank">Youtube Tutorial</a>
