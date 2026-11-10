# AI Customer Support Automation

## Project Overview

An AI-powered customer support automation built using **n8n, Tally, OpenAI, and Gmail**.

This project automates the process of receiving customer inquiries, analyzing questions with AI, and generating personalized email responses.

The goal is to help businesses reduce repetitive customer support tasks, improve response times, and streamline communication.

## Technologies Used

- **n8n:** Workflow automation platform
- **Tally:** Customer inquiry form
- **OpenAI (GPT-4o-mini):** AI-powered customer response generation
- **Gmail:** Automated email delivery
- **JSON:** Workflow data and configuration

## How It Works

1. **Customer submits a Tally form**
   - Full Name
   - Email Address
   - Inquiry Category
   - Customer Question

2. **Tally Trigger receives the submission**
   - Automatically starts the n8n workflow.

3. **Edit Fields organizes customer information**
   - Extracts the customer's name, email, inquiry category, and question.

4. **OpenAI generates a response**
   - Analyzes the customer's question.
   - Generates a personalized, professional email.
   - Avoids inventing company information.
   - Recommends human follow-up when information is unavailable.

5. **Gmail sends the response**
   - Automatically emails the AI-generated response to the customer.

## Workflow

Tally Form → Tally Trigger → Edit Fields → OpenAI → Gmail → Customer

## Key Features

- Automated customer inquiry collection
- Dynamic customer information mapping
- AI-generated personalized responses
- Basic inquiry categorization through the form
- Automatic email delivery
- Instructions to reduce unsupported AI-generated claims
- Human follow-up recommendations for unanswered questions

## Testing

Successfully tested the complete automation using sample customer inquiries.

**Results:**
- Customer submissions successfully triggered the workflow.
- Customer information was extracted correctly.
- OpenAI generated personalized email responses.
- Gmail successfully delivered the responses.
- The workflow completed without requiring manual execution of individual nodes.

## Project Status

**Working prototype — built, tested, and published in n8n.**

This project was developed as a hands-on learning experience to strengthen skills in workflow automation, API integrations, AI applications, and customer communication systems.
