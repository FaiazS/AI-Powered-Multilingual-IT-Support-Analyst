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

## 🧠 How It Works

```mermaid
flowchart TD
    A[User Multilingual IT Query] --> B[LangChain Prompt Template]
    B --> C[LLaMA 3.3 via Groq (70B)]
    C --> D[Structured JSON Output (Pydantic)]
    D --> E[Translated Issue + Category + Resolution]
    E --> F[Final DataFrame Report]
