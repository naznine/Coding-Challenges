## Challenge 3: Code-Mixed Language Detection and Separation

### Scenario:
Many social media users in Bangladesh use a mix of Bangla and English in their posts, often writing Bangla words in English script (romanized Bangla). You need to develop a system that can detect and separate the languages in such code-mixed text.

### Task:
Write a Python class that:
1. Takes a string of code-mixed text
2. Identifies which parts of the text are in English, romanized Bangla, and Bangla script
3. Separates the text into three categories: English, romanized Bangla, and Bangla script
4. Optionally, transliterates the romanized Bangla into Bangla script

### Sample Input:
```python
text = "Amar sonar Bangla, I love you. তোমার আকাশ তোমার বাতাস আমার prane bajay bashi."
```

### Expected Output:
A dictionary containing separated text for each language category and the transliterated version of romanized Bangla.