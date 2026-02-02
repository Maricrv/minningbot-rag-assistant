# MinningBots – Internal Document Assistant (RAG)

MinningBots is an AI-assisted solution designed to help organizations access and query their internal documents in a secure and controlled way, reducing the operational overhead caused by manual searches and repeated questions.

The idea for this product originated from operational needs identified in industrial environments, where teams rely heavily on manuals, procedures, and technical documentation to perform their work.

## Operational problem
In many organizations, critical knowledge is stored in PDFs, manuals, and internal documents that are difficult to search efficiently.
This becomes especially challenging in environments with:

- High staff rotation
- Temporary or project-based teams
- Complex procedures that must be followed correctly
- Heavy reliance on emails, calls, and ad-hoc support

These conditions often lead to a high volume of repetitive questions, incidents, and operational delays.

## Solution overview
MinningBots allows users to upload internal documents and ask questions in natural language. The system retrieves relevant information from the documents and provides answers together with the exact source (document and page), supporting transparency and trust.

The solution was initially conceived for Spanish-speaking organizations in Peru and Chile, but the approach is applicable to many operational contexts.

## My role
I joined this project as a collaborator focused on the **product, functional, and operational aspects**, not on the technical
implementation.

My contribution included:

- Contributing to problem definition and use-case discussions
- Translating operational needs into functional user flows
- Validating system behavior against real operational scenarios
- Performing functional testing and reporting issues
- Preparing product presentations and demo materials
- Creating and recording demo videos
- Writing functional documentation and early requirements
- Coordinating with the developer to align features with business needs
- Designing and customizing the product landing page

I did not develop the backend or write the system code. The technical implementation was handled by a teammate.

---

## Project materials (quick access)

This repository focuses on product definition, functional design, and validation of an AI-assisted operational solution.

- **Product vision and value proposition**  
  [docs/product-vision.md](docs/product-vision.md)

- **Operational context and use cases**  
  [docs/project-context.md](docs/project-context.md)

- **Demo scripts and communication materials**  
  [docs/demos-and-communication.md](docs/demos-and-communication.md)

- **Functional testing and evaluation notes**  
  [docs/testing-and-evaluation.md](docs/testing-and-evaluation.md)
---

## Why this project matters to me
This project strongly resonated with my prior experience in large-scale operational environments, where staff rotation and
process complexity generate a constant flow of questions and incidents.

An internal document assistant like MinningBots can significantly reduce operational friction by providing consistent, self-service access to procedural knowledge, especially for teams that perform critical work for limited periods of time.

## Technical overview (supporting layer)
- Web-based user interface
- Python-based backend services
- PostgreSQL for metadata storage
- Vector database for document retrieval
- Large Language Model and embeddings (configurable)
- Designed for on-premise or private deployment

Technology choices support the operational goal rather than drive it.

## Project status
This repository represents a portfolio and product-definition prototype. It focuses on functional design, validation, and communication rather than production readiness.

## Product landing page
🔗 https://minningbots.com/

The landing page was created to communicate the solution, its value, deployment options, and pricing during early outreach and demos.

## Demo

A short demo video showing the solution in use, focused on the operational flow rather than technical details.

Demo video:
[Watch demo](demo/minningbots-demo-en.mp4)
