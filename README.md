#Resume-parser-chatgpt
AI-based Resume Parser using Python and ChatGPT API
📄 Resume Parser using ChatGPT
🚀 Project Overview
This project is an AI-powered Resume Parser developed using Python and the OpenAI API.
The system extracts structured information from unstructured resume PDFs such as:
    👤 Name
    📧 Email Address
    📱 Phone Number
    🎓 Education
    💼 Work Experience
    🛠 Skills
The project was developed in Google Colab and focuses on automating resume screening using Natural Language Processing (NLP) and AI.
🎯 Objective
The main objective of this project is to:
     Automate resume data extraction
     Convert unstructured resume text into structured format
     Reduce manual effort in recruitment process
     Demonstrate practical implementation of AI in HR technology
🛠 Technologies Used
     Python
     OpenAI API
     Natural Language Processing (NLP)
     Pandas
     NumPy
     PDFPlumber (for PDF text extraction)
     Google Colab
🧠 System Architecture
     Upload Resume (PDF)
     Extract text from PDF
     Preprocess text
     Send text to ChatGPT API
     Extract structured data
     Display parsed output in structured format
📂 Project Structure   
  resume-parser-chatgpt/
│
├── Resume_Parser.ipynb
├── requirements.txt
├── sample_resume.pdf
└── README.md
▶️ How to Run the Project
1. Clone the repository:
     git clone https://github.com/your-username/resume-parser-chatgpt.git
2. Install required libraries:
   pip install -r requirements.txt
3.Open the notebook:
   jupyter notebook Resume_Parser.ipynb
4.Run all cells to execute the parser
📊 Sample Output
The system extracts and displays:
Name: John Doe
Email: johndoe@email.com
Phone: +91-XXXXXXXXXX
Skills: Python, Machine Learning, SQL
Education: B.Tech in Computer Science
Experience: 2 Years
💡 Key Features
   ✔ AI-powered resume analysis
   ✔ Extracts multiple resume fields
   ✔ Works with PDF resumes
   ✔ Structured JSON-like output
   ✔ Easy to integrate into HR systems
📈 Future Enhancements
    Build a Web Interface using Streamlit
    Add Resume Ranking System
    Deploy as a Web Application
    Support multiple file formats (DOCX, TXT)
    Integrate with job portals

