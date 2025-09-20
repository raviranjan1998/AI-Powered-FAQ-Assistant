# AI-Powered FAQ Assistant

A conversational chatbot that answers questions from CSV or Excel FAQ files. It uses **LangChain** to build the Q&A chain, **FAISS** for fast similarity search, and **Gradio** for a user-friendly web interface. Users can upload FAQ files, and the bot retrieves relevant answers using embeddings in a clear format.

---

## Features

- **Upload CSV or Excel** files containing question-answer pairs  
- **Semantic search** on FAQs using embeddings  
- **Human-readable answers** with bullet points if multiple points exist  
- **Interactive web interface** powered by Gradio  

---
| Question                     | Answer                                                |
| ---------------------------- | ----------------------------------------------------- |
| What are your working hours? | Our working hours are 9 AM to 6 PM, Monday to Friday. |
| How can I reset my password? | Use the "Forgot Password" option on the login page.   |
| What is the refund policy?   | Refunds are available within 30 days with a receipt.  |
