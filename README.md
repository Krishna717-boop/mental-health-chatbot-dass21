# 🧠 Mental Health Chatbot - DASS21

This project is a conversational AI chatbot built with [Rasa](https://rasa.com/) to support students' mental well-being in hostel environments. It uses the DASS-21 scale (Depression, Anxiety, and Stress Scale) to assess mental health status and provide empathetic responses, coping tips, and relevant resources.

---

## 🗂️ Project Structure

mental-health-chatbot-dass21/
├── rasa/
│ ├── actions/ # Custom action scripts (e.g., scoring DASS-21)
│ ├── data/ # NLU data, stories, rules
│ ├── models/ # (Model files not tracked in Git)
│ ├── tests/ # Test stories for automated tests
│ ├── config.yml # NLU pipeline and policies
│ ├── credentials.yml # Channel credentials
│ ├── domain.yml # Intents, entities, responses, actions
│ ├── endpoints.yml # Action server and tracker store config
│ └── requirements.txt # Python dependencies

yaml
Copy
Edit

---

## 🚀 Features

- 📋 **DASS-21 Questionnaire**: Asks users 21 validated questions to assess their emotional state.
- 🎯 **Dynamic Scoring**: Calculates scores and classifies stress, anxiety, and depression levels.
- 💬 **Empathetic Dialogue**: Provides supportive and context-aware replies.
- 📚 **Self-help Resources**: Recommends mindfulness exercises, helplines, and campus support.
- 🧠 **Custom Actions**: Uses Python logic to interpret user responses and manage session flow.

---

## 🔧 Setup Instructions

1. **Clone the repo:**

```bash
git clone https://github.com/YOUR_USERNAME/mental-health-chatbot-dass21.git
cd mental-health-chatbot-dass21/rasa
Create a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Train the model:

bash
Copy
Edit
rasa train
Run the action server:

bash
Copy
Edit
rasa run actions
Start the chatbot:

bash
Copy
Edit
rasa shell
💾 Model Download (Optional)
Pretrained model is not included due to file size.
If you'd like to use the latest pretrained model:

bash
Copy
Edit
bash get_model.sh
(Make sure you have the get_model.sh script with a valid download link)

🧪 Testing
Run automated test stories:

bash
Copy
Edit
rasa test
📌 Use Cases
University or hostel mental health support

Anonymous preliminary mental health screening

Resource distribution and awareness campaigns

