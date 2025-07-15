# 🤖 Simple OpenAI Chatbot

A basic chatbot web app built using **Flask** and **OpenAI API**.  
It features a simple HTML/CSS interface and communicates with GPT via backend calls.  
The OpenAI API key is managed securely through environment variables.

---

## 🔧 Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS
- **API**: OpenAI GPT models
- **Environment Management**: python-dotenv
- **Templating**: Flask render_template

---

## 🚀 Features

- User-friendly web interface
- Sends user input to OpenAI's API and returns generated responses
- Secure API key handling via `.env` file
- Easy to run locally with minimal setup

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sina-Rezaeii/Chatbot-Final.git
   cd Chatbot-Final
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate
   ```

3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Create a `.env` file in the root directory and add your OpenAI API key:**
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

5. **Run the app:**
   ```bash
   python app.py
   ```

6. **Open your browser and go to:**
   ```
   http://127.0.0.1:5000
   ```

---

## 📁 Project Structure

```
Chatbot-Final/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── styles.css
├── .env (not uploaded)
└── requirements.txt
```

---

## 📌 Notes

- This is a beginner-friendly project. No AI model training is needed—OpenAI does the heavy lifting.
- You must have an OpenAI API key to run this project.
- For deployment, make sure to hide your `.env` file properly.

---

## 🧠 Author

Made with 💻 by Sina Rezaei  
📬 [rezaeii.sina.gh@gmail.com](mailto:rezaeii.sina.gh@gmail.com)
