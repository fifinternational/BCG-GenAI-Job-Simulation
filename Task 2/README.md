# Chatbot Prototype: Financial Analysis

## Overview
Building a fully functional AI chatbot for financial analysis involves advanced techniques, but we'll create a simplified prototype to introduce basic chatbot development concepts. This prototype will respond to predefined financial queries based on previously analyzed data.

## Step 1: Preparation

### Review Analyzed Data
Quickly review the financial data analyzed in Task 1 to understand available information.

### Set Up Your Environment
Ensure Python is installed along with essential libraries like pandas for data handling.

## Step 2: Chatbot Design and Data Preparation

### Define Predefined Queries
Select 3 to 5 common financial queries:
- "What is the total revenue?"
- "How has net income changed over the last year?"
- Add more queries as necessary based on your data.

### Prepare Responses
Use the analyzed financial data to create canned responses for each query.

## Step 3: Basic Chatbot Development

### Chatbot Logic
Write a simple Python script using if-else statements to match user input to predefined responses.

```python
def simple_chatbot(user_query):
   if user_query == "What is the total revenue?":
       return "The total revenue is [amount]."
   elif user_query == "How has net income changed over the last year?":
       return "The net income has [increased/decreased] by [amount] over the last year."
   # Add more conditions for other predefined queries
   else:
       return "Sorry, I can only provide information on predefined queries."
```
## Step 4: Demonstration and Documentation
### Test Your Chatbot
Test the chatbot with predefined queries to ensure accurate responses.

### Documentation
Prepare a brief summary explaining:

How the chatbot works.
Predefined queries it can respond to.
Limitations or areas for improvement.
