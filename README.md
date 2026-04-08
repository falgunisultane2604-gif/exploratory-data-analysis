🤖 Smart Resume Analyzer (AI-Powered)

An intelligent web app that analyzes resumes using AI and provides instant feedback, keyword insights, and job-match scoring to help candidates improve their chances of getting hired.

✨ Features
🎨 Modern UI/UX
Glassmorphism Design: Elegant frosted glass cards with blur effects
Gradient Themes: Blue → cyan gradient (#3b82f6 → #06b6d4)
Smooth Animations: Fade + slide transitions (0.5s ease-in-out)
Interactive Components: Hover states, progress bars, dynamic charts
Fully Responsive: Optimized for mobile, tablet, and desktop
Dark Mode Support 🌙
🚀 Core Functionality
Resume Upload: Upload PDF or DOCX files
AI Resume Analysis: Extract and evaluate resume content
Keyword Matching: Compare resume with job description
ATS Score: Get Applicant Tracking System compatibility score
Skill Detection: Identify technical & soft skills
Improvement Suggestions: Actionable tips to improve resume
📊 Analysis Capabilities
Keyword Density Analysis
Skill Gap Identification
Experience Breakdown
Education Verification
Grammar & Readability Check
ATS Optimization Score (0–100)
🛠️ Tech Stack
Technology	Purpose
Streamlit	Web app interface
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
env\Scripts\activate   # Windows
source env/bin/activate  # macOS/Linux
pip install -r requirements.txt
streamlit run app.py
🚀 Usage
Step 1: Upload Resume
Drag & drop your resume (PDF/DOCX)
Step 2: Add Job Description
Paste job description for better analysis
Step 3: View Results
ATS Score
Keyword Match %
Suggestions
📋 Supported Formats
Format	Extension	Support
PDF	.pdf	✅
Word	.docx	✅
🎨 Color System
Primary
Blue: #3b82f6
Cyan: #06b6d4
Neutral
Background: #0f172a
Card: #1e293b
Text: #e2e8f0
Status Colors
Success: #22c55e
Warning: #facc15
Error: #ef4444
📐 Design System
Typography
Font: Inter / Poppins
Headings: Bold (600–800)
Body: Regular (400)
Spacing
8px grid system (8, 16, 24, 32px)
Components
Rounded cards (16px radius)
Soft shadows
Gradient buttons
🐛 Troubleshooting
App not running
python --version
pip install --upgrade -r requirements.txt
Resume not parsing
Ensure file is not scanned image
Use text-based PDF
Low ATS score
Add more keywords from job description
Use standard section headings
📁 Project Structure
resume-analyzer/
├── app.py
├── analyzer.py
├── utils/
├── requirements.txt
└── README.md
🤝 Contributing
Fork repo
Create branch (feature/new-feature)
Commit changes
Push & create PR
💡 Tips
Use clear headings (Skills, Experience, Education)
Avoid graphics-heavy resumes
Match keywords with job description
Keep resume 1–2 pages max
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
