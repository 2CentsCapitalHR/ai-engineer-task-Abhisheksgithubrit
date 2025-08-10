
🚀 Live Demo: https://ai-engineer-task-yunxxcxsyr9dnkcrxgdkwe.streamlit.app/

📌 Overview
The ADGM Corporate Agent is an AI-powered legal assistant designed to help businesses and professionals prepare and review incorporation and compliance documentation for the Abu Dhabi Global Market (ADGM) jurisdiction.
It uses Document Intelligence + RAG (Retrieval-Augmented Generation) to verify document completeness, detect compliance issues, and provide actionable suggestions.

🎯 Purpose
This project was built to:

Automate document checklist verification for ADGM processes (e.g., Company Incorporation)

Detect legal red flags and inconsistencies

Provide inline comments & legal references directly in .docx documents

Reduce manual legal review time while ensuring compliance with ADGM regulations

✨ Features
✅ Process Detection – Automatically detects the legal process (e.g., "Company Incorporation") from uploaded documents.
✅ Checklist Verification – Compares uploaded .docx files against official ADGM requirements and identifies missing documents.
✅ Red Flag Detection – Flags invalid clauses, missing jurisdiction details, ambiguous language, and non-compliance.
✅ Inline Comments – Inserts comments in the .docx at the exact location of issues, citing ADGM laws/regulations.
✅ RAG Integration – Uses ADGM official documents and templates for accurate compliance checks.
✅ Structured Output – Generates a JSON/Python report summarizing:

json
Copy
Edit
{
  "process": "Company Incorporation",
  "documents_uploaded": 4,
  "required_documents": 5,
  "missing_documents": ["Register of Members and Directors"],
  "issues_found": [...]
}
✅ Streamlit Interface – Simple, interactive UI to upload, review, and download documents.

📂 Document Types Supported
The system supports at least the following ADGM document categories:

Company Formation Documents: AoA, MoA, Board Resolutions, Shareholder Resolutions, UBO Declaration, Register of Members & Directors, etc.

Licensing Regulatory Filings
Employment & HR Contracts
Commercial Agreements
Compliance & Risk Policies

🖥 How to Run Locally
bash
Copy
Edit
# 1. Navigate to the workspace
cd workspace

# 2. Navigate to the Streamlit template folder
cd streamlit_template

# 3. Activate the virtual environment
# (Windows)
venv\Scripts\activate
# (Mac/Linux)
source venv/bin/activate

# 4. Run the Streamlit app
streamlit run app.py

📜 Data Sources & References

[ACFrOgCVWQwXFmzcQ2f3wFC3UW1X8VCzvfsvBjp87pGo1536u7jJ90Uer-m7UhLhIW82kn8TmQayXkpRUTEKbc8y-UFT9MJlMHbuIHch5gxw6xMohCKeR6N2cuLUx9pfvlyons_DxI2j6Nv30w1mSl-v6yRqGCMfqyPTs1K7-A==.pdf](https://github.com/user-attachments/files/21705016/ACFrOgCVWQwXFmzcQ2f3wFC3UW1X8VCzvfsvBjp87pGo1536u7jJ90Uer-m7UhLhIW82kn8TmQayXkpRUTEKbc8y-UFT9MJlMHbuIHch5gxw6xMohCKeR6N2cuLUx9pfvlyons_DxI2j6Nv30w1mSl-v6yRqGCMfqyPTs1K7-A.pdf)
