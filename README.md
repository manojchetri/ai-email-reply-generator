# AI Email Reply Generator

An n8n automation that uses Google Gmail and Google Gemini to automatically generate and send replies to incoming emails.

## Workflow

Gmail Trigger
↓
Get Email
↓
Prepare Email Data
↓
Gemini AI Reply Generator
↓
Gmail Send Message
↓
Add AI-PROCESSED Label
↓
Remove AI-REPLY Label

## Features

- Detects emails with the AI-REPLY Gmail label
- Extracts sender, subject and email body
- Uses Google Gemini to generate a professional reply
- Automatically sends the generated reply
- Preserves the original email context/thread when supported
- Marks processed emails with AI-PROCESSED
- Removes the AI-REPLY label after processing
- Reduces repetitive manual email work

## Technologies

- n8n
- Gmail
- Google Gemini
- GitHub

## Workflow Purpose

The workflow automates repetitive email responses while keeping the process simple and reliable.

## Important

The exported workflow JSON should not contain API keys, passwords, OAuth secrets, or other sensitive credentials.
