# Week 2 - Day 13: API Keys and Environment Variables

## Objective
Learn what API keys are and how to store them securely using environment variables.

## What is an API Key?
An API key is a unique code that allows you to access an API securely.

## Why Use Environment Variables?
Environment variables keep your API keys safe by storing them outside your code.

## Python Example

python
import os

api_key = os.getenv("API_KEY")
print(api_key)

## What I Learned
- What an API key is.
- Why API keys should not be hardcoded.
- How to use environment variables in Python.

## Conclusion
Today I learned how to securely manage API keys using environment variables. This is an important step before working with AI APIs like OpenAI and Gemini.
