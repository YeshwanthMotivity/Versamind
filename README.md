# Versamind

VersaMind – Smart Document Summarizer & Email Drafter
VersaMind is an intelligent, lightweight AI tool designed to summarize lengthy documents and draft professional emails efficiently. Built using Microsoft Phi-3 Mini 4K Instruct model and NLP techniques, VersaMind simplifies document analysis and accelerates business communication workflows.

🚀 Features
1. Supports PDF, DOCX, and TXT document formats.

2. Extracts, cleans, and chunks document content for accurate summarization.

3. Uses the Phi-3 Mini LLM for context-aware summarization and email drafting.

4. Generates clear, concise email drafts with adjustable tone and style.

5. Lightweight and optimized for local execution.

🛠️ Tech Stack

Category	Tools & Libraries
Programming Language	Python
LLM	Microsoft Phi-3 Mini 4K Instruct
File Parsing	PyMuPDF, python-docx, standard I/O
NLP Techniques	Chunking, typo correction, formatting
Deployment (CLI)	Streamlined through script execution

🧾 How It Works

1. Document Input: Upload or specify the path to a .pdf, .docx, or .txt file.

2. Parsing & Cleaning: The file is parsed using PyMuPDF or python-docx, and cleaned using NLP techniques (typo correction, sentence formatting).

3. Summarization: The cleaned content is chunked and passed to the Phi-3 model for summarization.

4. Email Drafting: A custom prompt generates a professional email based on the summarized content.

📂 Project Structure

VersaMind/
├── versamind_–_smart_document_summarizer_&_email_drafter.py  # Main script
├── README.md                                                  # Project documentation

💻 Run Locally

🧰 Requirements

Install required libraries:

pip install -r requirements.txt  # or install manually:

pip install torch transformers pymupdf python-docx

▶️ Execution

Run the summarizer and email drafter:

python versamind_–_smart_document_summarizer_&_email_drafter.py
Follow the CLI prompts to input a document and generate a summary or draft email.

🎯 Future Enhancements

Web UI using Streamlit or Flask

Multiple tone options for email drafts

Multi-document summarization

Save/export summaries and emails

📬 Contact
For questions, feedback, or contributions:

📧 yeshwanth.mudimala@motivitylabs.com

