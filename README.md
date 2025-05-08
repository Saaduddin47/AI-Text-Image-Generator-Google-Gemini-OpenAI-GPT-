
```markdown
# 🌐 Multi-LLM Prompt App with Streamlit

This Streamlit web app allows you to interact with two powerful large language models (LLMs):  
- **OpenAI's GPT-4o** (for text and image generation)  
- **Google's Gemini 1.5 Flash** (for text generation)

Easily send prompts, receive responses, and visualize AI outputs through a simple user interface.

---

## 🚀 Features

- 🔤 **Text Generation with OpenAI GPT-4o**
- 🎨 **Image Generation using DALL·E 3**
- 🧠 **Text Generation with Google Gemini**
- 🖥️ Interactive UI powered by Streamlit

---

## 📁 Project Structure

```

.
├── app.py                # Main Streamlit application
├── gpt\_wrapper.py        # Functions for OpenAI GPT & DALL·E
├── gemini\_wrapper.py     # Functions for Google Gemini
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── .streamlit/
└── secrets.toml      # API keys (excluded from GitHub)

````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/llm-streamlit-app.git
cd llm-streamlit-app
````

### 2. (Optional) Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Add API Keys

Create a `.streamlit/secrets.toml` file in the root folder:

```toml
api_key = "your_openai_api_key"
api_key_google = "your_google_gemini_api_key"
```

> ⚠️ **Do not share your secrets.toml publicly or push it to GitHub!**

---

## ▶️ Running the App

```bash
streamlit run app.py
```

This will open a browser window with the app running.

---

## 📦 requirements.txt

```
openai
google-generativeai
streamlit
requests
```

You can install these with:

```bash
pip install -r requirements.txt
```

---

## 📸 Optional: Image Output

If using the OpenAI image generation feature, the image is saved as `output_image.png` in your working directory.

---

## 📜 License

MIT License. You are free to use, modify, and distribute this software.

---

## 🤝 Contributions

Pull requests and feature suggestions are welcome. Please open an issue to start a discussion before making major changes.

---

## 🙋‍♂️ Author

Syed Saaduddin Azhaan
[LinkedIn](https://www.linkedin.com/in/syed-saaduddin-b7682726b/) | [GitHub](https://github.com/Saaduddin47)

```

