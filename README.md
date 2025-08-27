# <img src="https://i.ibb.co/BVXgJLNT/vlogger-unscreen.gif" width="50"> PersonaPath – Personalized Career & Skills Advisor <img src="https://i.ibb.co/BVXgJLNT/vlogger-unscreen.gif" width="50">

A ready-to-run website built with **HTML, CSS, JS** on the frontend and **Python (Flask)** on the backend.

## <img scr="https://i.ibb.co/KxbbVzdb/features-unscreen.gif" width="50"> Features
- Cool **glassmorphism login** with subtle animations 🪟✨  
- **Career advisor chat** backed by a rules engine and dataset 💬🤖  
- **500+ skills & careers** with bullets, paths, and learning links 📚🔗  
- **Dark/Light** theme toggle with glowing **sun/moon** button 🌞🌙  
- Transparent blur effects, glowing active tabs, and micro-interactions ✨🖱️  
- **Hover to flip** skill/career cards to reveal bullets and links 🔄📇  
- Home page includes a **career journey SVG** illustration (right side) 🗺️🚀  

## <img src="https://i.ibb.co/zhfJJvRJ/technology-unscreen.gif" width="50"> Tech Stack

| Layer       | Technology Used |
|-------------|-----------------|
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Backend**  | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) |
| **Data**     | ![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white) |


## <img src="https://i.ibb.co/qYCVCxxK/video-unscreen.gif" width="50"> Run locally (VS Code)
1. Ensure Python 3.10+ is installed. 🐍✅  
2. Create a virtual environment (recommended):  
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows: .venv\Scripts\activate

   ```
3. Install dependencies:
   ```bash
   pip install flask
   ```
4. Start the app:
   ```bash
   python app.py
   ```
5. Open http://localhost:5000 in your browser.

## <img src="https://i.ibb.co/DfQcFbqd/add-folder-unscreen.gif" width="50"> Project structure
```
career_advisor_site/
  app.py
  data/skills_careers.json
  static/
    styles.css
    theme.js
    explore.js
    dashboard.js
    chat.js
  templates/
    base.html
    index.html
    login.html
    dashboard.html
    chat.html
    explore.html
```

## <img src="https://i.ibb.co/nNRCNCHc/notebook-unscreen.gif" width="50"> Notes
- The chat uses deterministic rules + search to return **exact data** where possible.
- Replace/add items in `data/skills_careers.json` to customize content.
- You can deploy to any Python-friendly host (Render, Railway, etc.).
