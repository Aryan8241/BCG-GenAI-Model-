# Financial Chatbot Prototype

## Overview
This is a simple rule-based chatbot prototype designed to answer predefined financial queries using manually extracted 10-K data for Microsoft, Tesla, and Apple.

## Predefined Queries
- What is the total revenue?
- How has net income changed over the last year?
- What are the total assets?
- What are the total liabilities?
- What is the operating cash flow?

## How It Works
- User enters a query in the terminal.
- The chatbot checks the input against predefined questions.
- If matched, it responds with a canned financial answer based on 2024 data.
- If unmatched, it replies with a default "Sorry..." message.

## Limitations
- Only supports predefined queries (no NLP).
- Responses are static and not dynamically calculated.
- Financial data is hardcoded from the 2024 dataset.
- Intended as an educational prototype, not a production AI chatbot.

## Running the Chatbot
```bash
python chatbot.py
```
Type `quit` to exit.
