# Retrieval Augmented Generation (RAG)

Basically, RAG is a technique used alongside LLMs for generating **more accurate and contextually** relevant responses by **providing additional and specific knowledge** beyond general or open-source data used to train these models.

RAG combines generative capabilities with the ability to search for and incorporate relevant information from a **knowledge base**.

It excels at providing access to **dynamic external data sources**. Through RAG, it’s possible to utilize company-specific documents or internal information about your business, allowing the LLM to provide precise and specific answers.

> Be in mind, that **transparency in response generation** is a key feature of RAG. It's a good practice to show the knowledge sources used to generate the output.

## How It Works:

1. **Document Retrieval**: Identifies relevant documents based on the prompt (e.g., employee parking policy).

2. **Prompt Construction**: Incorporates relevant information from documents into the prompt for the LLM.

3. **Answer Generation**: LLM uses the enriched prompt to generate a specific answer.

For example: Asking a general chat system about company-specific parking results in vague responses due to lack of specific knowledge.

By using RAG, you can use the facilities policies as a knowledge source to answer those type of questions.

![how-rag-works-example](/images/how-rag-works.png)

After finding the correct document related to the question asked on the prompt, only the most relevant document parts (due token limitations and compute efficiency) are added at the final prompt, called enriched prompt. 

Generally, the responses also include the documents used for generating the outputs.

## Real Life RAG Applications

- Chatting with PDFs: PandaChat, AskYourPDF and ChatPDF.
- Answering questions based on website articles as Coursera Coach, SnapChat bot and Hubspot chat bot.
- New forms of web search as Microsoft Bing, Google's generative AI feature and Perplexity startup's own search base application.

## RAG’s Impact and Key Takeaways

The usage of RAG has been transforming the web search and information retrieval.

RAG enhances the capabilities of LLMs, allowing them not only to use their computational intelligence to **understand contexts** and **make cohesive decisions** but also to access and **integrate knowledge from external databases**. 

This makes them not just engines of reason but also facilitators of access to a vast array of updated and specific information, significantly **improving the quality and relevance of their responses**, besides it enables LLMs to process and reason through provided context, expanding their application scope.

In summary, the potential of RAG offers a promising direction for the development and application of LLMs, supporting a wide range of applications, being very versatile.