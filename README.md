# AI-Powered-Calorie-Tracker-and-Nutrient-Assistant
Great! Here's your **final GitHub-ready `README.md`** version with everything you need, including:

* 📛 Badges (build, license, stars, etc.)
* 📌 GitHub topics
* 🌐 Deployment suggestions (Streamlit & Hugging Face Spaces)

---

````markdown
# 🥗 AI Powered Calorie Tracker and Nutrient Assistant

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![OpenAI](https://img.shields.io/badge/API-OpenAI-blue?logo=openai)]
[![Gradio](https://img.shields.io/badge/UI-Gradio-orange?logo=gradio)]
[![Stars](https://img.shields.io/github/stars/YOUR_GITHUB_USERNAME/ai-calorie-tracker?style=social)](https://github.com/YOUR_GITHUB_USERNAME/ai-calorie-tracker)

An interactive AI-based **nutrition assistant** that logs meals and provides **calorie & nutrient information** using natural language.  
Built using **OpenAI**, **LangChain**, **Gradio**, and food data APIs from **Nutritionix** and **USDA**.

---

## 🔧 Features

- 🧠 Natural language meal logging (_e.g., "I had oats and almond milk"_)
- 🔍 AI-powered food parsing via **LangChain + OpenAI**
- 🍽 Calorie & macro breakdown from Nutritionix & USDA
- 🎨 Beautiful **Gradio-based UI**
- 📝 Real-time chatbot-style logging experience

---

## 📦 Installation

Install required packages:

```bash
pip install -r requirements.txt
````

<details>
<summary>📋 Sample <code>requirements.txt</code></summary>

```text
openai
langchain
gradio
python-dotenv
requests
```

</details>

---

## 🔑 API Keys Setup

Create a `.env` file in your project root:

```env
OPENAI_API_KEY=your_openai_key
NUTRITIONIX_APP_ID=your_nutritionix_app_id
NUTRITIONIX_API_KEY=your_nutritionix_api_key
USDA_API_KEY=your_usda_api_key
USDA_API_URL=https://api.nal.usda.gov/fdc/v1/foods/search
```

🎯 Get API keys from:

* [OpenAI](https://platform.openai.com/account/api-keys)
* [Nutritionix](https://developer.nutritionix.com/)
* [USDA FDC](https://fdc.nal.usda.gov/api-key-signup.html)

---

## 🚀 Running the App

### Option 1: Jupyter Notebook

```bash
Open: AI Powered Calorie Tracker and Nutrient Assistant.ipynb
Run all cells sequentially
```

### Option 2: Python Script

```bash
python app.py
```

---

## 🌐 Deploy Your App Online

### ✅ Option 1: Streamlit Cloud

1. Convert code into a `streamlit_app.py`
2. Push to GitHub
3. Deploy on [Streamlit Cloud](https://streamlit.io/cloud)

### ✅ Option 2: Hugging Face Spaces

1. Create a `space` using **Gradio**
2. Push your repo with `README.md`, `requirements.txt`, and `app.py`
3. Deploy at [huggingface.co/spaces](https://huggingface.co/spaces)

---

## ⚠ Troubleshooting

### ❌ OpenAI Quota Error

```bash
openai.RateLimitError: Error code: 429 - You exceeded your current quota...
```

✅ Fix by:

* Checking [OpenAI Usage](https://platform.openai.com/account/usage)
* Adding [Billing Info](https://platform.openai.com/account/billing)

---

### ⚠ LangChain Deprecation Warning

```bash
LangChainDeprecationWarning: LangChain agents will continue to be supported...
```

✅ You may safely ignore it or explore [LangGraph](https://www.langchain.com/langgraph)

---

## 📁 Project Structure

```
📦 project-root/
 ┣ 📜 AI Powered Calorie Tracker and Nutrient Assistant.ipynb
 ┣ 📜 app.py
 ┣ 📜 .env
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📜 LICENSE
```

---

## 🙋‍♀️ Author

**Aishwarya M. Bharadwaj**
📍 *Maharaja Institute of Technology*
🧠 *CSE - AI Department*

---

## ⭐️ Show Your Support

If you found this project helpful:

✅ Star this repo
✅ Share with friends
✅ Fork and build your own health app!

---

## 🏷 GitHub Topics

```text
ai-nutrition · calorie-tracker · langchain · gradio-app · openai-api · health-tech
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

```

---

Let me know if you want help:

- generating the `LICENSE` file,
- creating `app.py` from your notebook,
- or auto-deploying on Streamlit/Hugging Face with live preview.
```
