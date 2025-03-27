# ShopTalk-RAG-and-Agent
This repo contains both the implementation. One is RAG based and other one is Agent based. It is smart Shopping Assistant that enhances product discoverability.

# Problem Statement
The goal is to build a smart assistant that can comprehend user queries in natural language, find the most relevant products, and provide recommendations in a conversational style. Key aspects include:
●	User Input Understanding: Recognizing complex queries, synonyms, and variations.
●	Retrieval Augmented Generation (RAG): Efficiently retrieving relevant products based on user queries.
●	Natural Language Generation (NLG): Transforming identified products into coherent and human-like recommendations.
●	Agents: Implementing agentic flow to manage user interactions effectively, adding another layer to the system's conversational capabilities.
●	Evaluation: Using tools like Langsmith to evaluate model performance, including comparisons between RAG and agent-based approaches.
●	User Experience Optimization: Providing clear, contextually relevant recommendations to enhance satisfaction.
●	Latency Improvement: Strategies to improve the response time of the shopping assistant.


#Dataset
We recommend using the Amazon Berkeley Objects (ABO) Dataset: ABO Dataset Link. This dataset contains product data, including descriptions and images, which are crucial for building an effective shopping assistant. Useful features include:
●	Product Description: Textual details about the product.
●	Product Keywords: Important tags for product identification.
●	Product Images: To be used for image captioning and data augmentation.

#Overall Flow
1.	Introduction: Introduce the problem statement and the real-life use case for a natural language-based shopping assistant.
2.	Building the Solution: Discuss different ways to build the system, focusing on key methodologies.
3.	RAG Implementation: Briefly explain Retrieval Augmented Generation (RAG), as it has been previously covered, followed by its implementation.
4.	Agentic Flow Explanation: Provide a quick overview of the agentic flow, ensuring clarity by connecting it to previous discussions.
5.	Comparison: Conduct a detailed comparison between RAG and the agentic flow to highlight their strengths and differences.
6.	Evaluation: Use Langsmith or other tools to evaluate the performance of the models, with a separate evaluation notebook comparing RAG and agents.

#Prerequisites
●	Python: Python Guide
●	Chroma Vector DB: Chroma Vector DB Documentation - To store vectorized product data and facilitate the connection with LLM using RAG.
●	LangChain: LangChain Documentation - For building prompts and orchestrating interactions with LLMs and databases.

#Get Ready and execute below line of code in the sequence to learn
1.	Running Google Colab Notebook
○	Upload the agent_shop_talk_implementation.ipynb and rag-shoptalk-implementation.ipynb notebooks to Colab.
○	Upload the dataset we are planning to use for this project.
○	Run the rag-shoptalk-implementation.ipynb
○	Run the agent_shop_talk_implementation.ipynb
○	After this run the Evaluation notebooks
i.	ragas-intro.ipynb
ii.	llm-evals.ipynb

#Milestones
1.	Data Pipeline and Integration: Develop a robust data pipeline to ingest product data, set up a vector database, and load the vectorized product dataset for retrieval using RAG.
2.	Explore LangChain: Use the LangChain toolkit to connect with the database, ensuring effective data ingestion, transformation, and storage for insights generation.
3.	Prompt Engineering: Explore various prompt templates to enhance data retrieval through natural language queries.
4.	Understand RAG: Implement RAG to improve the natural language processing capabilities for generating product recommendations.
5.	Agentic Flow: Develop the agentic flow mechanism, compare its performance against RAG, and document the findings.
6.	Evaluation: Conduct model evaluations using Langsmith or other tools, providing a comparative analysis of RAG and agent-based models.

#Model
●	OpenAI GPT-4: This project utilizes GPT-4, a multimodal model that accepts text inputs and generates human-like recommendations. The chosen model variant is gpt-4o-mini-2024-07-18.

