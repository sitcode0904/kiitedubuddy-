KIIT EduBuddy
AI-Powered Academic Assistant for KIIT Students and Educators

EduBuddy is a smart academic assistant designed to streamline access to categorized, insightful, and exam-oriented content using AI and NLP. Built with students in mind, it enables intelligent retrieval of previous year questions, conceptual and application-based queries, and semester-specific insights. For educators, it offers trend analysis tools to simplify question paper design.

Features:
AI-based Query Resolution (GPT-powered)
Downloadable Results (.txt, .pdf, .docx)
Chat History & Favorites
Voice-to-Text Response Reader
Frequent Topic Identification
Real-time Analytics Dashboard
Dark Mode Toggle
Secure Authentication & Logout
Quick-Access Buttons for FAQs

Project Goals:
Simplify access to exam-relevant resources
Personalize learning using intelligent data analysis
Support faculty in exam paper formulation
Promote AI integration in academic workflows

Architecture Overview:
Frontend: Flask-based responsive UI with support for bookmarks, dark mode, and voice interaction
Backend: Python APIs integrating a fine-tuned GPT-based LLM (TinyLlama)
Data Pipeline: Extracted and preprocessed past exam questions using OCR, Pandas, and TF-IDF
Dashboard: Analytics powered by Matplotlib, Seaborn, and interactive filters

Tech Stack:
Component	Tools/Frameworks
Frontend	Flask, HTML, CSS, JS
Backend	Python, Flask, GPT-based LLMs (TinyLlama, Deepseek, etc.)
AI & NLP	Transformers, Scikit-learn, TF-IDF, OCR
Visualization	Matplotlib, Seaborn, WordCloud
Storage	SQLite
IDEs	VS Code, Google Colab, Jupyter
Hosting (Future)	Cloud Platforms (TBD)
Installation & Usage
Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-repo/kiit-edubuddy.git
cd kiit-edubuddy

Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
Run the App
bash
Copy
Edit
python app.py
Access in Browser
Open http://localhost:5000 in your web browser.

Testing:
Test Case ID	Test Description	Expected Outcome
T01	Query Handling	Relevant questions returned
T02	File Download	Downloads in chosen format work correctly
T03	Model Accuracy Test	≥ 90% accuracy on known inputs
T04	UI Responsiveness	Works on all screen sizes
T05	Frontend-Backend Integration	Smooth communication between layers

Performance Highlights:
Achieved optimized performance using TinyLlama model for CPU-only environments
Integrated real-time analytics for question trend visualization
Maintained < 2-second response latency for most queries

Future Scope:
Dual views for Students & Teachers
GPU-backed LLM integration (Falcon, DeepSeek)
AI-generated mock tests & topic-wise study plans
OCR-based document input from handwritten notes
Cloud deployment and mobile optimization
Collaborative study groups with shared chat features

Contributors:
Abhishree Bhadra
Ananya Srivastava
Ananya Dash 
Uttkarsh Anand

License:
This project is developed as a part of the academic curriculum under KIIT University and is subject to educational use. For collaboration or licensing inquiries, please contact the project contributors.


