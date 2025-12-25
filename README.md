# Markdown to Google Docs Converter

This project converts markdown-based meeting notes into a formatted Google Doc using the Google Docs API.  
It preserves headings, nested lists, checkboxes, mentions, and footer styling.

## Features
- Google Docs API integration
- Heading level mapping (H1–H3)
- Nested bullet points
- Markdown checkboxes → Google Docs checkboxes
- Highlighted assignee mentions
- Styled footer metadata

## Setup

### Requirements
- Google account
- Python 3
- Google Colab

### Dependencies
Installed automatically in Colab:
- google-api-python-client
- google-auth
- google-auth-oauthlib

## How to Run
1. Open the notebook in Google Colab
2. Run all cells top to bottom
3. Authenticate with your Google account when prompted
4. A new Google Doc will be created in your Drive

## Notes
- The markdown is parsed line-by-line for clarity and control
- Requests are batched for better performance
- Error handling is included for API initialization and updates