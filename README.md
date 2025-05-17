# 🦷 DentalAI Diagnosis

## **🔹 Project Overview**
**DentalAI Diagnosis** is an AI-powered system that detects and analyzes dental conditions from **X-ray images**. It utilizes **YOLO (You Only Look Once)** for image detection and **LLMs (Large Language Models)** to provide comprehensive **treatment plans**. The application is deployed using **Streamlit** and made accessible via **LocalTunnel**.

## **🔹 Features**
✅ **Dental Condition Detection** using YOLO
✅ **Treatment Plan Generation** with LLMs (GPT-3.5 / LLaMA-3)
✅ **Document Retrieval (RAG)** for evidence-based recommendations
✅ **User-Friendly Web Interface** via Streamlit
✅ **Remote Accessibility** using LocalTunnel

## **🔹 Tech Stack**
- **Deep Learning Model:** YOLO (Ultralytics)
- **Large Language Models:** GPT-3.5, LLaMA-3 (Groq API)
- **Embedding Model:** HuggingFace (BAAI/bge-small-en-v1.5)
- **Document Processing:** LlamaIndex (VectorStoreIndex)
- **Web Framework:** Streamlit
- **Deployment:** LocalTunnel, Google Colab

## **🔹 Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/DentalAI-Diagnosis.git
cd DentalAI-Diagnosis
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Application**
```bash
streamlit run app.py
```

### **4️⃣ Expose the App (Optional)**
```bash
npx localtunnel --port 8501
```

## **🔹 Usage**
1️⃣ **Upload a dental X-ray scan**
2️⃣ **Model detects dental conditions**
3️⃣ **AI provides a detailed treatment plan**
4️⃣ **View results and recommendations**

## **🔹 Model Details**
- **Trained on 6 dental conditions:**
  - Prosthesis
  - Root Canal
  - Caries
  - Impaction
  - Restoration
  - Root Stump
- **Confidence Threshold:** 70%
- **Trained with YOLOv8** for precision diagnosis

## **🔹 Future Improvements**
✅ Expand the dataset for better accuracy
✅ Optimize real-time inference
✅ Integrate patient history for personalized treatment plans

## **🔹 License**
📜 This project is licensed under the **MIT License**.

🚀 **Let's revolutionize dental care with AI!**

