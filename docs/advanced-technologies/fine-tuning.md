# Fine-tuning

Besides RAG, Fine-tuning is another technique used for enhancing and enrich LLMs, but the approach is a little bit different and relatively more complex to implement. 

It consists of **training the model on a new dataset to modify LLM behavior or style**.

For Language Modeling Task Fine-Tuning, raw unsupervised text is used, where the next token serves as the prediction label.
For Supervised Q&A Fine-Tuning, question-answer pairs are employed to improve the model’s performance in question-answering tasks.

It is used commonly used for:

- Absorbing larger contexts than the LLM’s default input length.
- Generating outputs in a specific style.

## Common Real Life Fine-tuning Applications

- Enhancing task specificity when prompts are insufficient 

    Example: Summarizing customer service calls with specific details.

    At this context, the LLM needs to learn from previous data, specific terminology and important topics that needs to be highlighted at a customer service application.

- Mimicking particular writing or speaking styles that are hard to define through prompts alone.

    Example: Use someone's voice to generate a voice message using her tone and speak style.

- Acquiring domain-specific knowledge (e.g., medical, legal, or financial terminology) not present in general training data.

## Benefits of using Fine-tuning

- Allows for precise customization of LLM outputs.
- Expands the range of tasks and styles an LLM can handle.
- Makes domain-specific knowledge accessible to LLMs.
- Facilitates the use of smaller, more efficient models for specific applications.

In summary, Fine-tuning makes a general LLM more **task-specific** and also allows **adaptation to specific domains** or tasks.