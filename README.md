# 📚 Document Chat App - Chat with Your Documents Effortlessly 💬

Welcome to the **Document Chat App**, an AI-powered chatbot that lets you seamlessly chat with your uploaded documents. Leverage state-of-the-art Natural Language Processing (NLP) to extract insights, ask questions, and get accurate answers directly from your documents.

---

## 🚀 Key Features

✅ **CSV Document Upload:** Effortlessly upload one or more CSV files and turn them into a knowledge base.
✅ **Context-Aware Conversations:** The chatbot retains context, ensuring consistent and meaningful interactions.
✅ **Instant Document Retrieval:** Uses FAISS (Facebook AI Similarity Search) for fast, scalable document storage and retrieval.
✅ **Answer Relevancy Check:** Calculate the answer's relevancy with source documents using similarity scores.
✅ **Interactive UI:** A clean, user-friendly interface with a visually appealing chat design.

---

## 🌐 Tech Stack

* **Frontend:** Streamlit (for an intuitive and responsive UI).
* **NLP Backend:** LangChain (document processing, conversation management).
* **Vector Storage:** FAISS (scalable and efficient document vector storage).
* **LLM:** Ollama LLM (for accurate, context-aware answers).
* **Embeddings:** Hugging Face Embeddings (for document vectorization).
* **Relevancy Calculation:** SentenceTransformers (for answer relevancy scoring).

---

## 📥 Installation

1. **Clone this repository:**

   ```bash
   git clone <repository-link>
   cd document-chat-app
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**

   ```bash
   streamlit run app.py
   ```

---

## ⚡ How to Use

1. **Upload Documents:** Use the sidebar to upload one or more CSV files.
2. **Process Documents:** Click "Process CSVs" to ingest the documents into the vector database.
3. **Start Chatting:** Ask questions about the documents, and the chatbot will provide direct answers.
4. **Show/Hide Source Docs:** Toggle visibility of source documents for each answer.
5. **Calculate Relevancy:** Check the relevancy score of the answer with the source context.

---

## 📌 Example Usage

1. **Upload CSV:** A file containing product FAQs.
2. **Ask:** "What is the return policy?"
3. **Get Answer:** The chatbot retrieves the answer directly from the document.

---

## 📷 Screenshots

*(Include UI screenshots here for a better understanding)*

---

## 💡 How It Works

1. Uploaded CSV documents are read and split into text chunks using LangChain.
2. These chunks are vectorized using Hugging Face Embeddings.
3. The vectors are stored in a FAISS database for fast retrieval.
4. The chatbot (powered by Ollama LLM) uses these vectors to provide context-aware answers.
5. The answer relevancy is calculated using SentenceTransformers.

---

## 🚀 Future Improvements

* Add support for more document formats (PDF, TXT, DOCX).
* Enhanced UI with modern design elements.
* Multi-user support with personalized chat history.
* Improved answer summarization for better clarity.

---

## 📄 License

This project is licensed under the MIT License.
