## Challenge 4: LLM Fine-tuning for Compliance Checking

### Scenario:
You have a pre-trained LLM and need to fine-tune it for checking compliance with Bangladesh labor laws and international standards.

### Task:
Write a script that:
1. Loads a pre-trained model (e.g., BERT or RoBERTa)
2. Prepares a dataset of labeled compliance text (you can use dummy data for this challenge)
3. Implements a fine-tuning loop
4. Includes a function to use the fine-tuned model for classifying new text as compliant or non-compliant

### Sample Input:
labor_law_complaint_dataset.csv is small dataset of text snippets labeled as compliant or non-compliant with labor laws.

### Expected Output:
A fine-tuned model and a function that takes new text and returns a compliance classification with a confidence score.
