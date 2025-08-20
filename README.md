# Healthcare NLP RAG Project

A low-code Retrieval-Augmented Generation (RAG) system for medical diagnosis using the **Merck Manual** and **Mistral-7B-Instruct** model via `llama.cpp`.

## 🎯 Objective
To assist healthcare professionals by providing accurate, context-aware answers to medical queries using up-to-date knowledge from a trusted manual.

## 📁 Project Structure
- `Low_Code_NLP_RAG_Project_Notebook.ipynb`: Main notebook with RAG pipeline
- `medical_diagnosis_manual.pdf`: Source document (Merck Manual)
- `medical_db/`: Chroma vector database (generated embeddings)

## 🔧 Technologies Used
- LangChain
- Sentence Transformers (`all-MiniLM-L6-v2`)
- Llama.cpp (Mistral-7B-Instruct GGUF)
- Chroma (vector store)
- Hugging Face Hub

## 📚 Example Queries
1. What is the protocol for managing sepsis?
2. Can appendicitis be cured with medicine?
3. What causes sudden patchy hair loss?

## 🚀 How to Run
1. Clone the repo
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

3. Run the notebook in Jupyter