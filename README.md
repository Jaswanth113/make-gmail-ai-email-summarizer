# Make.com Gmail AI Summarizer

## Overview
This Make.com scenario automatically summarizes new Gmail using OpenAI (ChatGPT) and logs the results into Google Sheets. It streamlines Gmail management, extracts key action items, and allows easy team notifications.

## Workflow Components
- **Gmail** → Watches incoming emails in your inbox.
- **OpenAI (ChatGPT)** → Summarizes email content into 2-3 sentences and extracts action items.
- **Google Sheets** → Adds a new row for each email with fields: Date, From, Subject, Summary, Action Items.

## Setup Instructions

1. **Import Scenario**
   - Go to [Make.com](https://www.make.com/) → Create Scenario → Import → `make-gmail-ai-summarizer`.

2. **Connect Services**
   - **Gmail:** Connect your Gmail account.
   - **OpenAI:** Add your API key.
   - **Google Sheets:** Connect your Google Sheets account and select the target sheet.

3. **Configure Modules**
   - Gmail: Set the label/folder (Inbox or a custom label) to watch.
   - OpenAI: Ensure the model is GPT-3.5-turbo or GPT-4.
   - Google Sheets: Map fields correctly (Date, From, Subject, Summary, Action Items).

4. **Test Scenario**
   - Click **Run once** in Make.com.
   - Send yourself a test email.
   - Verify that a new row is added in Google Sheets with the summarized content.

5. **Activate Scenario**
   - Once confirmed, turn the scenario **ON** to automate new incoming emails.
