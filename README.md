# GenAI RAG Business Report Summarizer
An end-to-end Generative AI project that uses Retrieval-Augmented Generation (RAG) to create executive and analytical summaries from business reports.

## Project Overview

Long business reports often contain large amounts of information, making it difficult for decision-makers to identify important findings quickly. This project explores how Generative AI can help simplify report analysis and present key information in a structured format.

The project uses the Infosys ESG Report 2024–25 as its case study.

## Objectives

- Extract and clean text from PDF business reports.
- Divide text into smaller, manageable chunks.
- Generate embeddings and retrieve relevant information.
- Produce an executive summary for business leaders.
- Prepare a data-backed analytical summary for analysts.
- Provide a simple interface using Streamlit.

## Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **PDF Processing:** PyPDF
- **Embeddings:** Sentence Transformers (`all-MiniLM-L6-v2`)
- **Retrieval:** Scikit-learn cosine similarity
- **Text Generation:** FLAN-T5
- **Interface:** Streamlit

## Project Workflow

1. Upload a business report in PDF format.
2. Extract and clean the report text.
3. Split the text into overlapping chunks.
4. Generate embeddings for the text chunks.
5. Retrieve relevant content using similarity search.
6. Generate executive and analytical summaries.
7. Display the results through a Streamlit interface.

## Project Files

| File | Description |
|---|---|
| `app.py` | Streamlit user interface |
| `GenAI_RAG_Business_Report.ipynb` | Jupyter Notebook containing the project workflow |
| `executive_summary.txt` | Executive-level summary |
| `analytical_summary.txt` | Data-backed analytical summary |
| `GenAI_RAG_Project_Report.docx` | Project methodology, results, and analysis |

## Dataset

**Infosys ESG Report 2024–25**

Source: [Official Infosys ESG Report](https://www.infosys.com/about/esg/reports/2024-25.html)

## Key Learning Outcomes

- Understanding the fundamentals of Retrieval-Augmented Generation.
- Working with text embeddings and semantic similarity.
- Applying transformer-based text generation.
- Building a basic Generative AI application using Streamlit.
- Converting long-form business information into concise summaries.

## Limitations

The quality of generated summaries depends on text extraction, retrieval relevance, and the language model. Tables, figures, and numerical details may require manual verification against the original report.

## Author

Developed as part of a Generative AI project assignment.
