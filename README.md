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









<img width="596" height="623" alt="Screenshot 2026-05-19 at 6 33 46 PM" src="https://github.com/user-attachments/assets/78c7e9e3-56b0-4dd7-87d5-5fe85290bc76" />

<img width="795" height="310" alt="Screenshot 2026-05-19 at 6 46 23 PM" src="https://github.com/user-attachments/assets/4efa2355-7192-480c-b238-080b1fb885ef" />

<img width="1419" height="737" alt="Screenshot 2026-05-19 at 7 44 43 PM" src="https://github.com/user-attachments/assets/036eee2e-080c-45b2-a107-9a1c777710cf" />

<img width="1305" height="770" alt="Screenshot 2026-05-19 at 7 56 31 PM" src="https://github.com/user-attachments/assets/b4b19040-3f01-4f6e-9316-3f2b05f04275" />

<img width="1296" height="770" alt="Screenshot 2026-05-19 at 7 59 02 PM" src="https://github.com/user-attachments/assets/be00b673-1690-4cde-bb42-ae4b57878c87" />

<img width="1307" height="579" alt="Screenshot 2026-05-19 at 8 04 49 PM" src="https://github.com/user-attachments/assets/2e18dbb3-01c0-4877-82ef-ce3f8e87bb39" />

<img width="1375" height="493" alt="Screenshot 2026-05-19 at 8 16 36 PM" src="https://github.com/user-attachments/assets/4bf3bf31-759d-4317-8f72-63b1476fddea" />

<img width="1055" height="711" alt="Screenshot 2026-05-19 at 8 27 43 PM" src="https://github.com/user-attachments/assets/7c417a99-ab68-448e-a3d3-3cc3751dab88" />

<img width="1377" height="707" alt="Screenshot 2026-05-19 at 9 29 00 PM" src="https://github.com/user-attachments/assets/9f35a0a1-4a43-4663-86f5-909b0d76894d" />
