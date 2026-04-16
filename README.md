# Zero-vs-Few-Shot

This repository is setup to display the expeirmental data, setup, and figures used for the evaluation of zero vs few shot prompting performance of GPT-3.5.

Overview:
The goal of the project is to find how the addition of demonstrations to a prompt is able to impact:
- EM or Exact Match
- F1 Scores
- Token usage
- Efficiency

Every result found was computed on a subset pf SQuAD QA pairs leveraging GPT 3.5

Prompting Conditions:
- Zero Shot: No need for demonstrations
- One Shot: One QA demonstration
- Two Shot: Two QA demonstrations
- Three Shot: Three QA demonstrations
