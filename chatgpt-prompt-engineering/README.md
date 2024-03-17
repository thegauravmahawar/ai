# ChatGPT Prompt Engineering

## Prerequisites

- OpenAI API Key

## Introduction

There are two types of LLMs (Large Language Models):

| Base LLM                                                                                                                | Instruction Tuned LLM         |
| ----------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| Predicts next word, based on text training data.                                                                        | Tries to follow instructions. |
| :white_check_mark: Once upon a time, there was a unicorn... that lived in a magical forest with all her unicorn friends |                               |
| :x: What is the capital of France?                                                                                      |                               |

Instruction Tuned LLMs use RLHF (Reinforcement Learning with Human Feedback) to make the system better able to learn and follow instructions.

We can tune the output by giving specific prompts and defining the tone of those prompts.

## Guidelines

**Prompting Principles:**

- Write clear and specific instructions
  - Use delimiters to clearly indicate distinct parts of the input (``, "", <>, :)
  - Ask for a structured output - JSON, HTML
  - Ask the model to check whether conditions are satisfied
  - "Few-shot" prompting
- Give the model time to "think"
  - Specify the steps required to complete a task
  - Ask for the output in a specified format
  - Instruct the model to work on its own solution before rushing to a conclusion

**Model Limitations: Hallucinations**

Boie is a real company, the product name is not real.

## Iterative

## Summarizing

## Transforming

## Expanding

## Chatbot

## Conclusion
