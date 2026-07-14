# Day 10 – JSON Basics

## What I Learned
- What is JSON?
- Difference between Python Dictionary and JSON
- Convert Python Dictionary to JSON using `json.dumps()`
- Convert JSON to Python Dictionary using `json.loads()`
- Why JSON is used in APIs and Generative AI

## Python Example

```python
import json

student = {
    "name": "Kalyani",
    "age": 21,
    "course": "B.Tech CSE"
}

json_data = json.dumps(student)
print(json_data)

python_data = json.loads(json_data)
print(python_data["name"])
```

##  Key Takeaways
- JSON is a lightweight data format.
- APIs use JSON to exchange data.
- Python's `json` module helps work with JSON easily.
- JSON is essential for AI applications.

## Day 10 Completed 
