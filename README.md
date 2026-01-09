# 🧑‍🍳 Mood-to-Menu: AI-Powered Culinary Recommendations

An end-to-end NLP application built with Python and Streamlit that suggests recipes based on the user's emotional state.

## 🚀 Features
- **Emotion Detection:** Uses a `DistilRoBERTa` transformer model to analyze text sentiment.
- **Smart Mapping:** Matches 7 core emotions to a curated database of 40+ international and Nepali recipes.
- **OOP Architecture:** Built using Object-Oriented Programming for modularity and scalability.
- **Optimized UI:** Implements Streamlit caching (`@st.cache_resource`) for near-instant response times.

## 🛠️ Tech Stack
- **Language:** Python 3.10+
- **AI Framework:** Hugging Face Transformers (PyTorch)
- **Data Handling:** Pandas
- **Web Framework:** Streamlit

## 📦 Installation
1. Clone the repo: `git clone https://github.com/YOUR_USERNAME/mood-to-menu.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `streamlit run 1_Mood_to_Menu.py`
