# Week 1, Task 2: Prompt Engineering for a Hypothetical AI Assistant

## 🎯 Objective
Design and demonstrate effective prompt engineering techniques for a hypothetical AI assistant to perform specific Natural Language Processing (NLP) tasks.

## 📋 Requirements
1.  **Select NLP Tasks:** Choose **two distinct NLP tasks** that an AI assistant might perform (e.g., text summarization, sentiment analysis of customer reviews, extracting key entities from a news article, or answering factual questions based on provided context).
2.  **Design System & User Prompts:** For each selected NLP task:
    *   **System Prompt:** Craft a concise system prompt that sets the persona, instructions, and constraints for the hypothetical AI assistant.
    *   **User Prompts:** Design at least three diverse user prompts that would elicit the desired output for the given task. These prompts should cover different scenarios or input variations.
    *   **Expected Outputs:** For each user prompt, provide an example of the ideal expected output from the AI assistant.
3.  **Simulated Interaction Script:**
    *   Write a simple Python script (`prompt_simulator.py`) that demonstrates how your designed prompts would be used.
    *   This script does **not** need to call a real LLM API. Instead, it should clearly show the structure of your prompts (system + user input) and then print the example expected output for each.
    *   The script should allow for easy demonstration of different prompts and their hypothetical results.
4.  **Prompt Engineering Documentation:** Provide a `README.md` file within your task directory detailing:
    *   The two NLP tasks you chose and why.
    *   A clear explanation of each system prompt and your rationale behind its design (e.g., why certain constraints or personas were chosen).
    *   An explanation for each user prompt and how it's designed to guide the model.
    *   Any considerations for making prompts more robust (e.g., few-shot examples, chain-of-thought, input formatting).

## ✨ Deliverables
*   Python script (`prompt_simulator.py`) demonstrating prompt structures and expected outputs.
*   A `README.md` file documenting your prompt engineering choices and rationale.