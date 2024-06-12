# Gen AI Projects

## Traditional AI Development x Gen AI Development

Before we understand how Gen AI applications are built, it’s important to know how traditional AI applications were developed in the past. In summary, **supervised learning** was the key to develop most AI applications.

With the birth of **prompt-based development** approach enabled by generative AI, supervised learning approach was not needed anymore (in most cases). The integration with LLMs’ APIs and the usage of prompt-base development started a new era of developing AI applications.

### Supervised Learning Development

The traditional method (e.g. Supervised Learning) involves:

1. Collecting labeled data
2. Training an AI model using this data to (learn how to output B based on an input A)
3. Deploying the model on a cloud service.

This process is described as **time-consuming**, often taking 6-12 months to complete.

### Prompt-based Development

In contrast, the prompt-based development approach requires merely specifying a prompt in code and using a single line of code to call a large language model (LLM) to get a response.

This method drastically reduces development and deployment time from months to potentially days or weeks.

Therefore, the ease of building applications with generative AI is lowering the barrier to entry for developers, leading to a proliferation of AI applications.

Keep in mind that generative AI works better with **unstructured data** such as **text, images, and audio**. It is not advisable to use it with structured data, like databases, due to the limitations of generative AI.

## Terminologies

- **Token Definition and Cost**: A token, which can be a word or part of a word, is the **basic unit of text processed by LLMs**. 

> **Token vs Word**: It's explained that a token corresponds to roughly 3/4 of a word, meaning that generating text will require more tokens than the actual number of words. This is due to how LLMs may split fewer common words into multiple tokens.

## Lifecycle of a Gen AI Project

The usual process of developing a new Gen AI project consists in the following steps:

1. **Project Scoping**: The initial step involves defining the purpose and goals of the software, such as creating a restaurant reputation monitoring system.

2. **Prototype Development**: Quickly building a prototype, despite its initial imperfections, to facilitate early testing and improvements.

3. **Internal Evaluation**: Testing the prototype internally to identify and correct inaccuracies, such as misinterpretations of sentiment in customer reviews.

4. **Deployment and Monitoring**: After achieving sufficient confidence in the system's performance, it is deployed for external use, with ongoing monitoring to catch and correct any errors identified by users.

Keep in mind that developing Generative AI applications involves a **continuous cycle of iteration and improvement**.

The system is consistently refined through feedback and insights gained at every stage, with the flexibility to revisit and reassess previous steps as necessary.

Additionally, the development process is **empirical** in nature, marked by a **highly experimental** approach that encompasses continuous trials, the identification of errors, and the meticulous refinement of the system.

## Costs

The cost of utilizing generative **AI varies based on the selected LLM** - large language model - yet it remains **relatively low** compared to other technologies.

> For instance, OpenAI's GPT-3.5, GPT-4, Google's PaLM 2, and Amazon's Titan Lite all charge less than or equal to $0.01 per 1,000 tokens. Specifically, GPT-3.5 costs just $0.002 for every 1,000 tokens.

The cost for input tokens (prompts) is typically lower compared to the cost for output tokens. This pricing model is common among various LLM providers, where the focus is on the number of tokens processed, especially in generating responses.

In general, the cost is relatively low, especially if it enhances productivity, however, the cost can become significant for free products with a large user base.

In conclusion, the usage LLMs is generally cheaper than most people assume, and it’s highly recommended to consider the cost-effectiveness of incorporating LLMs into legacy or even modern applications.