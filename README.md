# Embeddings_ResearchPaper

## 1. Goal

<p> The objective of this project is to develop a Virtual Assistant Bot on Whatsapp that can receive and process diverse types of documents, including research papers, enabling users to obtain accurate and timely responses to their inquiries.</p>

## 2. Technology

<p> In order to train the model on the submitted document, I utilized the OpenAI <b>Embeddings API</b>. This involved constructing a dataframe from the document and assigning tokens to track the length of sentences. Using the embeddings API, I generated embeddings for the dataframe, which can subsequently be used to match user questions and provide accurate responses. </p>

## Shortcomings

I am encountering a <b>RateLimitError</b> due to the utilization of the free API for this project, which is subject to certain restrictions. However, opting for the paid API would eliminate this issue entirely.
