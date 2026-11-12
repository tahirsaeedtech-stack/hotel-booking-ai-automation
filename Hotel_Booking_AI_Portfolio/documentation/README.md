# AI-Powered Hotel Booking Automation

## Project Overview

A no-code hotel booking automation prototype developed using **n8n Cloud and Google Gemini AI**.

The system validates booking information, analyzes valid bookings, classifies priorities, and routes problematic records for human review.

## Technology Stack

- n8n Cloud
- Google Gemini API
- JSON
- Rule-based validation

## Automation Workflow

1. Receive sample hotel bookings.
2. Split bookings into individual records.
3. Validate booking input data.
4. Send valid bookings to Gemini AI.
5. Parse structured AI responses.
6. Verify AI priority against business rules.
7. Route approved records and exceptions to separate processing paths.

## Key Features

- Multiple booking processing
- Input validation
- AI-powered priority classification
- Structured JSON parsing
- AI decision verification
- Human-review routing

## Test Results

| Metric | Result |
|---|---|
| Total bookings | 5 |
| Approved for processing | 3 |
| Invalid input review | 2 |
| AI priority review | 0 |
| End-to-end execution | Successful |

## Current Limitations

This prototype uses sample booking data. It does not yet connect to a live hotel booking platform, send customer notifications, or save records to a database.

Additional error handling and production testing are required before real-world deployment.

## Project Files

- **Workflow:** `workflow/Hotel_Booking_AI_Automation_v1.json`
- **Screenshots:** `screenshots/`