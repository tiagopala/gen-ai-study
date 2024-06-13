# Instruction Tuning

Due the nature of LLMs to be trained on a vast amount of text data from the internet. LLM learns to predict the next word in a sequence.

However, this initial training is not enough for the LLM to follow specific instructions or give precise answers.

For instance, if you ask, "What is the capital of France?" the model might generate related but irrelevant questions instead of answering "Paris."

Through the usage of instruction tuning, it is possible improve the LLM's ability to **follow specific instructions** and **give relevant answers**.

## How it works

This involves fine-tuning the pre-trained LLM using examples of good responses to various prompts.

For example, if you ask, "What is the capital of South Korea?" the model is fine-tuned to answer "Seoul."

> At this example, we are "teaching" the LLM to answer questions correctly.

The model should be trained on different types of prompts such as factual questions, brainstorming ideas, or creative tasks like writing a poem, and learns to provide appropriate responses.

## Safety Measures

To make the model even safer, it should also be trained on prompts that should be discouraged.

For instance, asking something "How to break into Fort Knox?" and the desired response would be something like, "I can't assist with that."