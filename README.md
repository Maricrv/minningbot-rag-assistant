# MinningBots – RAG - Document Assistant

MinningBots is an AI-powered assistant designed to help organizations securely access and query their internal documents using Retrieval-Augmented Generation (RAG).
The main goal of the product is to reduce the time employees spend searching for information while keeping sensitive company data inside a controlled and private environment.

*Simplify and enhance access to your information with MinningBots – Fast Answers, Clear Information.*

---

## About the project

Many companies store important information in PDFs, manuals, procedures, and internal documents. Over time, this information becomes difficult to access quickly, and employees often rely on manual searches or asking colleagues for help.
MinningBots was created to address this problem by allowing users to upload documents and ask questions in natural language. The system retrieves relevant information from the uploaded files and provides clear answers, including the exact document and page where the information was found.
The solution was initially designed for Spanish-speaking companies in Peru and Chile, but the concept and architecture can be applied to organizations in any region.

---

## What the system offers

MinningBots provides a set of features focused on usability, security, and clarity:

- Secure document upload and storage  
- Natural language questions based on internal documents  
- Accurate answers supported by document references (file and page)  
- A general chatbot for non-document-related questions  
- User authentication and password management  
- An admin area for managing users and access  
- Deployment in on-premise or private server environments  
- Support for multilingual usage  

---

## How it works (high level)

1. Users upload internal documents such as manuals or procedures.  
2. Documents are stored securely within the organization’s environment.  
3. Text is processed, split into chunks, and indexed using embeddings.  
4. When a user asks a question, the system retrieves the most relevant document fragments.  
5. The AI generates an answer grounded in those documents and shows the source for verification.

This approach ensures transparency and trust in the answers provided.

---

## Main user flows

- Login with individual credentials  
- Upload documents  
- View and manage uploaded files  
- Ask questions about document content  
- Delete outdated documents  
- Use a general chatbot  
- Admin management of users and areas  

These flows are demonstrated in the product presentation and demo videos.

---

## Business value

From a business perspective, MinningBots helps organizations by:

- Saving time spent searching for information  
- Improving internal knowledge access  
- Making AI accessible to non-technical users  
- Increasing confidence in answers through document references  
- Protecting sensitive data by avoiding public cloud exposure  

---

## My contribution to the project

I did not develop the backend or write the system code.  
The technical implementation was handled by a teammate.

My contribution focused mainly on the product, functional, and communication aspects of the project. I worked on:

- Participating in product discussions and planning sessions  
- Defining the problem, product vision, and value proposition  
- Contributing to the definition and refinement of the main user flows (login, upload, query, admin, etc.)  
- Preparing the product presentation in Spanish and English  
- Creating and recording demo videos  
- Performing functional testing and reporting issues  
- Writing functional documentation and supporting early requirements  
- Coordinating with the developer to align features with business needs
- Creating and customizing the product landing page  

This repository reflects my contribution to the product definition, documentation, testing, and communication of an AI-based RAG solution.

---

## Product landing page

As part of the product communication and early outreach, I also created and customized the official MinningBots landing page:

🔗 https://minningbots.com/

The site was built using a professional template and adapted with product messaging, structure, and content to clearly explain the solution, its benefits, deployment options, and pricing plans.  
It served as the main customer-facing page for demos and initial conversations with potential clients.

---

## Technology overview

The system prototype includes:

- Web-based user interface  
- Python-based backend services  
- PostgreSQL for metadata storage  
- Qdrant as a vector database  
- Large Language Model and embeddings (configurable)  
- Designed for on-premise or private cloud deployment  

My role focused on the functional and product aspects rather than technical implementation.

---

## Documentation

This repository includes supporting documentation related to the project, such as product presentations, demo materials, and functional notes.

Some documentation is being organized in the `/docs` folder.

---

## Credits

- System development: teammate  
- Product definition, documentation, testing, demos, and communication: Mariela Ramos
