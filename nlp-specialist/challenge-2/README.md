## Challenge 2: Sentiment Analysis for Bangla Product Reviews

### Scenario:
You're developing a sentiment analysis model for an e-commerce platform that primarily deals with Bangla-speaking customers. The model needs to analyze product reviews and classify them as positive, negative, or neutral.

### Task:
1. Implement a simple sentiment analysis model using any method of your choice (e.g., rule-based, machine learning, or deep learning)
2. The model should be able to handle common Bangla expressions and idioms related to product satisfaction
3. Include a function to preprocess the Bangla text (handle Unicode properly, remove noise, etc.)
4. Provide a way to explain the model's decision (e.g., highlighting key phrases that influenced the sentiment classification)

### Sample Input:
Provide a CSV file with Bangla product reviews and their corresponding ratings (1-5 stars).

### Expected Output:
A trained model and a function that takes a new Bangla review text and returns:
- The predicted sentiment (positive, negative, or neutral)
- A confidence score for the prediction
- Key phrases that influenced the decision