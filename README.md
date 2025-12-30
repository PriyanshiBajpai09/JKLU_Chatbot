# JKLU Information Chatbot (LLM Guardrails)

## Overview
This project is an AI-based information chatbot designed to answer queries related to
JK Lakshmipat University (JKLU). The chatbot uses Large Language Models (LLMs) with
input and output guardrails to ensure accurate, domain-specific, and hallucination-free
responses.

## Problem Statement
General-purpose LLMs may generate incorrect or misleading answers when asked
institution-specific questions. This project addresses the issue by restricting the
model to a verified JKLU dataset and applying guardrails to control both user inputs
and generated outputs.

## Solution Approach
- Implemented input filtering to allow only JKLU-related queries
- Applied output validation to prevent hallucinated or irrelevant responses
- Used a static, verified dataset containing JKLU information
- Developed and tested the chatbot in Google Colab using Python

## Features
- Domain-restricted AI chatbot for university-related queries
- Reduced hallucination through input and output guardrails
- Clear and controlled response generation
- Simple and modular notebook-based implementation

## Tech Stack
- Python
- Google Colab
- Large Language Models (LLMs)
- Prompt Engineering
- Input & Output Guardrails

## How to Run
1. Open the provided `.ipynb` file in Google Colab
2. Run all cells sequentially
3. Enter JKLU-related queries as input to test the chatbot

## Outcome
The chatbot provides reliable and consistent responses for JKLU-related questions,
demonstrating the effective use of guardrails in LLM-based systems.
