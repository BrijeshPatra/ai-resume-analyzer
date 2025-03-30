# AI-Powered Resume Analyzer  

AI-Powered Resume Analyzer is a tool designed to evaluate resumes like an HR professional using **Google Generative AI**. It analyzes job compatibility, highlights strengths and weaknesses, and provides actionable insights for improvement.

---

## 📋 Project Overview  

This tool helps:
- Evaluate resumes with AI-driven insights.  
- Identify skill gaps and suggest improvements.  
- Compare resumes with job descriptions for compatibility.

---

## 🔑 Features  

### 1️⃣ General Resume Analysis  
- Summarizes resume details.  
- Highlights existing skills and gaps.  
- Suggests improvements and relevant courses.  
- Provides a strengths and weaknesses evaluation.  

### 2️⃣ Resume Matching with Job Description  
- Compares resume with job requirements.  
- Provides a match score in percentage.  
- Highlights missing skills and suggests enhancements.  

---

## 🛠️ Tech Stack  

| Component | Technology |  
|-----------|------------|  
| **Frontend** | Streamlit |  
| **Backend** | Python |  
| **AI Model** | Google Generative AI (Gemini) |  
| **PDF Parsing** | pdfplumber |  
| **OCR Fallback** | pytesseract |  
| **Environment Config** | .env for API key security |  

---

## 🚀 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
```

### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up API Key  
Create a `.env` file and add:
```sh
GOOGLE_API_KEY=your_api_key_here
```

### 4️⃣ Run the Application  
```sh
streamlit run app.py
```

---

## 📊 How It Works  

1. **Resume Parsing**: Extracts text from PDFs using `pdfplumber`, with `pytesseract` as a fallback.
2. **AI Analysis**: Uses Google AI to analyze resume content and match job descriptions.
3. **Insightful Feedback**: Suggests skill improvements and provides compatibility scores.

---

## 🙌 Contributing  

Contributions are welcome! To contribute:
1. **Fork** the repository.  
2. **Create a new branch** (`feature-branch`).  
3. **Commit** your changes and push to GitHub.  
4. **Submit a pull request** with a description of your changes.  

---

**📌 Developed with ❤️ using Streamlit & Google Gemini AI**

