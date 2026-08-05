# 📚 Interactive Study Assistant

An AI-powered **Interactive Study Assistant** built using **Google Gemini API** and **Gradio**. This application allows users to ask academic questions and receive responses in different personalities such as **Friendly**, **Academic**, or any other predefined persona.

---

## 🚀 Features

- 🤖 Powered by Google Gemini API
- 🎭 Multiple AI personalities
- 💬 Interactive Gradio-based user interface
- ⚡ Real-time AI-generated responses
- 🔐 Secure API key management using `.env`

---

## 🛠️ Tech Stack

- Python
- Google Gemini API (`google-genai`)
- Gradio
- python-dotenv

---

## 📂 Project Structure

```
InteractiveStudyAssistant/
│
├── app.py              # Main application
├── .env                # Gemini API Key
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/InteractiveStudyAssistant.git
cd InteractiveStudyAssistant
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file in the project directory.

```env
GEMINI_API_KEY=your_gemini_api_key
```

---

## ▶️ Run the Application

```bash
python app.py
```

The Gradio application launches using:

```python
demo.launch(server_name="0.0.0.0", root_path="/gradio")
```

---

## 💻 User Interface

### Inputs

- **Question Textbox**
  - Enter any academic question.

- **Personality Selector**
  - Friendly
  - Academic
  - (Additional personalities can be added.)

### Output

- AI-generated response based on the selected personality.

---

## 📖 How It Works

1. Loads the Gemini API key from the `.env` file.
2. Initializes the Google Gemini client.
3. Accepts a user question and selected personality.
4. Sends the request to Gemini with a system instruction based on the selected personality.
5. Displays the generated response in the Gradio interface.

---

## 📌 Example

### Question

```
Explain Generative AI.
```

### Personality

```
Academic
```

### Output

```
Generative AI is a branch of Artificial Intelligence that focuses on creating new content such as text, images, code, audio, and videos using deep learning models...
```

---

## 📦 Dependencies

- google-genai
- gradio
- python-dotenv

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Enhancements

- 🌍 Multi-language support
- 🎤 Voice-based interaction
- 📄 PDF-based study assistant
- 📝 Quiz generation
- 📚 Conversation history
- 🔍 RAG-based document understanding

---

## 👨‍💻 Author

**Aniruth Reddy Devarapelly**

- LinkedIn: [https://linkedin.com/in/your-profile](https://www.linkedin.com/in/aniruthreddy/)
- GitHub: https://github.com/ANIRUTHREDDY3071

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
