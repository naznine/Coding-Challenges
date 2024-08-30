## Challenge 1: Multilingual Named Entity Recognition for Customer Queries

### Scenario:
You're working on a customer service chatbot for a major telecommunications company in Bangladesh. The chatbot needs to handle customer queries in Bangla, English, and code-mixed text. Your task is to implement a Named Entity Recognition (NER) system that can identify key entities like phone numbers, account numbers, and service types across these language varieties.

### Task:
Write a Python function that:
1. Takes a string of text (which could be in Bangla, English, or code-mixed)
2. Identifies and extracts the following entities:
   - Phone numbers (BD format)
   - Account numbers (alphanumeric)
   - Service types (e.g., prepaid, postpaid, internet package names)
3. Returns the extracted entities with their positions in the text

### Sample Input:
```python
text1 = "আমার ফোন নাম্বার 01712345678 এবং আমার account number হলো ACC123456"
text2 = "I want to switch my prepaid connection to postpaid. My phone number is 01898765432."
text3 = "Amr internet package ta upgrade korte chai. Account number: XYZ789012"
```

### Expected Output:
A dictionary containing the extracted entities and their positions for each input text.