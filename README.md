# ✨ SkillPilot AI — Your Personal Career Planner

SkillPilot AI is an AI-powered career planning application built with Python and Streamlit. It helps students identify the skills needed for their target career, understand skill gaps, and create a personalized learning roadmap using Google's Gemini AI.

The project is designed to help students organize their learning journey with practical steps and useful learning resources.

## 🚀 Features

- **Personalized Career Roadmap:** Generate a learning plan based on your target career and available preparation time.
- **Skill Gap Analysis:** Identify important skills to learn based on your current skills and career goals.
- **AI-Powered Recommendations:** Use Gemini AI to generate practical learning suggestions and project ideas.
- **Free Learning Resources:** Access links to learning platforms, documentation, coding practice websites, and tutorials.
- **AI Toolkit:** Explore AI tools that can help with research, studying, programming, and presentations.
- **Interactive Dashboard:** View your career information through a clean, user-friendly interface.
- **Downloadable Report:** Download your personalized career roadmap as a text file.

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini AI
- LangChain
- `langchain-google-genai`
- `python-dotenv`

## 📁 Project Structure

```text
SkillPilot-AI/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Required Python packages
├── README.md           # Project documentation
├── .gitignore          # Files excluded from Git
├── .env                # API key for local development
└── .venv/              # Python virtual environment
```

**Note:** `.env` and `.venv/` should not be uploaded to GitHub.

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or a compatible version supported by your installed packages
- Git
- A Google Gemini API key
- Visual Studio Code or another code editor

### Step 1: Clone the repository

```bash
git clone https://github.com/vedasriveerannapet-source/SkillPilot-AI.git
cd SkillPilot-AI
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Configure your Gemini API key

Create a file named `.env` in the project root directory and add:

```dotenv
GOOGLE_API_KEY=your_actual_api_key
GEMINI_MODEL=your_working_model_name
```

Replace the example values with your own API key and the Gemini model name that works with your account.

Keep this file private. Never commit your API key to GitHub.

### Step 5: Run the application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:8501
```

## 📚 Learning Resources

SkillPilot AI provides links to resources that can help students learn and practise skills, including:

- [Kaggle Learn](https://www.kaggle.com/learn/)
- [freeCodeCamp](https://www.freecodecamp.org/learn/)
- [Google Colab](https://colab.research.google.com/)
- [Microsoft Learn](https://learn.microsoft.com/training/)
- [SQLBolt](https://sqlbolt.com/)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [GitHub Skills](https://skills.github.com/)
- [Python Documentation](https://docs.python.org/3/tutorial/)

Availability, course access, and optional paid features may vary by platform.

## 🔐 Security

- Store API keys in environment variables or a secrets manager.
- Keep `.env` out of version control.
- Never publish API keys, passwords, or private credentials.
- For online deployment, configure secrets through the hosting platform rather than hardcoding credentials.

## 🎯 Project Goal

The goal of SkillPilot AI is to make career preparation more organized and accessible by helping students understand what to learn, where to learn it, and how to practise toward their career goals.

## 🔮 Future Enhancements

- Save student progress between sessions.
- Add skill-specific AI practice tasks and quizzes.
- Track learning milestones.
- Generate downloadable PDF roadmaps.
- Add personalized project recommendations.
- Deploy the application online for public access.

## 👩‍💻 Author

Created as a student project to explore AI-powered career guidance, Python development, and practical applications of generative AI.

## 📄 License

This project is available for educational and personal learning purposes. A formal open-source license can be added if you choose to distribute the project under specific reuse terms.
