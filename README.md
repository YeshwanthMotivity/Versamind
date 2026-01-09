# <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/e526e9da-2401-4fa8-930f-d22748d9bb31" /> VersaMind - Smart Document Summarizer & Email Drafter
VersaMind is a lightweight, intelligent AI tool designed to streamline business communication by efficiently summarizing lengthy documents and drafting professional emails. Built on the Microsoft Phi-3 Mini 4K Instruct model and leveraging key NLP techniques, VersaMind simplifies document analysis and accelerates workflows.

---
### 🚀 Features

• **Multi-Format Support**: Handles documents in .pdf, .docx, and .txt formats.

• **Intelligent Summarization**: Extracts, cleans, and chunks document content to provide accurate, context-aware summaries using the Phi-3 Mini LLM.

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
Versamind-main/
├── notebooks/
│   └── VersaMind.ipynb      # Original Jupyter Notebook for experimentation
├── versamind.py             # Main executable Python script
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

### 💻 Installation & Usage

#### 1. Prerequisites
*   Python 3.10 or higher installed.
*   **GPU Recommended**: This project uses 4-bit quantization which requires a CUDA-capable GPU for optimal performance. It may not run correctly on CPU-only machines.

#### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
*Note: You may need to install PyTorch manually ensuring it matches your CUDA version if the default install fails to detect your GPU.*

#### 3. Run the Application
```bash
python versamind.py
```
This will launch a local Gradio interface (usually at `http://127.0.0.1:7860`).

---

### 🎯 Future Enhancements

• Develop a Web UI using Streamlit or Flask,React.

• Add multiple tone options for email drafts (e.g., formal, friendly).

• Implement support for multi-document summarization.

• Add a feature to save or export generated summaries and emails.


---

## 🙋‍♂️ Author

• Mentor / Manager: Mr. Venkata Ramana Sudhakar Polavarapu

• Mudimala Yeshwanth Goud

 🛠️ Passionate about AI/ML, NLP, RAG, Data Science, system programming, full-stack development, and intelligent assistant systems.

---

## 📬 Contact
For questions or collaboration, you can reach out at:

**Email 📧** : yeshwanth.mudimala@motivitylabs.com
