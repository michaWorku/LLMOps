# LLMOps: Building Real-World Applications With Large Language Models

## Overview

This repository provides a structured approach to LLMOps, covering various aspects of Large Language Model (LLM) development, deployment, evaluation, and safety considerations. It includes Jupyter notebooks demonstrating different LLM applications, fine-tuning techniques, evaluation strategies, and model monitoring.

## Repository Structure

### 1. Prompt Engineering Basics (`1_prompt_engineering_basics.ipynb`)
- Introduces fundamental prompt engineering techniques.
- Covers best practices such as specificity, clarity, prompt chaining, and role-playing.

### 2. Advanced Prompt Engineering (`2_prompt_engineering_advanced.ipynb`)
- Explores advanced prompting techniques including:
  - Zero-shot, Few-shot, and Chain-of-Thought (CoT)
  - ReAct (retrieval-augmented generation)
  - Prompt chaining and Tree of Thoughts
  - Data Augmentation / RAG
- Enhances LLM reasoning and task-specific performance.

### 3. Prompt Tracking with Comet (`3_prompt_tracking_comet.ipynb`)
- Demonstrates how to track prompts and model responses using Comet.
- Covers logging techniques and evaluation strategies.

### 4. Fine-Tuning an Emotion Classifier (`4_fine_tuning_emotion_classifier.ipynb`)
- Guides through fine-tuning an LLM for emotion classification.
- Covers dataset preparation, tokenization, training, and model registration.

### 5. Evaluating a Fine-Tuned Model (`5_evaluating_finetuned_model.ipynb`)
- Focuses on assessment techniques, confusion matrices, and validation methods.
- Discusses AI safety measures and bias mitigation.

### 6. Customer Support Chatbot (`customer_support_chatbot.ipynb`)
- Builds an AI-powered chatbot for customer support.
- Implements retrieval-based responses using OpenAI.
- Ensures safety and factual accuracy in generated responses.

### 7. LLM-Powered Evaluation System (`LLM_powered_evaluation_system.ipynb`)
- Develops an automated LLM-based evaluation system.
- Performs evaluations using few-shot and zero-shot templates.
- Logs results to Comet for tracking and analysis.

### 8. Clickbait Detection (`project_clickbait.ipynb`)
- Implements an LLM-powered clickbait detector.
- Logs results using Comet ML.
- Develops tagging and classification techniques.
- Fine-tunes a transformer model for improved accuracy.
- Builds a Gradio app for interactive clickbait detection.

### 9. AI Safety (`AI_safety.ipynb`)
- Covers prompt injection attacks and defense mechanisms.
- Demonstrates OpenAI moderation API usage.
- Implements safe-unsafe classification for AI-generated content.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Transformers (Hugging Face)
- Comet ML (for experiment tracking)
- OpenAI API (for LLM integration)
- Other dependencies as specified in individual notebooks