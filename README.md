# 🦷 SmartMolar-Dental-AI

## 🔹 Project Overview
**SmartMolar** is an AI-powered application that identifies and evaluates dental conditions from **X-ray images**. It integrates **YOLO (You Only Look Once)** for image-based detection and uses **Large Language Models (LLMs)** to deliver detailed **treatment recommendations**. The system is yet to be deployed but is planned with **Streamlit** and to be made remotely accessible via **LocalTunnel**.

## 🔹 Features
✅ Accurate **dental condition detection** using YOLO  
✅ AI-generated **treatment plans** with GPT-3.5 or LLaMA-3  
✅ **RAG-based document retrieval** for evidence-backed suggestions  
✅ Intuitive **Streamlit web interface** for easy interaction  
✅ **Remote access** enabled through LocalTunnel  

## 🔹 Tech Stack
- **Object Detection:** YOLO (Ultralytics)  
- **Language Models:** GPT-3.5, LLaMA-3 (via Groq API)  
- **Embedding Model:** BAAI/bge-small-en-v1.5 (HuggingFace)  
- **Vector Indexing:** LlamaIndex with VectorStoreIndex  
- **Web App Framework:** Streamlit  
- **Deployment Tools:** LocalTunnel (Expected) 


## **🔹 Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/KaranS2111/SmartMolar-Dental-AI
cd SmartMolar-Dental-AI
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


