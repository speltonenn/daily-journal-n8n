# daily-journal-n8n
A personal daily journaling workflow. Sends 4 morning prompts via Telegram, receives my answers, and uses Claude AI to send back a warm personal reflection.
# My Daily Journal — n8n Workflow

A simple but powerful personal journaling workflow that runs every morning automatically.

## What it does
1. Every morning at 8am sends 4 journal prompts to Telegram
2. Waits for my reply
3. Sends my answers to Claude AI
4. Claude writes a warm personal reflection based on my answers
5. Reflection is sent back to me on Telegram

## The 4 daily prompts
1. What is one thing you are grateful for yesterday — or one thing you did well?
2. What is your one goal for today — or one task you want to complete?
3. What is something you noticed about yourself yesterday?
4. Who were you kind to yesterday — or who was kind to you?

## Tools used
- n8n (workflow automation)
- Telegram Bot API
- Anthropic Claude API

## Nodes
- Daily 8am Journal Trigger
- Send Morning Journal Questions
- Listen for User Reply
- Generate Personal Reflection
- Send Reflection to User

## Setup
1. Create a Telegram bot via @BotFather
2. Get your Anthropic API key from console.anthropic.com
3. Import the workflow JSON into n8n
4. Add your credentials
5. Publish the workflow
