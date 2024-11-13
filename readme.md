# Advanced PDF-Integrated Chatbot with Memory

This project is an advanced chatbot designed to answer questions related to PDF data, with the ability to retain contextual memory for an enhanced user experience.

## Contents

### Code Files
- **`.env.example`**  
  Rename to `.env` and add your API keys here.

- **`part1_pdf_extraction_&_retriever.ipynb`**  
  Converts PDFs to vector store format. If you only want to use the chatbot with an existing PDF vector store, skip to Part 2.

- **`part2_ui_of_chatbot.ipynb`**  
  Contains the code for the RAG (Retrieval-Augmented Generation) chain and the user interface.

### Test Resources
- **`test_pdf_&_retriever/Alignminds-AI-Machine-Test.pdf`**  
  Sample PDF document for testing purposes.

- **`vectorstore.pkl`**  
  Default vector store containing embeddings for `Alignminds-AI-Machine-Test.pdf`.

### Documentation & Dependencies
- **`readme.md`**  
  Documentation for this project.

- **`requirements.txt`**  
  List of dependencies necessary to run the project.

## Version
- **Python**: 3.9.11

---

## Installation

To set up and run the chatbot, follow these steps:

1. **Create a new environment**  
   ```bash
   python -m venv rag_env
2. **rag_env\Scripts\activate**
    ```bash
   rag_env\Scripts\activate
3. **Install required packages**
    ```bash
    pip install -r requirements.txt
4. **Run the application**
    - Using an existing PDF vector store:
     Simply run part2_ui_of_chatbot.ipynb to launch the chatbot interface.
    - Using a new PDF:
     Run part1_pdf_extraction_&_retriever.ipynb to convert the new PDF to a vector store (update the PDF path as needed). Then, run part2_ui_of_chatbot.ipynb to launch the chatbot.

![Chatbot Sample Output]('sample_output//pic1.png')





