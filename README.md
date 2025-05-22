#  Text Emotion Detection App

A simple web application that detects **emotions from text** using machine learning. Enter any sentence, and the app will analyze it and return the detected emotion such as **happy**, **sad**, **angry**, etc.

🌐 **Live Demo**: [https://textemotiondetect.streamlit.app/](https://textemotiondetect.streamlit.app/)

## 🚀 Features

* ✍️ Accepts free-form text input
* 🧠 Uses a trained machine learning model to detect emotions
* 📊 Displays the predicted emotion and confidence
* 🧾 Clean and responsive UI with **Streamlit**
* ⚡ Deployed and accessible online 24/7

## 📦 Tech Stack

* 🐍 Python
* 📚 scikit-learn / Transformers (depending on your model)
* 🌐 Streamlit (for frontend)
* 🧠 NLP techniques for text preprocessing and classification

## 🛠 How It Works

1. User enters a sentence (e.g., *"I'm feeling awesome today!"*).
2. Text is cleaned and preprocessed.
3. A pre-trained emotion detection model makes a prediction.
4. The predicted emotion is shown with confidence/probability.

## 🧪 Example Emotions Detected

* 😄 Happy
* 😢 Sad
* 😡 Angry
* 😨 Fear
* 😐 Neutral
* 😍 Love


## ▶️ Run Locally

```bash
git clone https://github.com/your-username/text-emotion-detect.git
cd text-emotion-detect
pip install -r requirements.txt
streamlit run app.py
```
