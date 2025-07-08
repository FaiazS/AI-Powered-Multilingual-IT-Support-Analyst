# 🌐 AI-Powered Multilingual IT Support Analyst 🤖💻

A LangChain + Groq-powered AI system that resolves IT support queries across multiple languages — translating issues, detecting the language, categorizing them, and responding with resolutions both in the original and English language.

> ✨ Built with 🔥 LLaMA 3.3 (70B) running on Groq for ultra-fast inference  
> 🛠️ Structured responses using `Pydantic` and `JsonOutputParser`  
> 🗣️ Supports real-world IT queries in multiple languages  
> 📊 Outputs clean structured data in a Pandas DataFrame

---

## 📸 Demo Output

| Original Query | Language | Category | Resolution |
|----------------|----------|----------|------------|
| Não consigo sincronizar meus contatos... | Portuguese | Contact Sync | Verifique se o seu telefone... |
| Ho problemi a stampare i documenti... | Italian | Printing | Controlla la connessione... |
| プリンターのトナーを交換しました... | Japanese | Printer Issue | トナー交換後、プリンターのヘッドを... |

---
### 🛠 Tech Stack

Layer	Tools / Frameworks

💬 LLM	LLaMA 3.3 70B via Groq

🧠 Framework	LangChain, PromptTemplate, Output Parsers

📦 Structure	Pydantic, JSON, Pandas

🔐 Security	Google Colab userdata for API keys

📊 Output	Tabular Pandas DataFrame

---

### 🚀 Features

✅ Handles multilingual IT issues.

✅ Auto-translates issue and resolution.

✅ Categorizes the issue (e.g., “Printer”, “Login Issue”).

✅ Dual-language support (native + English).

✅ Clean, structured JSON outputs (ideal for APIs).

✅ Batch processing of multiple IT tickets.

---
### 📈 Use Cases

  - Enterprise IT Helpdesk Automation.

  - B2B SaaS Support Chatbots.

  - Global Multilingual Customer Support.

  - Internal Ticket Resolution Engines.
---

## 🧠 How It Works

```mermaid
%%{init: {'theme': 'dark'}}%%
flowchart TD
    A[User Multilingual IT Query] --> B[LangChain Prompt Template]
    B --> C[LLaMA-3.3-via-Groq-70B]
    C --> D[Structured JSON Output via Pydantic]
    D --> E[Translated Message + Category + Resolution]
    E --> F[Final DataFrame Display]
