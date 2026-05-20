In this real-time project, we are building a smart incident assistant that enhances urban safety through Retrieval-Augmented Generation (RAG), leveraging Microsoft Azure AI technologies. This intelligent system analyzes and responds to incidents in urban environments by processing both structured data (like incident reports) and unstructured data (such as images of road damage, fires, and flooding). 

Using advanced AI models, the assistant generates contextually accurate answers, making it an invaluable tool for municipal control centers, emergency response teams, and infrastructure maintenance units.

The project utilizes various Azure AI services—including Azure OpenAI, Azure Document Intelligence, Azure AI Vision, and Azure AI Search—to perform tasks such as text extraction from PDFs, image captioning, and semantic document search.

The result is an AI-driven assistant capable of answering complex queries such as:

"What incidents were reported in the west zone?"

"Show me all fire-related incidents from May, including photos."

"What actions were taken for road damage shown in image X?"

By combining RAG with hybrid search capabilities, the assistant ensures that responses are grounded in real-time, domain-specific data, providing actionable insights for critical urban safety decisions.

In this project, we completed the following main steps:

Created Azure AI Foundry| Azure OpenAI resource: Set up the necessary Azure AI Foundry| Azure OpenAI resource to access and manage AI models securely on the cloud.

Deploy Base Models: Deployed foundational AI models that serve as the starting point for further customizations and applications.

Deploy GPT-4o Base Model: Specifically deployed the powerful GPT-4o base model, enabling advanced natural language understanding and generation capabilities.

Deploy Text-Embedding-3-small Model: Deployed the Text-Embedding-3-small model to generate meaningful vector representations of text for semantic search and similarity tasks.

Preparing Environment in Google Colab: Configured and set up the Google Colab environment to run the application development and testing interactively.

Developing the RAG Application: Built the Retrieval-Augmented Generation (RAG) application that combines external data retrieval with generative AI for more accurate responses.

Integrating and Testing the Application: Connected all components and conducted thorough testing to ensure the RAG application functions as intended.
