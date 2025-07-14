# Reddit User-Persona Generator 
  
It scrapes a Reddit user's posts and comments, then generates a structured **persona profile** using **OpenAI's GPT-4**, with citations from the user's content.

---

## 🚀 Features

✅ Scrape a Reddit user's public posts & comments  
✅ Build a persona using GPT-4 (or GPT-4o)  
✅ Output includes cited traits like tone, interests, political leaning, etc.  
✅ Output saved as `.txt` per user  
✅ PEP-8 compliant, clean and modular code  
✅ Fully CLI- and notebook-compatible

---

## 🛠 Requirements

Install Python dependencies:

```bash
pip install -r requirements.txt
# Reddit_persona
File: requirements.txt:
praw>=7.7.0
openai>=1.12.0
