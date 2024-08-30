## Challenge 4: Query Intent Classification for Digital Financial Services

### Scenario:
You're working on an AI assistant for a mobile financial service provider in Bangladesh. The assistant needs to understand and classify user intents from their queries, which could be in Bangla or English.

### Task:
1. Design a multi-class classification model to identify user intents (e.g., check balance, send money, pay bill, get help)
2. The model should handle both Bangla and English inputs
3. Implement a simple few-shot learning mechanism to allow easy addition of new intents in the future
4. Include a confidence score with each classification

### Sample Input:
Provide a JSON file with sample user queries in both Bangla and English, along with their corresponding intents.

### Expected Output:
A trained model and a function that takes a new user query (in either Bangla or English) and returns:
- The predicted intent
- A confidence score for the prediction
- Top 3 most likely intents (for cases where the model is uncertain)