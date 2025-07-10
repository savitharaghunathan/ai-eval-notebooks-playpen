# Ragas Evaluation Notebooks

This folder contains Jupyter notebooks for evaluating RAG (Retrieval-Augmented Generation) systems using the Ragas framework.

## Overview

Ragas is a framework for evaluating RAG systems using LLM-based metrics. These notebooks demonstrate how to use Ragas to evaluate the quality of question-answer pairs.

## Notebooks

### 1. `eval.ipynb`
Basic evaluation notebook with a simple example:
- Single question-answer pair evaluation
- Demonstrates the core Ragas workflow
- Shows how to set up data and run metrics

### 2. `eval_any_question.ipynb`
Interactive evaluation notebook:
- Input widgets for question and response
- Real-time evaluation
- User-friendly interface for testing custom Q&A pairs

### 3. `multiple_questions.ipynb`
Batch evaluation with multiple examples:
- Pre-defined Q&A pairs with varying quality
- Demonstrates how different response qualities score
- Shows metrics for good, incomplete, and incorrect responses

## Metrics Used

The notebooks evaluate using these Ragas metrics:

- **Faithfulness**: Measures if the answer is faithful to the provided context
- **Context Precision**: Measures if the retrieved context is relevant to the question
- **Context Recall**: Measures if all relevant context was retrieved
- **Answer Relevancy**: Measures if the answer is relevant to the question

## Understanding Scores

- **1.000**: Perfect score (answer is completely faithful/relevant)
- **0.500-0.999**: Good to very good quality
- **0.000-0.499**: Poor quality (unfaithful, irrelevant, or incorrect)
