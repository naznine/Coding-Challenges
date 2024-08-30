## Challenge 1: Data Preprocessing for Multilingual Garment Orders

### Scenario:
You're working with order data from various international buyers. The data includes text in English, Bangla, and occasionally Hindi or Chinese. You need to preprocess this data for input into your LLM.

### Task:
Write a Python function that takes a pandas DataFrame of order data and performs the following:
1. Identifies the language of each text field
2. Translates non-English text to English
3. Normalizes all text (lowercase, remove special characters)
4. Handles missing data appropriately

### Sample Input:
```python
import pandas as pd

data = pd.DataFrame({
    'order_id': [1, 2, 3],
    'product': ['T-shirt', 'জিন্স', '衬衫'],
    'quantity': [1000, 500, 750],
    'special_instructions': ['Rush order', 'দ্রুত প্রয়োজন', 'Standard shipping']
})
```

### Expected Output:
A preprocessed DataFrame with all text in normalized English.