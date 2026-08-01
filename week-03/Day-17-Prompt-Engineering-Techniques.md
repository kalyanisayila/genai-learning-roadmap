# Week 3 - Day 17: Prompt Engineering Techniques

# What is Prompt Engineering?
Prompt engineering is the practice of designing clear and effective prompts to help AI models generate accurate, relevant, and useful responses.

## Types of Prompting

#1. Zero-shot Prompting
No examples are provided. The model completes the task based only on the instruction.

Example:
Prompt:
Classify the sentiment: "The product is amazing."

Output:
Positive

---

#2. One-shot Prompting
One example is provided before asking the model to perform the task.

Example:
Input: "I love this phone."
Output: Positive

Input: "The battery drains quickly."
Output: Negative

---

#3. Few-shot Prompting
Multiple examples are given to help the model understand the pattern.

Example:
Input: "Excellent service." → Positive

Input: "Very slow delivery." → Negative

Input: "The quality is fantastic." → Positive

Input: "The app keeps crashing." → Negative

---

# 4. Chain of Thought (CoT) Prompting
The model is encouraged to reason through a problem step by step before producing the final answer.

Example:
Prompt:
A car travels 50 km per hour. How far will it travel in 4 hours? Think step by step.

Answer:
Distance = Speed × Time = 50 × 4 = 200 km.

Key Takeaways
- Prompt engineering improves AI responses.
- Zero-shot uses no examples.
- One-shot uses one example.
- Few-shot uses multiple examples.
- Chain of Thought is useful for reasoning and problem-solving.

# Conclusion
Choosing the right prompting technique can significantly improve the quality and accuracy of AI-generated responses.
