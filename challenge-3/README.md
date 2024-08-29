## Challenge 3: Agentic Workflow for Quality Control

### Scenario:
Design a simple agentic workflow system for quality control in a garment production line. The system should be able to decide when to escalate issues to human supervisors.

### Task:
Implement a Python class for a quality control agent that:
1. Takes input data about garment measurements and defect rates
2. Uses a decision tree or simple rule-based system to classify the quality of a batch
3. Decides whether to approve the batch, reject it, or escalate to a human supervisor
4. Logs its decisions and the reasons for them

### Sample Input:
```python
batch_data = {
    'measurements': {
        'length': 25.2,
        'width': 15.8,
        'sleeve_length': 22.1
    },
    'defect_rate': 0.02,
    'batch_size': 1000
}
```

### Expected Output:
An instance of the QualityControlAgent class that can process batch data and output decisions with explanations.
