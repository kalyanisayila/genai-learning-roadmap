# Week 2 - Day 12: Calling APIs Using Python

## Objective
Learn how to fetch data from an API using Python and the requests library.

## What is an API?
An API (Application Programming Interface) allows one application to communicate with another and exchange data.

## Install Requests Library
bash
pip install requests

## Python Example
python
import requests

url = "https://jsonplaceholder.typicode.com/posts/1"

response = requests.get(url)

print(response.status_code)
print(response.json())

## Output
- Status Code: 200
- JSON data is returned from the API.

## What I Learned
- What an API is.
- How to use the requests library.
- How to send a GET request.
- How to read JSON data.

## Mini Practice
Fetch user details from:
https://jsonplaceholder.typicode.com/users/1

Print:
- Name
- Email
- City

## Conclusion
Today I learned how to connect Python with an API and retrieve data. This is the foundation for working with AI APIs like OpenAI and Gemini.
