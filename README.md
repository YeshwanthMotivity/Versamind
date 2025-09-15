# <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/e526e9da-2401-4fa8-930f-d22748d9bb31" /> VersaMind - Smart Document Summarizer & Email Drafter
VersaMind is a lightweight, intelligent AI tool designed to streamline business communication by efficiently summarizing lengthy documents and drafting professional emails. Built on the Microsoft Phi-3 Mini 4K Instruct model and leveraging key NLP techniques, VersaMind simplifies document analysis and accelerates workflows.

---

### 🚀 Features
• **Multi-Format Support**: Handles documents in .pdf, .docx, and .txt formats.
• **Intelligent Summarization**: Extracts, cleans, and chunks document content to provide accurate, context-aware summaries using the Phi-3 Mini LLM.
• **Professional Email Drafting**: Automatically generates concise and professional email drafts.
• **Configurable Tone**: The email drafting feature can be customized for different tones and styles.
• **Lightweight & Efficient**: Optimized for local execution, ensuring data privacy and fast performance.

---

### 🛠️ Tech Stack

|          Category        |          Tools & Libraries                  |
|  ----------------------- | ------------------------------------------- |
| **Programming Language** | `Python`                                    |
| **LLM**                  | `Microsoft Phi-3 Mini 4K Instruct`          |
| **File Parsing**         | `PyMuPDF`, `python-docx`, `standard I/O`    |
| **NLP Techniques**       | `Chunking`, `typo correction`, `formatting` |
| **Deployment**           | `Streamlined CLI`                           |

---

### 🧾 How It Works
1. **Document Input**: Upload or specify the path to a .pdf, .docx, or .txt file.
2. **Parsing & Cleaning**: The file is parsed using PyMuPDF or python-docx, and cleaned using NLP techniques (typo correction, sentence formatting).
3. **Summarization**: The cleaned content is chunked and passed to the Phi-3 model for summarization.
4. **Email Drafting**: A custom prompt generates a professional email based on the summarized content.

---

### 📂 Project Structure
 ```
VersaMind/
├── versamind_–_smart_document_summarizer_&_email_drafter.py  # Main script
├── README.md                                                 # Project documentation
 ```

---

### 💻 Run Locally

**🧰 Requirements**

• Install required libraries:

pip install -r requirements.txt  # or install manually:
pip install torch transformers pymupdf python-docx

**▶️ Execution**

Run the summarizer and email drafter:

python versamind_–_smart_document_summarizer_&_email_drafter.py
Follow the CLI prompts to input a document and generate a summary or draft email.

---

### 🎯 Future Enhancements
• Develop a Web UI using Streamlit or Flask,React.
• Add multiple tone options for email drafts (e.g., formal, friendly).
• Implement support for multi-document summarization.
• Add a feature to save or export generated summaries and emails.

---
### 📬 Contact
For questions, feedback, or contributions:

📧 yeshwanth.mudimala@motivitylabs.com

