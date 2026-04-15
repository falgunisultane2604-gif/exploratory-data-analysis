🤖 Smart Resume Analyzer (AI-Powered)

An intelligent web application that analyzes resumes using AI and provides instant feedback, keyword insights, and ATS-based scoring to help candidates improve their chances of getting hired.

✨ Features
🎨 Modern UI/UX
Glassmorphism design with frosted cards
Blue → cyan gradient theme (#3b82f6 → #06b6d4)
Smooth animations and transitions
Fully responsive (mobile, tablet, desktop)
Dark mode support 🌙
🚀 Core Functionality
📄 Resume Upload (PDF/DOCX)
🤖 AI-based Resume Analysis
🔍 Keyword Matching with Job Description
📊 ATS Score (0–100)
🧠 Skill Detection (technical + soft skills)
💡 Improvement Suggestions
📊 Analysis Capabilities
Keyword density analysis
Skill gap identification
Experience breakdown
Education verification
Grammar & readability check
ATS optimization scoring
🛠️ Tech Stack
Technology	Purpose
Streamlit	Web app UI
Python	Backend logic
spaCy	NLP processing
PyPDF2 / docx	Resume parsing
Scikit-learn	Matching algorithms
Matplotlib	Data visualization
📦 Installation
Prerequisites
Python 3.8+
pip
Setup Steps
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer

python -m venv env
env\Scripts\activate      # Windows
source env/bin/activate   # macOS/Linux

pip install -r requirements.txt
streamlit run app.py
🚀 Usage
Upload Resume
Drag & drop PDF or DOCX file
Add Job Description
Paste job description for better matching
View Results
ATS Score
Keyword Match %
Improvement Suggestions
📋 Supported Formats
Format	Extension	Support
PDF	.pdf	✅
Word	.docx	✅
📁 Project Structure
resume-analyzer/
├── app.py
├── analyzer.py
├── utils/
├── requirements.txt
└── README.md
💡 Tips
Use clear headings (Skills, Experience, Education)
Match keywords with job description
Keep resume concise (1–2 pages)
Avoid image-based resumes
🐛 Troubleshooting

App not running?

python --version
pip install --upgrade -r requirements.txt

Resume not parsing?

Ensure it is a text-based PDF
Avoid scanned images

Low ATS score?

Add relevant keywords
Use standard formatting
🔮 Future Enhancements
LinkedIn profile analysis
AI resume rewriting
Cover letter generator
Multi-language support
Interview question suggestions
🔒 Privacy
Files processed locally
No data stored or shared
Secure and private
🤝 Contributing
Fork the repository
Create a feature branch
Commit changes
Push and create a Pull Request
