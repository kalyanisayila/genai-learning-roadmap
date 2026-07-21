# Week 2 - Day 14: Read Text and PDF Files in Python

## Objective
Learn how to read text (.txt) and PDF (.pdf) files using Python.

## Reading a Text File

python
with open("sample.txt", "r") as file:
    content = file.read()
    print(content)

## Reading a PDF File

Install the required library:
bash
pip install PyPDF2

Python example:

python
from PyPDF2 import PdfReader

reader = PdfReader("sample.pdf")

for page in reader.pages:
    print(page.extract_text())

## What I Learned

- How to read text files in Python.
- How to extract text from PDF files.
- How file handling works in Python.
- Why reading documents is useful for AI applications.

## Conclusion

Today I learned how to read text and PDF files using Python. This skill is useful for processing documents and building AI applications like chatbots and document summarizers.
