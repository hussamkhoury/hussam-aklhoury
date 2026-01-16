# Hussam Kh

AI Engineer | Senior Backend / Full-Stack Engineer | LLM, RAG & Agentic Systems

---

## 👋 About Me

I am an AI Engineer with a strong backend and full-stack engineering background, focused on building **production-grade AI systems** rather than demos. My work centers on **LLM-powered applications**, **Retrieval-Augmented Generation (RAG)**, and **agent-based architectures**, with a strong emphasis on clean design, scalability, and real-world usability.

I have hands-on experience designing and deploying AI systems on **Google Cloud Platform**, working across the full lifecycle: from data ingestion and document intelligence, to model integration, backend APIs, and cloud deployment.

I enjoy solving complex problems where **AI meets system design**, and I care deeply about maintainability, observability, and long-term evolution of software systems.

---

This is an impressive project, especially given the complexity of tax regulations and the "Big Four" professional standards required by Deloitte.

To showcase this on your **GitHub.io** profile, you should structure it to highlight both the **business impact** and your **technical architectural decisions**.

Here is a professionally drafted section you can use. I’ve categorized it so recruiters can quickly see your skills in Data Engineering, AI Orchestration, and Backend Development.

---

# Project: Deloitte ME Tax Pulse – AI Tax Assistant

### **Overview**
Developed the core AI-Powered Tax Assistant for **Deloitte Middle East**, designed to simplify complex tax regulations, ensure compliance, and optimize tax strategies across the GCC (Gulf Cooperation Council) region. The system serves as a sophisticated interface for users to query massive repositories of tax law, bulletins, and real-time updates.

### **My Role: Lead AI Engineer / Backend Developer**
I was responsible for the end-to-end development of the AI assistant, focusing on high-accuracy data ingestion, RAG pipeline architecture, and a hybrid agentic workflow.

---

### **🚀 Key Technical Contributions**

#### **1. Multi-Modal Data Ingestion Pipeline**
*   **Large-Scale Ingestion:** Engineered a robust pipeline to process and vectorize massive amounts of heterogeneous data, including **Word docs, PDFs, and complex Excel spreadsheets**.
*   **Real-time Data:** Integrated web-scraping via APIs to ensure the assistant remains updated with the latest tax alerts and market changes.

#### **2. Hybrid Workflow & Agentic Architecture**
*   **System Design:** Implemented a **Hybrid Workflow/Agentic System**. While the general conversation follows a structured flow for reliability, I integrated **LLM-based routing nodes** where the model autonomously decides the best path/tool to take based on user intent.
*   **Dynamic Context Switching:** Built a multi-country context engine. The assistant tracks the selected GCC country (KSA, UAE, Qatar, etc.) and can **autonomously offer to switch contexts** if it detects the user is asking about a different jurisdiction mid-conversation.

#### **3. Advanced RAG Pipeline**
*   **Orchestration:** Leveraged **Gemini Models** (Google Cloud) for advanced reasoning and response generation.
*   **Vector Search:** Utilized **MongoDB Atlas Vector Search** for semantic retrieval, ensuring that the most relevant tax clauses are fetched to ground the LLM’s responses, minimizing hallucinations.
*   **Tools Integration:** Integrated a **Web Search tool** to supplement the internal knowledge base when users ask about breaking news or external economic events.

#### **4. Backend & Infrastructure**
*   **Performance:** Developed the core service using **FastAPI**, ensuring low-latency responses for the chat interface.
*   **Cloud:** Deployed and managed within the **Google Cloud Platform (GCP)** ecosystem, adhering to enterprise-level security and scalability standards.

---

### **🛠️ Tech Stack**
*   **LLMs:** Google Gemini
*   **Frameworks:** FastAPI, LangGraph (or specialized workflow logic), Pydantic
*   **Database:** MongoDB (Atlas Vector Search)
*   **Cloud:** Google Cloud Platform (GCP)
*   **Data Processing:** Python (Pandas for Excel, PyMuPDF for PDF parsing)

---

### **📸 Gallery / Showcase**
*(Note to you: This is where you will insert the screenshots you provided. I recommend arranging them in this order:)*
1.  **The Disclaimer:** Shows the professional/legal nature of the project.
2.  **Home Screen:** Shows the country selection and "Discover tax insights" UI.
3.  **Chat Initial State:** Shows the "Select Country" starting point.
4.  **The Assistant in Action:** Use the screenshots showing the VAT rates breakdown for KSA to demonstrate how the RAG pipeline formats complex data into readable bullet points.

---

### **How to add this to your GitHub.io:**
1.  **README.md:** If you have a specific repository for this (even if the code is private, you can make a "Project Documentation" repo), paste the text above there.
2.  **Portfolio Page:** If you are using a template (like Jekyll or Hugo), create a new project entry and use the headers above.
3.  **Keywords:** Ensure you use tags like **#GenerativeAI**, **#RAG**, **#AgenticAI**, and **#EnterpriseAI**.

**Would you like me to refine the "Hybrid Workflow" part to be more technical? (e.g., explaining how you handled state management or specific prompt engineering techniques?)**
