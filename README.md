# Hi, I'm Padmakshi Bhonagiri 👋

**Graduate Software Developer | Generative AI | Python | Java**

I build practical AI solutions for real business problems — LLM-powered tools, retrieval-augmented generation (RAG), and data-driven analytics applications.

- 🎓 M.S. Information Systems, Saint Louis University
- 🎓 B.E. Electronics and Communication Engineering, Jawaharlal Nehru Technological University, Hyderabad
- 🧠 Focus: LLM API integration, prompt engineering, RAG, embeddings, vector search
- 💻 Languages: Python, Java, SQL
- 🛠️ Frameworks: LangChain, Streamlit, Pandas, PyPDF
- 🗄️ Databases: MySQL, ChromaDB

## Featured Projects

### 1. AI Resume Analyzer and Job Match Assistant
Python, Streamlit, LLM API, MySQL, JSON

Upload a resume (PDF / DOCX), get a structured skills profile as JSON, compare it against a job description for matched / missing skills, and get role-specific interview questions from the gaps. Includes JSON validation with automatic retry, and MySQL storage to compare resume versions over time.

→ [Padmakshi15/ai-resume-analyzer](https://github.com/Padmakshi15/ai-resume-analyzer)

### 2. Document Q&A Assistant using RAG
Python, LangChain, Embeddings, ChromaDB, LLM API, Streamlit

Ask questions about your uploaded PDF and text documents and get grounded answers with the source page for every answer. Ingestion: text extraction, chunking with overlap, embeddings, ChromaDB vector store. Answers only from retrieved context, with a clear fallback when no supporting text is found.

→ [Padmakshi15/document-qa-rag-assistant](https://github.com/Padmakshi15/document-qa-rag-assistant)

### 3. CareerWise: Employability Analytics Application
Java, MySQL, Dashboards, Data Analysis — Graduate Capstone

Helps universities track student career readiness and guide students toward employer expectations. Career assessment modules, individual progress dashboards, and skill-gap analysis mapping student competencies against job-posting requirements.

→ [Padmakshi15/careerwise-employability-analytics](https://github.com/Padmakshi15/careerwise-employability-analytics) (Java implementation)
→ [Padmakshi15/Career-Wise](https://github.com/Padmakshi15/Career-Wise) (original Python analytics dashboard)

## How to explore

Each repo has a `README.md` with how to run it, and a `LEARN.md` that walks through the code file by file — start there if you want to learn how it works.

- Run the Resume Analyzer: `streamlit run app.py`
- Run the RAG Assistant: `streamlit run app.py`, then `python eval.py`
- Run CareerWise (Java): `./run.sh` — then open `output/dashboard.html`, or `./run.sh serve`

## Portfolio

A Hogwarts-themed portfolio showcasing these projects is in progress — castle, candles, and all — and will be linked here once it is live.

---
*Built with Python, Java, and a lot of curiosity about how AI can help people get hired.*
