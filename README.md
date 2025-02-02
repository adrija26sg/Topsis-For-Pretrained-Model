#  Model Evaluation with TOPSIS
## description: 
  This project evaluates multiple text summarization models using ROUGE scores, inference time, and model size. 
  The TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method is used to rank the models.

## features:
  - Evaluates five models: BART, PEGASUS, T5, FLAN-T5, LongT5
  - Uses the XSum dataset for summarization
  - Computes ROUGE-1, ROUGE-2, ROUGE-L scores
  - Measures inference time and model size
  - Applies TOPSIS ranking to determine the best model
  - Generates visual comparisons of evaluation metrics

## dependencies:
  - torch
  - transformers
  - datasets
  - evaluate
  - numpy
  - pandas
  - matplotlib

## installation:
```python
  command: pip install torch transformers datasets evaluate numpy pandas matplotlib
```
## usage:
```python
command: python script.py
```
## steps:
    - Load a small subset of the XSum dataset.
    - Evaluate each model based on:
        - ROUGE scores (ROUGE-1, ROUGE-2, ROUGE-L)
        - Inference time
        - Model size
    - Rank the models using the TOPSIS method.
    - Generate bar charts comparing performance.
