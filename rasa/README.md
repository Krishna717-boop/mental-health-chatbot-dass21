# 🧠 Student Mental Health Chatbot (DASS-21 Powered) 🤖

![Rasa](https://img.shields.io/badge/built%20with-Rasa-blue)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Welcome to my Mental Health Chatbot for students living away from home, powered by Rasa and trained on real DASS-21 responses from diverse Indian universities.

## 💡 Project Highlights

- **Conversational AI**: Understands and responds to mental health queries.
- **Custom Data**: Trained on real, anonymized DASS-21 survey data.
- **Empathy First**: Offers support, encouragement, and can walk users through DASS-21 questions.
- **Open Source**: Feel free to fork, star, and contribute!

## 📂 Project Structure
rasa/
│
├── data/
│ ├── nlu.yml
│ ├── stories.yml
│ └── rules.yml
├── models/
├── actions/
├── config.yml
├── domain.yml
├── endpoints.yml
├── credentials.yml
└── DASS-21-Assessment-1-Responses-1.xlsx

## 🚀 Quickstart
git clone https://github.com/yourusername/mental-health-chatbot.git
cd mental-health-chatbot
pip install rasa
rasa train
rasa shell
