# Abandoned Cart Recovery Automation

## Overview

This project is an automated abandoned cart recovery workflow built with n8n.

It detects customers who left products in their shopping cart, waits before sending a reminder email, and updates the database after the email is sent to avoid duplicate reminders.

## Workflow

- Schedule Trigger
- Read abandoned carts from PostgreSQL
- Check cart status
- Wait before sending reminder
- Send personalized recovery email
- Update cart status in PostgreSQL

## Technologies

- n8n
- PostgreSQL
- Gmail SMTP
- Conditional Logic
- Email Automation

## Business Value

- Recovers lost sales
- Reduces abandoned carts
- Eliminates manual follow-up
- Prevents duplicate reminder emails
- Improves customer engagement

## Repository Contents

- Abandoned Cart Recovery.pdf

## Author

Mohamed
