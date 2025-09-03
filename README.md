# Metal OCR Chassis Detector

An AI-powered **metal OCR detector** that extracts **chassis/serial numbers** from images where the numbers are **punched on metal surfaces**.  
Built with **Streamlit** and **Google Gemini AI**, this tool helps in automating inspection processes for manufacturers, mechanics, and dealerships.

---

## 🚀 Features
- 📷 Upload or capture an image of a metal chassis number.
- 🔍 Uses **Gemini AI** for precise OCR with lookalike character distinction (`0≠O`, `1≠I`, etc.).
- 🎨 Beautiful **Streamlit UI** with a modern theme.
- ⚡ Real-time chassis number detection.
- 🌐 Web app ready – can be deployed on **Streamlit Cloud** or similar platforms.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Google Gemini AI](https://ai.google.dev/)
- [dotenv](https://pypi.org/project/python-dotenv/)


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/metal-ocr-chassis-detector.git
cd metal-ocr-chassis-detector
```

### 2️⃣ Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Set up API key
  **🔑 Setting Up Google Gemini API Key**
      - Go to Google AI Studio: https://aistudio.google.com
      - Sign in with your Google Account.
      - Click Get API Key from the sidebar.
      - Create a new API key and copy it.

### 5️⃣ Add API Key
**Create a .env file in the project root and add your keys:**
```bash
# GOOGLE API KEY
GOOGLE_API_KEY=your_api_key_here
```

### 6️⃣ Run the app
```bash
streamlit run Youtube_transcript_project.py
```
---

## 📸 Demo Screenshot
![App Screenshot](assets/screenshot.png)





