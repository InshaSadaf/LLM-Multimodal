# VisionaryX - A Multi-Modal LLM

## 🚀 Introduction
**VisionaryX** is an advanced AI-powered multi-modal chatbot that integrates text generation, image-based queries, text-to-image generation, and PDF document interaction. It aims to simplify AI interactions by offering a seamless and intuitive platform.

---

## 🎯 Problem Statement
### ❌ Challenges with Existing AI Tools:
- **Fragmentation**: Users rely on multiple AI platforms for different tasks, leading to inefficiency.
- **Limited Multitasking**: Handling text, images, and documents separately creates workflow disruptions.
- **Time-Consuming**: Switching between applications slows down productivity.

### ✅ VisionaryX - The All-in-One AI Assistant
VisionaryX bridges these gaps by providing a **unified AI platform** that integrates:
- **Text Generation**
- **Image-Based Queries**
- **Text-to-Image Generation**
- **PDF Interaction & Q&A**

---

## 🔥 Features
### 📌 **Text Generation**
✔️ Context-aware AI-powered responses using **Google Gemini API**

### 📌 **Image-Based Queries**
✔️ Upload an image and get relevant answers powered by **Hugging Face APIs**

### 📌 **Text-to-Image Generation**
✔️ Convert text prompts into **high-quality AI-generated images**

### 📌 **PDF Interaction & Q&A**
✔️ Upload PDFs and interact via **contextual Q&A**
✔️ Extract and analyze information with **PyPDF2 + FAISS**

### 📌 **Secure User Authentication**
✔️ Login system to ensure data privacy *(Default: Username: admin | Password: admin)*

### 📌 **User-Friendly Interface**
✔️ **Built with Streamlit** for an intuitive and seamless experience

---

## 🛠️ Tech Stack
### ✅ **Backend Technologies**
- **Google Gemini API** *(gemini-1.5-flash)*
- **Hugging Face API** *(Inference Client for Text-to-Image)*
- **PyPDF2** *(Extract and process PDFs)*

### ✅ **Frontend Framework**
- **Streamlit** *(For interactive UI and real-time updates)*

### ✅ **Embedding & Vector Store**
- **Google Generative AI Embeddings** *(for PDF similarity search)*
- **FAISS (Facebook AI Similarity Search)** *(efficient document retrieval)*

### ✅ **Libraries & Utilities**
- **LangChain** *(for text chunking & Q&A chain)*
- **Pillow (PIL)** *(for image processing)*
- **dotenv** *(for secure API key storage)*

---

## 🏗️ System Architecture
```
1️⃣ User Inputs: Text / Image / PDF
2️⃣ Processing via LLM Models & APIs
3️⃣ Outputs: AI-Generated Text, Insights, Images, or Document Q&A
```
### 📌 High-Level Workflow
1. **User enters a text prompt / uploads an image / uploads a PDF**
2. **AI model processes the request using appropriate APIs**
3. **Displays response based on text, image, or document context**

---

## 📊 Comparative Analysis
| Feature                  | VisionaryX | ChatGPT | Google Lens | DALL·E 2 | Adobe AI |
|--------------------------|------------|--------|-------------|----------|---------|
| **Text Generation**      | ✅ Advanced | ✅ Basic | ❌ | ❌ | ❌ |
| **Image-Based Queries**  | ✅ Supported | ✅ | ✅ Limited | ❌ | ❌ |
| **Text-to-Image**        | ✅ High-Quality | ✅ | ❌ | ✅ | ❌ |
| **PDF Q&A**              | ✅ Contextual | ✅ | ❌ | ❌ | ✅ Limited |
| **Unified AI Platform**  | ✅ Fully Integrated | ❌ | ❌ | ❌ | ❌ |

---

## 📌 Demo
### 🎥 https://multimodalchatbot.streamlit.app/

- **Response Time:** ⚡ 5-30 seconds (depends on query complexity)
- **Processing Time:** ⚡ 2-120 seconds (based on input type)

---

## 🔮 Future Scope
🔹 **Voice Interaction** - Adding speech-to-text & text-to-speech
🔹 **Expanded Document Support** - Support for Word, Excel, PowerPoint
🔹 **Memory Feature** - Personalization based on past user interactions
🔹 **Session History Tracking** - Save & revisit past queries

---

## 🛠️ Installation & Setup
```sh
# Clone the repository
git clone https://github.com/InshaSadaf/-LLM-Multimodal.git
cd -LLM-Multimodal

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

---

## 🤝 Contributing
We welcome contributions! If you’d like to improve **VisionaryX**, follow these steps:
1. Fork the repository
2. Create a new branch (`feature-xyz`)
3. Commit your changes
4. Open a pull request

---

## 🏆 Credits
Developed by **Insha Sadaf** & Team 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

---

**📌 [GitHub Repository](https://github.com/InshaSadaf/-LLM-Multimodal)**

