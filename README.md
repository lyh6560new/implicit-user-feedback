# implicit-user-feedback
This is the official github repo for paper ["User Feedback in Human-LLM Dialogues: A Lens to Understand Users But Noisy as a Learning Signal"](https://arxiv.org/pdf/2507.23158).

## Manually Annotated Feedback Dataset
[Hf link](https://huggingface.co/datasets/yuhan-nlp/multiturn-feedback)
```python
from datasets import load_dataset

dataset = load_dataset("yuhan-nlp/multiturn-feedback")
sparse_eval = dataset['sparse']
dense_eval = dataset['dense']
```
