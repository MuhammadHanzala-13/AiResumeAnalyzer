# AI RESUME ANALYZER
A Tool for Resume Analysis, Predictions and Recommendations

## About the Project
Parses resumes using NLP -> clusters keywords -> provides recommendations, predictions, analytics.

## Tech Stack
- Streamlit + Python + MySQL
- pandas, pyresparser, pdfminer3, Plotly, NLTK

## Client Features
- Basic info extraction
- Skill & keyword parsing
- Skill/course/job role suggestions
- Resume tips & video tips
- Scoring

## Admin Features
- View or download resumes
- Analytics: ratings, roles, experience, score, demographics

## Setup
1. Clone repo
2. Setup venv & install requirements
3. `python -m spacy download en_core_web_sm`
4. Create MySQL db `cv` & update credentials in `App.py`
5. Replace pyresparser resume_parser.py as instructed

## Usage
- Upload resume → get analysis
- Admin login: `admin` / `admin@resume-analyzer`
