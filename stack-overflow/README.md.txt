# Stack Overflow Multi-label Dataset for Explainability

This dataset contains 499 instances extracted from the Stack Overflow platform.

Each instance is represented by 100 binary attributes (Bag-of-Words representation)
and annotated with 5 multi-labels: Asp.net, Java, MySQL, PHP, Python.

## Files
- `stack.csv`: 499 rows × 105 columns (100 features + 5 binary labels)

## Format
- Attributes: columns 1–100 (binary values: 0 or 1)
- Labels: columns 101–105 (multi-label binary encoding)

## Usage
This dataset is intended for evaluating explainability methods in multi-label classification settings.

## Reference
If you use this dataset, please cite:
Radja, Hakim et al. (2025). *Stack Overflow multi-label dataset for explainability evaluation*.  
https://github.com/hakimradja/fca-explainability/stack-overflow