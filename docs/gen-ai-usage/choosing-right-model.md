# Choosing the right model (LLM)

There are a few considerations that you must be think of when choosing the best LLM for your application such as model size, capabilities and open-source or closed-source models.

## Model Size and Capability

| Parameters                | Best Use Cases                                                   | Examples                                 |
| ------------------------- | ---------------------------------------------------------------- | ---------------------------------------- |
| 1 Billion Parameters      | Best for pattern matching and basic knowledge tasks              | sentiment analysis in restaurant reviews |
| 10 Billion Parameters     | Greater world knowledge and are better at following instructions | applications like food order chat bots   |
| >= 100 Billion Parameters | Rich world knowledge and complex reasoning capabilities          | Ideal for tasks requiring deep knowledge or complex reasoning, like brainstorming tools |

## Open-source vs. Closed-source Models

### Closed-source models characteristics

- Accessible via cloud programming interfaces.
- Easy to integrate.
- Often inexpensive due to optimizations by hosting companies. 
- They pose a risk of vendor lock-in.

### Open-source models characteristics

- Offer full control.
- The ability to run on various devices including on-premises.
- Ensure data privacy. 

They are commonly preferable for applications requiring strict data privacy, such as those handling electronic health records.

Also remember that the development of applications using LLMs is a highly empirical process, so you should try different models to find the best fit for specific applications.