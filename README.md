# Legal Assistant Platform - GenAI Powered

## Overview

This is a Generative AI-based legal assistant platform that enables attorneys to generate court-ready legal documents, suggest detailed legal arguments with citations, and interact through a contextual legal Q&A chatbot. It uses Retrieval-Augmented Generation (RAG) and integrates trusted U.S. legal databases to provide accurate and actionable legal outputs.

## Features

- Case type workflows: Civil and Criminal  
- Role-based views: Plaintiff Lawyer, Defendant Lawyer, Prosecution, Criminal Defendant  
- Auto-generation of legal documents: plaint, summons, answers, counterclaims, statement of facts, client statements  
- Upload support for evidence, identification documents, witness statements  
- Suggestion engine for legal arguments using FAISS + OpenAI  
- RAG-based legal Q&A with fallback to official legal resources  
- Citation of relevant laws and acts when applicable  
- Sidebar notes for each role  
- Local vector database to enable fast retrieval  

## Architecture and Tools Used

- OpenAI GPT-4o for LLM document generation and Q&A  
- LangChain for agent, document tools, and prompt management  
- FAISS for local semantic vector search  
- Google Custom Search API for legal.gov website access  
- Streamlit for UI development  
- Python (backend logic, file handling)  
- Prompt engineering and RAG pipeline construction  

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/LegalDoc-AI-Assistant  
   
Install dependencies:

bash
Always show details

Copy
pip install -r requirements.txt
## Configure API keys directly in the script:

OpenAI API Key

Google API Key

Google CSE ID

## streamlit run GENAi(3).ipynb
Open in browser:

http://localhost:8501

## Legal Sources Referenced
https://www.uscourts.gov/

https://www.law.cornell.edu/

https://www.uniformlaws.org/

All official U.S. state government domains (e.g., georgia.gov, texas.gov)
 
## Example Use Case
A Plaintiff Lawyer selects Civil > Plaintiff

Inputs conversation with client and optionally uploads evidence

Generates a plaint and summons using the conversation

Builds a vector DB from all uploaded materials

Uses Suggest Arguments to generate citations

Asks strategic questions via the Q&A interface

## Skills Demonstrated
Generative AI

Retrieval-Augmented Generation (RAG)

Natural Language Processing (NLP)

Legal Document Automation

LangChain Tool and Agent Integration

FAISS Semantic Indexing

Prompt Engineering

Python Application Development

Legal Tech and Compliance Systems

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
Ramani Desai
Email: rdesai7@student.gsu.edu

LinkedIn: https://www.linkedin.com/in/ramani-desai

GitHub: https://github.com/ramanidesai
