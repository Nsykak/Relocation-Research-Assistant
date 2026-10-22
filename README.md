Relocation Research Assistant

A Python application using retrieval-augmented generation (RAG) to help people research relocation or working abroad, using the UK as an example.

What I built

I built a RAG pipeline combining public government information on healthcare, security, cost of living and accommodation. A weather API added destination conditions to support the research.

How it worked

* LangChain connected retrieval, model API calls and responses.
* OpenAI and Anthropic APIs provided language-model capabilities.
* Semantic chunking helped preserve context when preparing information for retrieval.
* Pinecone stored embeddings and supported vector retrieval. I chose it to support a growing knowledge base as more destination information was added.
* LangSmith supported tracing and evaluation of the workflow.

Reliability and human review

The workflow included human-in-the-loop review, error flagging and retrieval retries when information could not be retrieved. I reviewed outputs and investigated failures rather than assuming generated answers were correct.

My contribution

My work covered data preparation, retrieval and API integration, workflow evaluation and cloud deployment. The project brought together practical AI engineering and attention to useful, reliable outputs.

Repository scope

This repository contains a project write-up only. Source code, credentials, private data and confidential implementation details are not included.
